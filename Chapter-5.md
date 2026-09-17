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

Para la gestión del código fuente de NUBI se utiliza **Git** como sistema de control de versiones distribuido y **GitHub** como plataforma para alojar los repositorios del proyecto y facilitar el trabajo colaborativo entre los integrantes del equipo. Mediante estas herramientas se mantiene la trazabilidad de los cambios realizados durante el desarrollo del Landing Page, la Frontend Web Application y los RESTful Web Services.

Los repositorios correspondientes a los productos de software de NUBI son los siguientes:

| Producto | Repositorio |
|---|---|
| Landing Page | [COLOCAR URL DEL REPOSITORIO] |
| Frontend Web Application | [COLOCAR URL DEL REPOSITORIO] |
| RESTful Web Services | [COLOCAR URL DEL REPOSITORIO] |

En el caso de los RESTful Web Services, el repositorio contendrá tanto el código fuente de los servicios como los archivos correspondientes a las pruebas unitarias y de integración.

#### GitFlow Workflow

El equipo adopta **GitFlow** como flujo de trabajo para organizar las diferentes etapas de desarrollo del proyecto. Esta estrategia permite separar las versiones estables de las funcionalidades que se encuentran en desarrollo y facilita la integración progresiva de los cambios realizados por los integrantes del equipo.

La estructura de ramas utilizada es la siguiente:

| Rama | Propósito |
|---|---|
| `main` | Contiene las versiones estables del producto preparadas para producción. |
| `develop` | Rama principal de integración de las funcionalidades desarrolladas por el equipo. |
| `feature/*` | Ramas utilizadas para desarrollar nuevas funcionalidades o cambios específicos. |
| `release/*` | Ramas utilizadas para preparar una nueva versión antes de integrarla a `main`. |
| `hotfix/*` | Ramas utilizadas para corregir errores críticos encontrados en una versión publicada. |

Las ramas de tipo `feature` se crean a partir de `develop`. Sus nombres deben ser descriptivos, estar escritos en inglés y utilizar la convención `kebab-case`.

Algunos ejemplos de ramas aplicadas a NUBI son: `feature/user-profile`, `feature/sos-mode`, `feature/self-regulation`, `feature/caa-board`, `feature/support-network` y `feature/landing-page`.

Para la elaboración y actualización de la documentación del proyecto también se utilizan ramas específicas como `feature/chapter-3`, `feature/chapter-4` y `feature/chapter-5`.

Una vez finalizado el trabajo realizado en una rama `feature/*`, los cambios son revisados antes de integrarse nuevamente a la rama `develop`.

Para preparar una nueva versión estable del producto se utilizan ramas `release/*`. La convención utilizada es `release/v<MAJOR>.<MINOR>.<PATCH>`. Por ejemplo: `release/v1.0.0` o `release/v1.1.0`.

Cuando se identifica un error crítico en una versión ya publicada se utiliza una rama `hotfix/*`. Por ejemplo: `hotfix/v1.0.1`.

Una vez realizada la corrección, los cambios de la rama `hotfix/*` son integrados tanto en `main` como en `develop`, con el objetivo de mantener consistencia entre las versiones del proyecto.

#### Semantic Versioning

Para identificar las diferentes versiones de los productos de NUBI se utiliza **Semantic Versioning**, siguiendo la estructura `MAJOR.MINOR.PATCH`.

Cada componente representa lo siguiente:

- **MAJOR:** se incrementa cuando se introducen cambios que no son compatibles con versiones anteriores.
- **MINOR:** se incrementa cuando se incorporan nuevas funcionalidades compatibles con la versión existente.
- **PATCH:** se incrementa cuando se realizan correcciones de errores compatibles con la versión actual.

Algunos ejemplos de versiones son `v1.0.0`, `v1.1.0` y `v1.1.1`.

De esta manera, la numeración de versiones permite identificar con mayor facilidad el alcance de los cambios realizados en cada publicación del producto.

#### Conventional Commits

Para mantener un historial de modificaciones claro, consistente y fácil de comprender, el equipo utiliza la especificación **Conventional Commits** para la redacción de los mensajes de commit.

La estructura utilizada es `<type>(<scope>): <description>`.

Los principales tipos de commit utilizados en el proyecto son:

| Tipo | Propósito |
|---|---|
| `feat` | Incorporación de una nueva funcionalidad. |
| `fix` | Corrección de un error. |
| `docs` | Cambios realizados en la documentación. |
| `style` | Cambios relacionados con formato o presentación que no modifican la lógica del sistema. |
| `refactor` | Reorganización del código sin modificar su comportamiento. |
| `test` | Incorporación o modificación de pruebas. |
| `chore` | Tareas relacionadas con configuración o mantenimiento del proyecto. |

Algunos ejemplos de mensajes de commit aplicados a NUBI son:

- `feat(profile): add user profile creation`
- `feat(sos): add SOS mode activation`
- `feat(regulation): add self-regulation stimuli`
- `feat(caa): add pictogram board`
- `feat(support): add support request`
- `style(landing): improve responsive layout`
- `fix(caa): correct pictogram selection`
- `docs(chapter5): add source code management`

El uso conjunto de Git, GitHub, GitFlow, Semantic Versioning y Conventional Commits permite mantener una organización consistente del código fuente, facilitar la colaboración entre los integrantes del equipo y conservar la trazabilidad de la evolución de los diferentes productos de software que conforman NUBI.

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

