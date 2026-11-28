# Conclusiones

## Conclusiones y recomendaciones

Esta sección presenta las conclusiones a la fecha de la entrega AV2. Las entrevistas de validación (sección 5.3) aportan una primera señal sobre las hipótesis del Lean UX Process, que se resume en la tabla de contraste de esta sección. Las conclusiones se apoyan además en el análisis de las entrevistas de needfinding, en el diseño del producto, en el Landing Page, en la Frontend Web Application y en los RESTful Web Services desplegados.

**Conclusiones**

- **Problema.** Las seis entrevistas de needfinding (tres por segmento) respaldan el Problem Statement: los tres adolescentes identifican los ruidos fuertes y las aglomeraciones como detonantes (100 %), se aíslan para calmarse (100 %) y evitan hablar durante la crisis (100 %); los cuidadores que atienden crisis sensoriales (67 %) consideran poco prácticas o infantiles las herramientas digitales actuales. Esto sostiene los assumptions UA2 y UA4 y la brecha de apoyo inmediato durante el episodio.
- **Confianza profesional.** El 100 % de los cuidadores entrevistados condiciona su adopción al respaldo explícito de profesionales de la salud, lo que confirma el assumption UA5 y la necesidad de mantener explícita la restricción de que Nubi no reemplaza la atención profesional.
- **Hallazgo que matiza una hipótesis.** Una de las tres cuidadoras entrevistadas (33 %) priorizó una comunidad de testimonios entre madres antes que un botón de crisis inmediata. Este caso debe contrastarse en la validación, pues afecta el supuesto FA1 (Modo SOS de un solo toque) para cuidadores que priorizan el apoyo entre pares.
- **Alcance del producto.** El dominio se organizó en cinco Bounded Contexts (Perfil y Personalización, Gestión de Crisis, Autorregulación, Comunicación Asistida y Red de Apoyo y Seguimiento), con 48 User Stories, 5 Technical Stories y 5 Landing Page Stories priorizadas en el Product Backlog.
- **Implementación.** El Sprint 1 entregó y desplegó la primera versión del Landing Page, responsive, bilingüe (English y Latin American Spanish) y con términos de uso enlazados desde el footer. El Sprint 2 implementó la primera versión de la Frontend Web Application con Angular, que integra en la rama `develop` los cinco Bounded Contexts y usa una API simulada con json-server hasta que se implementen los RESTful Web Services. De las 29 User Stories comprometidas (77 Story Points), 23 quedaron completas (62 Story Points); US-25, US-26 y US-29 quedaron en proceso porque el panel de Red de Apoyo y Seguimiento aún usa datos de muestra, y US-22, US-24 y US-28 quedaron pendientes y pasan al Sprint 3.
- **Web Services.** En el Sprint 3 los cinco Bounded Contexts se implementaron como RESTful Web Services con Java, Spring Boot y Spring Data JPA en el repositorio Nubi.Platform.Backend, con 138 commits sin merges de los cinco integrantes. Las ramas se integraron en `develop` el 13 y el 14 de noviembre, se publicaron las versiones `v1.0.0` a `v1.2.0` y los servicios quedaron desplegados en Render con Swagger UI, que documenta 92 operaciones en 16 etiquetas. La Frontend Web Application, desplegada en Firebase Hosting, consume estos servicios y reemplazó a la API simulada.
- **Integración de las ramas.** Cada Bounded Context se desarrolló en su propia rama. Al integrarlos se resolvió el conflicto de rutas de las recomendaciones (las de Gestión de Crisis cuelgan de `/profiles/{profileId}/recommendations` y las de Red de Apoyo y Seguimiento de `/support-network/recommendations`) y se agregaron los contextos de IAM y Rutina Visual, que no figuran en el Capítulo IV.
- **Mejora continua.** A partir de la retroalimentación del docente sobre TB1, el equipo estimó todas las tareas de los Sprint Backlog entre 4 y 8 horas, corrigió la evidencia de colaboración del Sprint 1, documentó las acciones HTTP y los ejemplos de la API simulada, registró los commits del Landing Page del Sprint 2 y la desviación respecto de GitFlow (commits directos en `master`), y alineó el segmento objetivo (personas autistas y sus padres) en las User Stories, el Sprint Backlog 2 y las Conclusiones.
- **Limitaciones del despliegue.** Los servicios desplegados usan una base H2 en memoria, por lo que los datos se reinician cuando Render reinicia el servicio, y el servicio tarda cerca de un minuto en despertar tras un periodo sin uso. Además, las operaciones confían en la cabecera `X-Account-Id` que devuelve el inicio de sesión y no en un token firmado.
- **Colaboración en el Sprint 3.** Los cinco integrantes registran commits en los Web Services, pero la Frontend Web Application se reconstruyó en dos días (13 y 14 de noviembre) y solo registra commits de un integrante, y las tareas del Landing Page (T-04, T-76 y T-77) quedaron sin cerrar.
- **Colaboración.** Los cinco integrantes registran commits en el informe y en la Frontend Web Application durante el Sprint 2, pero en el Landing Page solo participaron tres. Además, 81 de los 87 commits de `develop` de la Frontend Web Application (93 %) se registraron el último día del Sprint, lo que redujo el margen de revisión; por ello se recomienda integrar cada rama `feature/*` al completarse cada User Story.
- **Modo SOS frente al Problem Statement.** El Modo SOS se activa con un solo toque (FA1) y guía al cuidador paso a paso, priorizando los pasos según las sensibilidades del perfil. Cada sesión registra su estado (finalizada o finalizada anticipadamente) y su duración. Con estos datos ya es posible medir dos criterios de éxito del Problem Statement: el porcentaje de activaciones que termina con la guía completada (meta de 80 %) y la reducción de la duración de los episodios (meta de 25 % tras cuatro semanas de uso).
- **Diferencia entre la hipótesis y la implementación.** La hipótesis H1 plantea guías de máximo tres pasos, pero la guía implementada tiene seis. Queda por validar con usuarios si la cantidad de pasos afecta el porcentaje de cuidadores que completan la guía.
- **Limitación frente a los assumptions.** El assumption UOA6 (uso sin conexión a internet) no está cubierto: la Frontend Web Application depende de la API y no funciona sin conexión.

