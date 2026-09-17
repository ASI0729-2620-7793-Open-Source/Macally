# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

En esta sección se establecen las decisiones, herramientas y convenciones utilizadas por el equipo de NUBI para gestionar de manera consistente los diferentes productos de software que conforman la solución durante su ciclo de vida.

La gestión de configuración comprende la definición del entorno de desarrollo, la administración y control de versiones del código fuente, las convenciones de programación adoptadas por el equipo y la configuración necesaria para el despliegue de los productos digitales.

Para el desarrollo colaborativo de NUBI se emplean herramientas de gestión de proyectos, diseño UX/UI, desarrollo de software, documentación y control de versiones. Asimismo, se utiliza Git y GitHub para mantener la trazabilidad de los cambios realizados por los integrantes del equipo y facilitar la integración progresiva del Landing Page, la Frontend Web Application y los RESTful Web Services.

### 5.1.1. Software Development Environment Configuration

Para el desarrollo de NUBI se utiliza un conjunto de herramientas que permiten cubrir las diferentes actividades del ciclo de vida del producto de software, incluyendo la gestión del proyecto, gestión de requisitos, diseño UX/UI, desarrollo del Landing Page, Frontend Web Application, RESTful Web Services, documentación y control de versiones.

Las herramientas seleccionadas permiten que los integrantes del equipo trabajen de manera colaborativa y mantengan consistencia entre los diferentes productos que conforman la solución.

| Área | Producto / Herramienta | Propósito de uso en NUBI | Referencia |
|---|---|---|---|
| Project Management | Trello | Gestionar y priorizar el Product Backlog, organizar las User Stories y dar seguimiento a las actividades del equipo. | https://trello.com/ |
| Requirements Management | GitHub | Mantener de forma colaborativa la documentación del proyecto, User Stories, Product Backlog y demás artefactos desarrollados en formato Markdown. | https://github.com/ |
| UX Research | UXPressia | Elaborar y documentar artefactos UX como User Personas, User Journey Maps, Empathy Maps e Impact Mapping. | https://uxpressia.com/ |
| UX/UI Design | Figma | Diseñar Wireframes, Mock-ups y Prototypes correspondientes al Landing Page y la Web Application de NUBI. | https://www.figma.com/ |
| Software Development | Visual Studio Code | Editar y desarrollar el código fuente correspondiente a los diferentes productos de software de NUBI. | https://code.visualstudio.com/ |
| Landing Page Development | HTML5 | Definir la estructura semántica del Landing Page. | https://developer.mozilla.org/en-US/docs/Web/HTML |
| Landing Page Development | CSS3 | Implementar los estilos visuales y el Responsive Web Design del Landing Page. | https://developer.mozilla.org/en-US/docs/Web/CSS |
| Landing Page Development | JavaScript | Implementar las interacciones y comportamiento dinámico del Landing Page. | https://developer.mozilla.org/en-US/docs/Web/JavaScript |
| Frontend Web Application | Angular | Framework utilizado para desarrollar la Frontend Web Application de NUBI. | https://angular.dev/ |
| Frontend Web Application | TypeScript | Lenguaje de programación utilizado para desarrollar la lógica de la aplicación Angular. | https://www.typescriptlang.org/ |
| Frontend Web Application | Angular Material | Biblioteca de componentes UI basada en Material Design utilizada para mantener consistencia visual en la Web Application. | https://material.angular.dev/ |
| RESTful Web Services | Java | Lenguaje de programación utilizado para desarrollar la lógica del lado servidor. | https://www.java.com/ |
| RESTful Web Services | Spring Boot | Framework utilizado para desarrollar los RESTful Web Services de NUBI. | https://spring.io/projects/spring-boot |
| Data Persistence | Spring Data JPA | Facilitar el acceso y persistencia de información desde los RESTful Web Services. | https://spring.io/projects/spring-data-jpa |
| API Documentation | OpenAPI / Swagger | Documentar y visualizar los endpoints expuestos por el RESTful API. | https://swagger.io/ |
| Source Code Management | Git | Gestionar el historial de cambios realizado sobre el código fuente de los diferentes productos. | https://git-scm.com/ |
| Source Code Management | GitHub | Alojar los repositorios del Landing Page, Frontend Web Application y RESTful Web Services, facilitando la colaboración del equipo. | https://github.com/ |

La selección de estas herramientas responde a los lineamientos tecnológicos establecidos para el proyecto y permite mantener un entorno de trabajo común entre los integrantes del equipo. Git y GitHub permiten gestionar los cambios realizados durante el desarrollo, mientras que Trello facilita la organización del Product Backlog. UXPressia y Figma son utilizados para la elaboración de los artefactos UX/UI, y Visual Studio Code constituye el entorno principal para la edición del código fuente.

En cuanto a la implementación, el Landing Page se desarrolla utilizando HTML5, CSS3 y JavaScript; la Frontend Web Application utiliza Angular, TypeScript y Angular Material; mientras que los RESTful Web Services se implementan con Java, Spring Boot y Spring Data JPA. Finalmente, la documentación de los servicios se realiza mediante OpenAPI y Swagger.

### 5.1.2. Source Code Management

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

