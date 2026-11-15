# Conclusiones

## Conclusiones y recomendaciones

Esta sección presenta el avance de las conclusiones a la fecha de la entrega AV2. Las hipótesis del Lean UX Process todavía no se contrastan con usuarios, por lo que las conclusiones se apoyan en el análisis de las entrevistas de needfinding, en el diseño del producto, en el Landing Page, en la primera versión de la Frontend Web Application y en la primera versión de los RESTful Web Services. Las entrevistas de validación (sección 5.3) se realizan sobre el Landing Page y la Frontend Web Application, y sus resultados se incorporan en la versión final y en la tabla de contraste con las hipótesis de esta sección.

> **Borrador AV2.** Las conclusiones del Sprint 3 se redactaron con la evidencia disponible al 13 de noviembre de 2026. Los resultados de las validaciones están marcados como **[POR COMPLETAR]** hasta que se realicen las entrevistas.

**Conclusiones**

- **Problema.** Las seis entrevistas de needfinding (tres por segmento) respaldan el Problem Statement: los tres adolescentes identifican los ruidos fuertes y las aglomeraciones como detonantes (100 %), se aíslan para calmarse (100 %) y evitan hablar durante la crisis (100 %); los cuidadores que atienden crisis sensoriales (67 %) consideran poco prácticas o infantiles las herramientas digitales actuales. Esto sostiene los assumptions UA2 y UA4 y la brecha de apoyo inmediato durante el episodio.
- **Confianza profesional.** El 100 % de los cuidadores entrevistados condiciona su adopción al respaldo explícito de profesionales de la salud, lo que confirma el assumption UA5 y la necesidad de mantener explícita la restricción de que Nubi no reemplaza la atención profesional.
- **Hallazgo que matiza una hipótesis.** Una de las tres cuidadoras entrevistadas (33 %) priorizó una comunidad de testimonios entre madres antes que un botón de crisis inmediata. Este caso debe contrastarse en la validación, pues afecta el supuesto FA1 (Modo SOS de un solo toque) para cuidadores de personas con TDAH.
- **Alcance del producto.** El dominio se organizó en cinco Bounded Contexts (Perfil y Personalización, Gestión de Crisis, Autorregulación, Comunicación Asistida y Red de Apoyo y Seguimiento), con 48 User Stories, 5 Technical Stories y 5 Landing Page Stories priorizadas en el Product Backlog.
- **Implementación.** El Sprint 1 entregó y desplegó la primera versión del Landing Page, responsive, bilingüe (English y Latin American Spanish) y con términos de uso enlazados desde el footer. El Sprint 2 implementó la primera versión de la Frontend Web Application con Angular, que integra en la rama `develop` los cinco Bounded Contexts y usa una API simulada con json-server hasta que se implementen los RESTful Web Services. De las 29 User Stories comprometidas (77 Story Points), 23 quedaron completas (62 Story Points); US-25, US-26 y US-29 quedaron en proceso porque el panel de Red de Apoyo y Seguimiento aún usa datos de muestra, y US-22, US-24 y US-28 quedaron pendientes y pasan al Sprint 3.
- **Web Services.** En el Sprint 3 los cinco Bounded Contexts se implementaron como RESTful Web Services con Java, Spring Boot, Spring Data JPA y MySQL, en cinco ramas del repositorio Nubi.Platform.Backend con 112 commits de los cinco integrantes. Los endpoints se documentan con OpenAPI y los errores usan el formato RFC 9457. Al 13 de noviembre las ramas todavía no se integran en `develop` ni se despliegan, por lo que la Frontend Web Application sigue usando la API simulada hasta completar las tareas T-67 a T-75.
- **Riesgo de integración.** Cada Bounded Context se desarrolló en su propia rama y copió su propio núcleo compartido. Gestión de Crisis y Red de Apoyo y Seguimiento definen ambos recomendaciones, con una clase `RecommendationsController` y la ruta `/api/v1/recommendations` repetidas, lo que obliga a decidir qué contexto es dueño de las recomendaciones antes de integrarlos.
- **Mejora continua.** A partir de la retroalimentación del docente sobre TB1, el equipo estimó todas las tareas de los Sprint Backlog entre 4 y 8 horas, corrigió la evidencia de colaboración del Sprint 1, documentó las acciones HTTP y los ejemplos de la API simulada, registró los commits del Landing Page del Sprint 2 y la desviación respecto de GitFlow (commits directos en `master`), y alineó el segmento objetivo (personas autistas y sus padres) en las User Stories, el Sprint Backlog 2 y las Conclusiones.
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
6. Integrar las cinco ramas del backend en `develop`, desplegar los RESTful Web Services (TS-01 a TS-05), reemplazar la API simulada de la Frontend Web Application y conectar el botón «Crear cuenta y activarlo» del Landing Page con la vista de registro.
7. Validar con usuarios el flujo de registro, inicio de sesión y suscripción (US-46 a US-48), y ajustar el plan Premium según la disposición de pago de los cuidadores.
8. Implementar las historias de seguimiento y recomendaciones de Red de Apoyo y Seguimiento (US-30 a US-45), que no forman parte del compromiso del Sprint 2.
9. Reemplazar los testimonios de ejemplo del Landing Page por testimonios reales obtenidos en las entrevistas de validación.
10. Definir qué Bounded Context es dueño de las recomendaciones (Gestión de Crisis o Red de Apoyo y Seguimiento) y unificar su modelo y sus rutas antes de integrar los Web Services.
11. Integrar cada rama `feature/*` en `develop` al completar cada User Story y distribuir los commits a lo largo del Sprint, para evitar la concentración de commits en el último día que se repitió en los Sprint 2 y 3.
12. Reemplazar la identificación provisional por cabecera (`X-Account-Id`) de los Web Services por el inicio de sesión de la cuenta (US-46 y US-47) antes de publicar la versión de producción.