**Recomendaciones**

1. Realizar las entrevistas de validación con usuarios de los dos segmentos sobre el Landing Page y la Frontend Web Application conectada a los Web Services, y medir las métricas definidas en el Lean UX Canvas (por ejemplo, 80 % de cuidadores que completan la guía del Modo SOS).
2. Incluir en las validaciones a niños de 6 a 12 años: los adolescentes entrevistados tienen entre 15 y 17 años.
3. Contrastar en la validación una guía de tres pasos con la de seis pasos del Modo SOS, y conservar la que obtenga mayor porcentaje de guías completadas.
4. Registrar la intensidad inicial del episodio al activar el Modo SOS. Hoy toda sesión empieza con intensidad alta por defecto, y la comparación con la intensidad final depende de ese dato.
5. Habilitar el uso sin conexión de la guía del Modo SOS (UOA6), de modo que el cuidador pueda usarla con datos móviles limitados.
6. Reemplazar la base H2 en memoria del despliegue por una base MySQL persistente, y registrar en el Capítulo IV los contextos de IAM y Rutina Visual que se agregaron al backend.
7. Validar con usuarios el flujo de registro, inicio de sesión y suscripción (US-46 a US-48), y ajustar el plan Premium según la disposición de pago de los cuidadores.
8. Implementar las historias de seguimiento y recomendaciones de Red de Apoyo y Seguimiento (US-30 a US-45), que no forman parte del compromiso del Sprint 2.
9. Reemplazar los testimonios de ejemplo del Landing Page por testimonios reales obtenidos en las entrevistas de validación.
10. Unificar el modelo de recomendaciones de Gestión de Crisis y de Red de Apoyo y Seguimiento, que hoy exponen rutas y modelos distintos.
11. Integrar cada rama `feature/*` en `develop` al completar cada User Story y distribuir los commits a lo largo del Sprint, para evitar la concentración de commits en el último día que se repitió en los Sprint 2 y 3.
12. Reemplazar el envío del identificador de cuenta en la cabecera `X-Account-Id` por un token firmado que emita el inicio de sesión de la cuenta (US-46 y US-47) antes de publicar la versión de producción.

