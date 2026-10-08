# Conclusiones

## Conclusiones y recomendaciones

Esta sección presenta el avance de las conclusiones a la fecha de la entrega TB1. Las hipótesis del Lean UX Process todavía no se contrastan con usuarios, por lo que las conclusiones se apoyan en el análisis de las entrevistas de needfinding, en el diseño del producto, en el Landing Page y en la primera versión de la Frontend Web Application. Las entrevistas de validación con usuarios se realizarán sobre estas dos versiones y sus resultados se incorporarán en la versión final.

**Conclusiones**

- **Problema.** Las seis entrevistas de needfinding (tres por segmento) respaldan el Problem Statement: los tres adolescentes identifican los ruidos fuertes y las aglomeraciones como detonantes (100 %), se aíslan para calmarse (100 %) y evitan hablar durante la crisis (100 %); los cuidadores que atienden crisis sensoriales (67 %) consideran poco prácticas o infantiles las herramientas digitales actuales. Esto sostiene los assumptions UA2 y UA4 y la brecha de apoyo inmediato durante el episodio.
- **Confianza profesional.** El 100 % de los cuidadores entrevistados condiciona su adopción al respaldo explícito de profesionales de la salud, lo que confirma el assumption UA5 y la necesidad de mantener explícita la restricción de que Nubi no reemplaza la atención profesional.
- **Hallazgo que matiza una hipótesis.** Una de las tres cuidadoras entrevistadas (33 %) priorizó una comunidad de testimonios entre madres antes que un botón de crisis inmediata. Este caso debe contrastarse en la validación, pues afecta el supuesto FA1 (Modo SOS de un solo toque) para cuidadores de personas con TDAH.
- **Alcance del producto.** El dominio se organizó en cinco Bounded Contexts (Perfil y Personalización, Gestión de Crisis, Autorregulación, Comunicación Asistida y Red de Apoyo y Seguimiento), con 48 User Stories, 5 Technical Stories y 5 Landing Page Stories priorizadas en el Product Backlog.
- **Implementación.** El Sprint 1 entregó y desplegó la primera versión del Landing Page, responsive, bilingüe (English y Latin American Spanish) y con términos de uso enlazados desde el footer. El Sprint 2 implementó la primera versión de la Frontend Web Application con Angular, que integra en la rama `develop` los cinco Bounded Contexts (US-01 a US-29, 77 Story Points) y usa una API simulada con json-server hasta que se implementen los RESTful Web Services.
- **Modo SOS frente al Problem Statement.** El Modo SOS se activa con un solo toque (FA1) y guía al cuidador paso a paso, priorizando los pasos según las sensibilidades del perfil. Cada sesión registra su estado (finalizada o finalizada anticipadamente) y su duración. Con estos datos ya es posible medir dos criterios de éxito del Problem Statement: el porcentaje de activaciones que termina con la guía completada (meta de 80 %) y la reducción de la duración de los episodios (meta de 25 % tras cuatro semanas de uso).
- **Diferencia entre la hipótesis y la implementación.** La hipótesis H1 plantea guías de máximo tres pasos, pero la guía implementada tiene seis. Queda por validar con usuarios si la cantidad de pasos afecta el porcentaje de cuidadores que completan la guía.
- **Limitación frente a los assumptions.** El assumption UOA6 (uso sin conexión a internet) no está cubierto: la Frontend Web Application depende de la API y no funciona sin conexión.

**Recomendaciones**

1. Realizar las entrevistas de validación con usuarios de los dos segmentos sobre el Landing Page y la Frontend Web Application, y medir las métricas definidas en el Lean UX Canvas (por ejemplo, 80 % de cuidadores que completan la guía del Modo SOS).
2. Incluir en las validaciones a niños de 6 a 12 años: los adolescentes entrevistados tienen entre 15 y 17 años.
3. Contrastar en la validación una guía de tres pasos con la de seis pasos del Modo SOS, y conservar la que obtenga mayor porcentaje de guías completadas.
4. Registrar la intensidad inicial del episodio al activar el Modo SOS. Hoy toda sesión empieza con intensidad alta por defecto, y la comparación con la intensidad final depende de ese dato.
5. Habilitar el uso sin conexión de la guía del Modo SOS (UOA6), de modo que el cuidador pueda usarla con datos móviles limitados.
6. Reemplazar la API simulada por los RESTful Web Services (TS-01 a TS-05) y conectar el botón «Crear cuenta y activarlo» del Landing Page con la vista de registro de la Web Application.
7. Validar con usuarios el flujo de registro, inicio de sesión y suscripción (US-46 a US-48), y ajustar el plan Premium según la disposición de pago de los cuidadores.
8. Implementar las historias de seguimiento y recomendaciones de Red de Apoyo y Seguimiento (US-30 a US-45), que no forman parte del compromiso del Sprint 2.
9. Reemplazar los testimonios de ejemplo del Landing Page por testimonios reales obtenidos en las entrevistas de validación.