## Contraste con las hipótesis de Lean UX

La tabla contrasta cada Hypothesis Statement (sección 1.2.2.3) con los resultados de las validaciones. Se completa al terminar las entrevistas de la sección 5.3.

| Hipótesis | Criterio de éxito | Evidencia de la validación | Resultado | Conclusión |
|---|---|---|---|---|
| H1 (FA1): Modo SOS de un solo toque con guías de máximo tres pasos | 5 % de las cuentas gratuitas pasa a un plan Premium; 80 % de las activaciones termina con la guía completada | **[POR COMPLETAR]** Flujo UF-4 de la sección 5.3 | **[POR COMPLETAR]** | **[POR COMPLETAR]** |
| H2 (FA2): Interfaz de autorregulación personalizable | 40 % de los usuarios activos sigue usando la aplicación cada semana al tercer mes | **[POR COMPLETAR]** Flujo UF-1 | **[POR COMPLETAR]** | **[POR COMPLETAR]** |
| H3 (FA3): Tablero CAA con pictogramas y salida de voz | 30 % de los nuevos usuarios llega por recomendación | **[POR COMPLETAR]** Flujos UF-2 y UF-5 | **[POR COMPLETAR]** | **[POR COMPLETAR]** |
| H4 (FA4): Perfil sensorial con detonantes, preferencias y contactos de confianza | 40 % de los usuarios activos sigue usando la aplicación cada semana al tercer mes | **[POR COMPLETAR]** Flujo UF-3 | **[POR COMPLETAR]** | **[POR COMPLETAR]** |
| H5 (FA5): Solicitud de ayuda y registro de episodios | Cinco colegios o centros de terapia contratan el plan institucional en doce meses; 80 % de los usuarios logra enviar una solicitud de ayuda y 70 % de los padres considera útil el reporte | **[POR COMPLETAR]** Flujo UF-6 | **[POR COMPLETAR]** | **[POR COMPLETAR]** |

Los criterios de éxito de H1 a H5 se miden con datos de uso a largo plazo que las entrevistas no alcanzan a cubrir; por eso la columna de evidencia indica el flujo de la sección 5.3 que aporta una señal temprana. Los criterios coinciden con los Hypothesis Statements (1.2.2.3) y con el Lean UX Canvas (1.2.2.4).

## About the Team

El equipo de Macally está formado por cinco estudiantes que desarrollan Nubi, una plataforma web de apoyo para personas autistas y sus padres durante episodios de desregulación emocional o sensorial. Durante el proyecto trabajaron con GitFlow, Conventional Commits, Trello para el Product Backlog y los Sprint Backlog, Figma para el diseño y reuniones por Google Meet y WhatsApp. Desde el Sprint 2 cada integrante lidera un Bounded Context y lo desarrolla de extremo a extremo: primero en la Frontend Web Application y, en el Sprint 3, en los Web Services.

| Integrante | GitHub | Aporte durante el proyecto |
|---|---|---|
| Lopez Torres, Leonardo Gabriel (Team Leader) | LeonardoLopez138 | Startup Profile, Big Picture Event Storming, User Stories, diseño UX/UI de la Web Application, internacionalización del Landing Page, Comunicación Asistida (CAA), despliegue en Firebase y Render, y proyecto base del backend. |
| Diaz Yurivilca, Sofia | u20241a195-cmd | Lean UX Canvas, segmentos objetivo, análisis competitivo, Empathy Mapping, Product Backlog, Gestión de Crisis (Modo SOS) y su integración en `develop`. |
| Payano Puchuri, Joan Fabricio | joanfpp2-ai | Arquitectura de software dirigida por dominio, Autorregulación, base de la Frontend Web Application, sección de video About-the-Team del Landing Page y alineación del Capítulo IV. |
| Ruiz Villegas, Yngrid Nahir | nahiryn8 | Diseño y registro de entrevistas, User Stories, Style Guidelines, Perfil y Personalización y sección de video About-the-Product del Landing Page. |
| Diaz Caruzo, Edgard Daniel | Dan-trax | User Task Matrix, User Journey Mapping, Impact Mapping, Red de Apoyo y Seguimiento, documentación del contexto y licencia MIT. |

**Video About-the-Team.** El Landing Page incrusta una primera versión del video en su sección de equipo.

| Dato | Detalle |
|---|---|
| Título | `upc-pre-202620-1asi0729-7793-macally-about-the-team-sprint-3` |
| Formato | mp4 |
| Duración | **[POR COMPLETAR]** |
| URL en Microsoft Stream | **[POR COMPLETAR]** |
| Contenido | Escenas de sesiones de trabajo del equipo, narración del proceso, retrospectiva del grupo y el testimonio de cada integrante sobre sus actividades y los outcomes alcanzados. La duración sugerida es de 10 minutos: 5 de retrospectiva del grupo y 1 por cada uno de los cinco testimonios (Anexo C del enunciado). |

**[POR COMPLETAR]** Captura de pantalla del video (`images/Conclusiones/about-the-team.png`).

**Retrospectiva del equipo.** Esta parte la redacta el equipo a partir de su reunión de retrospectiva del Sprint 3.

- Qué funcionó: **[POR COMPLETAR]**
- Qué mejorar: **[POR COMPLETAR]**
- Aprendizajes de cada integrante: **[POR COMPLETAR]**