## Contraste con las hipótesis de Lean UX

La tabla contrasta cada Hypothesis Statement (sección 1.2.2.3) con los resultados de las seis entrevistas de validación de la sección 5.3.2.

| Hipótesis | Criterio de éxito | Evidencia de la validación | Resultado | Conclusión |
|---|---|---|---|---|
| H1 (FA1): Modo SOS de un solo toque con guías de máximo tres pasos | 5 % de las cuentas gratuitas pasa a un plan Premium; 80 % de las activaciones termina con la guía completada | 3 de 3 padres o familiares completaron la guía del Modo SOS (UF-4: 2 solos y 1 con ayuda). Los tres consideraron clara la guía y adecuada su cantidad de pasos | Sin concluir: 2 de 3 sin ayuda (67 %) frente a la meta de 80 % | La guía de seis pasos no impidió completarla en esta muestra de tres participantes. La conversión a Premium no se mide con entrevistas: Johan lo considera más conveniente, Carmen pagaría por él y Lizeth no respondió. |
| H2 (FA2): Interfaz de autorregulación personalizable | 40 % de los usuarios activos sigue usando la aplicación cada semana al tercer mes | 3 de 3 participantes completaron el flujo de autorregulación (UF-1). Probabilidad de uso: 3, 4 y 4 sobre 5 | Señal favorable, con observaciones de diseño sensorial | La interfaz se usa sin ayuda. Un participante señaló colores fluorescentes y elementos pequeños (sección 5.3.3). La retención semanal requiere datos de uso. |
| H3 (FA3): Tablero CAA con pictogramas y salida de voz | 30 % de los nuevos usuarios llega por recomendación | 2 de 3 personas autistas usaron el tablero de pictogramas (UF-2) y 2 de 3 padres lo configuraron (UF-5); los tres padres opinan que serviría para comunicarse en una crisis | Señal favorable | El tablero se entiende, aunque Sebastián no comprendió las opciones «entendí» y «no entendí». La salida de voz y las recomendaciones de uso no se midieron. |
| H4 (FA4): Perfil sensorial con detonantes, preferencias y contactos de confianza | 40 % de los usuarios activos sigue usando la aplicación cada semana al tercer mes | 3 de 3 padres o familiares crearon el perfil sin dificultad y consideraron necesarios los datos solicitados (UF-3) | Señal favorable | El perfil sensorial se completa sin ayuda. El término «archivar» generó dudas. La retención semanal requiere datos de uso. |
| H5 (FA5): Solicitud de ayuda y registro de episodios | Cinco colegios o centros de terapia contratan el plan institucional en doce meses; 80 % de los usuarios logra enviar una solicitud de ayuda y 70 % de los padres considera útil el reporte | 3 de 3 padres o familiares entendieron lo que ocurre después de confirmar una necesidad y valoraron el resumen del episodio (UF-6) | Señal parcial: no se midió el envío de solicitudes ni la utilidad del reporte | Los tres condicionan su confianza al respaldo de un profesional de la salud. La contratación institucional no se mide con entrevistas. |

Los criterios de la tabla son los de negocio de los Hypothesis Statements (1.2.2.3) y requieren datos de uso a largo plazo. El Lean UX Canvas (1.2.2.4) define además criterios para pruebas de uso, que se contrastan en la matriz de trazabilidad de la sección 5.3.2.

## Cierre de observaciones AV1

Estado de los ocho hallazgos del AV1 al 28/11/2026. «Cerrado» indica que la corrección está en el informe; «Parcial» o «Abierto», que falta trabajo o evidencia.

| Hallazgo | Antes (AV1) | Después (evidencia) | Estado | Pendiente |
|---|---|---|---|---|
| H-01 Trazabilidad estratégica | El Impact Mapping cubría un subconjunto de historias | [Matriz de las 58 historias](Chapter-3.md#321-matriz-de-trazabilidad-estratégica) | Cerrado | Actualizar el gráfico del Impact Mapping |
| H-02 «Para» operativo | Sin justificar su aporte al objetivo | Columna «Contribución» de la misma matriz | Cerrado | — |
| H-03 Criterios de aceptación | Profundidad a mantener | Las 58 historias tienen al menos dos Scenarios ([3.1](Chapter-3.md#31-user-stories)); matriz de cierre del Sprint 3 | Parcial | Revisar restricciones y autorización; TS-05 E2 parcial ([Pull Request #1 del backend](https://github.com/ASI0729-2620-7793-Open-Source/Nubi.Platform.Backend/pull/1), publicado en Render el 28/11/2026) |
| H-04 Diagramas de clases densos | Diagramas reducidos | [Diagramas](Chapter-4.md#471-class-diagrams) ampliables a resolución completa | Parcial | Dividir por Aggregate |
| H-05 Colaboración en Landing Page | Concentrada en un integrante | [Conciliación por repositorio](Chapter-5.md#5238-team-collaboration-insights-during-sprint): cuatro integrantes con commits acumulados | Abierto | Aporte de Edgard y reparto del trabajo en el Sprint |
| H-06 `main` / `master` | Uso ambiguo | [Convención real por repositorio](Chapter-5.md#512-source-code-management) | Parcial | Renombrar `master` en el Landing Page |
| H-07 Mensajes de commit | Errores de redacción | [Reglas de redacción](Chapter-5.md#512-source-code-management) | Parcial | Demostrar su cumplimiento en nuevos commits |
| H-08 Densidad documental | Capturas y diagramas pequeños | [Índice de evidencias](README.md#índice-de-evidencias) y diagramas ampliables | Parcial | Ampliar capturas densas y verificar el documento exportado |

## About the Team

El equipo de Macally está formado por cinco estudiantes que desarrollan Nubi, una plataforma web de apoyo para personas autistas y sus padres durante episodios de desregulación emocional o sensorial. Durante el proyecto trabajaron con GitFlow, Conventional Commits, Trello para el Product Backlog y los Sprint Backlog, Figma para el diseño y reuniones por Google Meet y WhatsApp. Desde el Sprint 2 cada integrante lidera un Bounded Context y lo desarrolla de extremo a extremo: primero en la Frontend Web Application y, en el Sprint 3, en los Web Services.

| Integrante | GitHub | Aporte durante el proyecto |
|---|---|---|
| Lopez Torres, Leonardo Gabriel (Team Leader) | LeonardoLopez138 | Startup Profile, Big Picture Event Storming, User Stories, diseño UX/UI de la Web Application, internacionalización del Landing Page, Comunicación Asistida (CAA), despliegue en Firebase y Render, y proyecto base del backend. |
| Diaz Yurivilca, Sofia | u20241a195-cmd | Lean UX Canvas, segmentos objetivo, análisis competitivo, Empathy Mapping, Product Backlog, Gestión de Crisis (Modo SOS) y su integración en `develop`. |
| Payano Puchuri, Joan Fabricio | joanfpp2-ai | Arquitectura de software dirigida por dominio, Autorregulación, base de la Frontend Web Application, sección de video About-the-Team del Landing Page y alineación del Capítulo IV. |
| Ruiz Villegas, Yngrid Nahir | nahiryn8 | Diseño y registro de entrevistas, User Stories, Style Guidelines, Perfil y Personalización y sección de video About-the-Product del Landing Page. |
| Diaz Caruzo, Edgard Daniel | Dan-trax | User Task Matrix, User Journey Mapping, Impact Mapping, Red de Apoyo y Seguimiento, documentación del contexto y licencia MIT. |

**Video About-the-Team.** El Landing Page incrusta una versión del video en su sección de equipo.

| Dato | Detalle                                                                                                                                                                                                                                                                                                              |
|---|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Título | `upc-pre-202620-1asi0729-7793-macally-about-the-team-sprint-3`                                                                                                                                                                                                                                                       |
| Formato | mp4                                                                                                                                                                                                                                                                                                                  |
| Duración | 8:51                                                                                                                                                                                                                                                                                                                 |
| URL en Microsoft Stream | https://sl1nk.com/penfp1q                                                                                                                                                                                                                                                                                            |
| Contenido | Escenas de sesiones de trabajo del equipo, narración del proceso, retrospectiva del grupo y el testimonio de cada integrante sobre sus actividades y los outcomes alcanzados. La duración sugerida es de 10 minutos: 5 de retrospectiva del grupo y 1 por cada uno de los cinco testimonios (Anexo C del enunciado). |

![img.png](images/Chapter-V/img.png)
 Captura de pantalla del video.

**Secuencias de la versión incrustada en el Landing Page** (duración 00:06:51, distinta de las 8:51 de la versión de Stream; tiempos aproximados, revisados el 28/11/2026 con fotogramas y sin audio):

| Inicio (hh:mm:ss) | Sección |
|---|---|
| 00:00:00 | Portada «About the team» |
| 00:00:05 | Testimonio 1 |
| 00:02:13 | Testimonio 2 |
| 00:03:25 | Testimonio 3 |
| 00:04:20 | Testimonio 4: Yngrid Ruiz (nombre rotulado en el video) |
| 00:05:57 | Testimonio 5 |

En esta versión no se observan las escenas de trabajo ni la retrospectiva del grupo. **Queda pendiente** rotular los testimonios, unificar la versión de Stream con la del Landing Page y publicar el video en YouTube.

**Retrospectiva del equipo.** Resumen de la retrospectiva del Sprint 3.

- **Qué funcionó:**
  - Repartir el trabajo por Bounded Context, con cada integrante en su propia rama, permitió implementar los Web Services entre el 4 y el 14 de noviembre de 2026.
  - Integrar con GitFlow y publicar versiones etiquetadas (`v1.0.0` a `v1.2.0`) dejó los servicios y la aplicación desplegados y verificables.
  - La documentación con OpenAPI (92 operaciones en 16 etiquetas) y las pruebas automáticas facilitaron revisar el trabajo de los demás.
  - Las entrevistas de validación con seis participantes de los dos segmentos dieron hallazgos concretos de usabilidad, que se registraron con su severidad.
**Problemas y decisiones del Sprint 3.**

| Problema observado | Decisión del equipo para el siguiente Sprint | Evidencia de cumplimiento |
|---|---|---|
| La Frontend Web Application quedó en una persona y en dos días | Asignar cada tarea al inicio y que su responsable haga el commit | Pendiente |
| Ramas con commits concentrados en un día | Revisar el avance a mitad del Sprint e integrar cada rama al terminarla | Pendiente |
| Tareas del Landing Page sin cerrar (T-04, T-76, T-77) | Integrar por Pull Request y desplegar antes del cierre | [Pull Request #1 del Landing Page](https://github.com/ASI0729-2620-7793-Open-Source/landing-page/pull/1) integrado y publicado el 27/11/2026 |
| Datos en memoria en el despliegue | Usar una base MySQL persistente | Pendiente |

- **Qué mejorar:** la comunicación dentro del equipo. La Frontend Web Application quedó en una sola persona y en dos días, varias ramas concentraron sus commits en un solo día y las tareas del Landing Page quedaron sin cerrar. Para el siguiente Sprint el equipo acuerda al inicio quién hace cada tarea, revisa el avance a mitad del Sprint e integra cada rama al terminarla.
- **Aprendizajes del equipo:**
  - Organizar un servicio en capas (dominio, aplicación, infraestructura e interfaces) con Spring Boot y JPA, separando el dominio de la persistencia.
  - Diseñar rutas REST con sustantivos y cambiar estados con `PATCH`.
  - Desplegar los servicios en Render y la aplicación en Firebase Hosting, y reconocer los límites del plan gratuito (arranque lento y datos en memoria).
  - Validar con usuarios reales: observar sin ayudar, registrar lo que ocurre y clasificar los problemas por severidad. Para personas autistas y sus padres pesan mucho el lenguaje claro y la baja carga sensorial.
  - Coordinar a cinco integrantes con GitFlow y Conventional Commits.
