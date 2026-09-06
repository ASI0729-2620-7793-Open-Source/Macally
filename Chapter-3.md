# Capítulo III: Requirements Specification

## 3.1. User Stories

En esta sección se especifican las épicas y las User Stories que definen el alcance funcional de Nubi. Primero se presentan las épicas con el conjunto de User Stories que agrupan, y luego el detalle de cada User Story con su descripción y criterios de aceptación.

## Épicas

### EPIC - 01 Inicio de sesión y registro

**Descripción:** Como usuario quiero registrarme, verificar mi cuenta, iniciar sesión y recuperar mi contraseña para acceder de forma segura a la plataforma.

| ID | User Story |
|---|---|
| US-01 | Registrar cuenta con email |
| US-02 | Verificar email |
| US-03 | Iniciar sesión con credenciales |
| US-04 | Iniciar sesión con Google OAuth |
| US-05 | Recuperar contraseña |
| US-06 | Cerrar sesión |

### EPIC - 02 Perfil y configuración de cuenta

**Descripción:** Como usuario quiero gestionar mi perfil y preferencias personales para personalizar mi experiencia dentro de la plataforma.

| ID | User Story |
|---|---|
| US-07 | Visualizar perfil de cuenta |
| US-08 | Actualizar datos personales |
| US-09 | Cambiar contraseña |
| US-10 | Configurar idioma y tema |
| US-11 | Configurar notificaciones |
| US-12 | Eliminar cuenta |

### EPIC - 03 Gestión de perfil del usuario neurodivergente

**Descripción:** Como cuidador quiero crear y gestionar el perfil del niño o adolescente neurodivergente para personalizar las herramientas de apoyo según sus necesidades.

| ID | User Story |
|---|---|
| US-13 | Crear perfil del usuario neurodivergente |
| US-14 | Editar perfil del usuario neurodivergente |
| US-15 | Registrar sensibilidades sensoriales |
| US-16 | Registrar diagnóstico y condición |
| US-17 | Subir foto de perfil del usuario |
| US-18 | Asociar múltiples cuidadores a un perfil |

### EPIC - 04 Modo SOS

**Descripción:** Como cuidador quiero contar con un Modo SOS con guías paso a paso para actuar con seguridad durante un episodio de desregulación.

| ID | User Story |
|---|---|
| US-19 | Activar Modo SOS |
| US-20 | Visualizar guía paso a paso del Modo SOS |
| US-21 | Personalizar guía SOS según perfil del usuario |
| US-22 | Marcar paso de la guía como completado |
| US-23 | Finalizar episodio desde el Modo SOS |
| US-24 | Acceder al Modo SOS desde pantalla principal |

### EPIC - 05 Interfaz de autorregulación

**Descripción:** Como usuario neurodivergente quiero contar con una interfaz de autorregulación con estímulos personalizables para recuperar la calma durante una sobrecarga sensorial.

| ID | User Story |
|---|---|
| US-25 | Seleccionar estímulo visual de autorregulación |
| US-26 | Seleccionar estímulo auditivo de autorregulación |
| US-27 | Ajustar intensidad del estímulo |
| US-28 | Guardar estímulos favoritos |
| US-29 | Activar modo de baja estimulación |
| US-30 | Usar temporizador de calma |

### EPIC - 06 Tablero de Comunicación Aumentativa y Alternativa (CAA)

**Descripción:** Como usuario neurodivergente quiero contar con un tablero de comunicación con pictogramas para expresar mis necesidades básicas sin depender del habla.

| ID | User Story |
|---|---|
| US-31 | Visualizar tablero de pictogramas |
| US-32 | Seleccionar pictograma para comunicar una necesidad |
| US-33 | Personalizar pictogramas favoritos |
| US-34 | Agregar pictograma personalizado |
| US-35 | Organizar pictogramas por categoría |
| US-36 | Reproducir audio asociado al pictograma |

### EPIC - 07 Sistema de solicitud de ayuda

**Descripción:** Como usuario neurodivergente quiero poder solicitar ayuda a mi cuidador de forma rápida para recibir apoyo durante una situación de crisis.

| ID | User Story |
|---|---|
| US-37 | Enviar solicitud de ayuda al cuidador |
| US-38 | Recibir notificación de solicitud de ayuda |
| US-39 | Confirmar recepción de la solicitud |
| US-40 | Cancelar solicitud de ayuda |
| US-41 | Consultar historial de solicitudes de ayuda |

### EPIC - 08 Panel de inicio del cuidador (Home)

**Descripción:** Como cuidador quiero contar con un panel de inicio centralizado que me muestre el estado del usuario a mi cargo para tomar decisiones rápidas.

| ID | User Story |
|---|---|
| US-42 | Visualizar resumen de episodios recientes |
| US-43 | Visualizar estado actual del usuario |
| US-44 | Acceder a módulos mediante accesos directos |
| US-45 | Visualizar alertas recientes en el home |
| US-46 | Visualizar recomendaciones personalizadas en el home |
| US-47 | Cambiar entre perfiles de usuarios a cargo |

### EPIC - 09 Registro e historial de episodios de crisis

**Descripción:** Como cuidador quiero registrar y consultar el historial de episodios de crisis para identificar patrones y mejorar el acompañamiento.

| ID | User Story |
|---|---|
| US-48 | Registrar episodio automáticamente al usar el Modo SOS |
| US-49 | Visualizar historial de episodios |
| US-50 | Filtrar historial de episodios por fecha |
| US-51 | Ver detalle de un episodio registrado |
| US-52 | Agregar notas manuales a un episodio |

### EPIC - 10 Guías y recomendaciones personalizadas

**Descripción:** Como cuidador quiero recibir recomendaciones personalizadas de actuación según el perfil del usuario para brindar un acompañamiento más adecuado.

| ID | User Story |
|---|---|
| US-53 | Generar recomendaciones según el perfil del usuario |
| US-54 | Visualizar guía de actuación recomendada |
| US-55 | Calificar la utilidad de una recomendación |
| US-56 | Guardar recomendación como favorita |
| US-57 | Actualizar recomendaciones tras nuevos episodios |

### EPIC - 11 Proceso de suscripción (Planes familiares)

**Descripción:** Como usuario con cuenta creada y Plan Free asignado por defecto, quiero iniciar la suscripción a un plan premium para habilitar funcionalidades adicionales.

| ID | User Story |
|---|---|
| US-58 | Visualizar planes de suscripción disponibles |
| US-59 | Seleccionar plan de suscripción |
| US-60 | Registrar datos de facturación |
| US-61 | Procesar cobro de suscripción |
| US-62 | Activar suscripción |
| US-63 | Cancelar proceso de suscripción antes de confirmar |

### EPIC - 12 Gestión de suscripción

**Descripción:** Como usuario quiero visualizar y gestionar mi plan actual desde la sección Suscripción para consultar su estado, renovarlo o cancelarlo.

| ID | User Story |
|---|---|
| US-64 | Visualizar panel de suscripción |
| US-65 | Consultar estado de suscripción |
| US-66 | Renovar suscripción |
| US-67 | Actualizar método de pago |
| US-68 | Descargar historial de pagos |
| US-69 | Solicitar cancelación de suscripción |

### EPIC - 13 Planes institucionales B2B

**Descripción:** Como institución educativa o centro de terapia, quiero contratar un plan B2B y gestionar los perfiles de mis estudiantes para acompañar a varios usuarios neurodivergentes a la vez.

| ID | User Story |
|---|---|
| US-70 | Registrar institución |
| US-71 | Gestionar perfiles de estudiantes desde la institución |
| US-72 | Asignar perfiles a educadores |
| US-73 | Visualizar dashboard institucional |
| US-74 | Generar reporte agregado de la institución |

### EPIC - 14 Centro de soporte y ayuda

**Descripción:** Como usuario quiero contar con un centro de soporte accesible para resolver mis dudas y reportar problemas sin necesidad de contactar a un agente externo.

| ID | User Story |
|---|---|
| US-75 | Visualizar el centro de soporte |
| US-76 | Buscar artículo de ayuda |
| US-77 | Consultar artículo de ayuda |
| US-78 | Reportar un problema |
| US-79 | Confirmar envío del reporte |

### EPIC - 15 Landing page

**Descripción:** Como visitante quiero acceder a la landing page para conocer la propuesta de valor de Nubi, sus funcionalidades y planes disponibles.

| ID | User Story |
|---|---|
| US-80 | Visualizar la propuesta de valor |
| US-81 | Explorar las funcionalidades principales |
| US-82 | Revisar los planes de suscripción |
| US-83 | Consultar las preguntas frecuentes |
| US-84 | Iniciar sesión desde la landing page |
| US-85 | Acceder mediante el botón de acción principal |

### EPIC - 16 Experiencia global de la aplicación

**Descripción:** Como usuario autenticado quiero contar con navegación global, cambio de idioma y accesibilidad para usar la aplicación de forma consistente.

| ID | User Story |
|---|---|
| US-86 | Navegar entre módulos desde el menú principal |
| US-87 | Cambiar idioma de la interfaz |
| US-88 | Gestionar rutas no encontradas |
| US-89 | Activar lectura en voz alta de contenidos |
| US-90 | Usar la aplicación en modo offline básico |

### EPIC - 17 Notificaciones push

**Descripción:** Como cuidador quiero recibir notificaciones relevantes sobre episodios y la suscripción para estar siempre informado.

| ID | User Story |
|---|---|
| US-91 | Configurar preferencias de notificaciones |
| US-92 | Recibir alerta de episodio en curso |
| US-93 | Recibir recordatorio de check-in |
| US-94 | Recibir alerta de vencimiento de suscripción |
| US-95 | Silenciar notificaciones temporalmente |

### EPIC - 18 Technical Stories – API y arquitectura

**Descripción:** Como equipo de desarrollo, queremos implementar una arquitectura de servicios RESTful segura y escalable para que todos los componentes de la plataforma intercambien datos de manera consistente.

| ID | User Story |
|---|---|
| US-96 | Autenticar y autorizar usuarios mediante JWT |
| US-97 | Exponer API RESTful de episodios y perfiles |
| US-98 | Persistir datos mediante JPA por bounded context |
| US-99 | Containerizar y desplegar la API mediante Docker y CI/CD |
| US-100 | Desplegar el frontend en hosting estático |

## User Stories

A continuación se detalla cada User Story con su épica relacionada, descripción y criterios de aceptación.

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>01</td>
      <td><strong>Epic ID</strong></td>
      <td>01</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Registrar cuenta con email</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero registrarme con mi email para crear una cuenta en Nubi.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Registro exitoso</strong><br>
      Dado que el usuario completa el formulario de registro con nombre, email y contraseña válidos y presiona "Registrarme", cuando el sistema valida la información, entonces crea la cuenta, la deja en estado "Pendiente de verificación" y envía un correo de verificación al email registrado.<br><br>
      <strong>Scenario 2: Email ya registrado</strong><br>
      Dado que el usuario ingresa un email que ya existe en el sistema y presiona "Registrarme", cuando el sistema valida el correo, entonces muestra el mensaje "Este correo ya está registrado" e impide continuar el registro.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>02</td>
      <td><strong>Epic ID</strong></td>
      <td>01</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Verificar email</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario recién registrado quiero verificar mi correo para activar completamente mi cuenta.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Verificación exitosa</strong><br>
      Dado que el usuario presiona el enlace de verificación recibido en su correo, cuando el token es válido y no ha expirado, entonces el sistema activa la cuenta y redirige al usuario a la pantalla de inicio de sesión con un mensaje de confirmación.<br><br>
      <strong>Scenario 2: Enlace expirado</strong><br>
      Dado que el usuario presiona un enlace de verificación con más de 24 horas de antigüedad, cuando el sistema valida el token, entonces muestra el mensaje "El enlace ha expirado" y ofrece la opción de reenviar el correo de verificación.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>03</td>
      <td><strong>Epic ID</strong></td>
      <td>01</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Iniciar sesión con credenciales</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero iniciar sesión con mi email y contraseña para acceder a la plataforma.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Inicio de sesión correcto</strong><br>
      Dado que el usuario ingresa un email y contraseña válidos y presiona "Iniciar sesión", cuando el sistema valida las credenciales, entonces redirige al usuario al panel de inicio correspondiente a su rol.<br><br>
      <strong>Scenario 2: Credenciales incorrectas</strong><br>
      Dado que el usuario ingresa un email o contraseña incorrectos, cuando el sistema intenta validar las credenciales, entonces muestra el mensaje "Correo o contraseña incorrectos" y no permite el acceso.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>04</td>
      <td><strong>Epic ID</strong></td>
      <td>01</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Iniciar sesión con Google OAuth</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero iniciar sesión con mi cuenta de Google para acceder de forma rápida sin crear una contraseña.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Inicio de sesión con Google exitoso</strong><br>
      Dado que el usuario presiona "Continuar con Google" y selecciona una cuenta válida, cuando Google autentica al usuario, entonces el sistema crea o vincula la cuenta y lo redirige al panel de inicio.<br><br>
      <strong>Scenario 2: Cancelación del flujo de Google</strong><br>
      Dado que el usuario presiona "Continuar con Google" pero cierra la ventana de autenticación antes de completar el proceso, cuando el flujo de OAuth se interrumpe, entonces el sistema regresa a la pantalla de inicio de sesión sin crear ninguna cuenta.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>05</td>
      <td><strong>Epic ID</strong></td>
      <td>01</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Recuperar contraseña</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero recuperar mi contraseña olvidada para poder volver a acceder a mi cuenta.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Solicitud de recuperación exitosa</strong><br>
      Dado que el usuario ingresa su email en la pantalla "Olvidé mi contraseña" y presiona "Enviar", cuando el email está registrado en el sistema, entonces se envía un correo con un enlace para restablecer la contraseña.<br><br>
      <strong>Scenario 2: Email no registrado</strong><br>
      Dado que el usuario ingresa un email que no existe en el sistema, cuando el sistema valida el correo, entonces muestra un mensaje genérico indicando que si el correo existe recibirá instrucciones, sin revelar si la cuenta existe.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>06</td>
      <td><strong>Epic ID</strong></td>
      <td>01</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Cerrar sesión</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero cerrar sesión para proteger el acceso a mi cuenta en dispositivos compartidos.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Cierre de sesión exitoso</strong><br>
      Dado que el usuario presiona "Cerrar sesión" desde el menú de perfil, cuando el sistema procesa la solicitud, entonces invalida la sesión activa y redirige al usuario a la pantalla de inicio de sesión.<br><br>
      <strong>Scenario 2: Sesión expirada automáticamente</strong><br>
      Dado que el usuario permanece inactivo por más de 30 minutos, cuando el sistema detecta la inactividad, entonces cierra la sesión automáticamente y solicita reautenticación en el siguiente intento de acción.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>07</td>
      <td><strong>Epic ID</strong></td>
      <td>02</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Visualizar perfil de cuenta</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero visualizar los datos de mi cuenta para verificar que la información esté correcta.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Visualización correcta</strong><br>
      Dado que el usuario accede a la sección "Mi cuenta", cuando la pantalla carga, entonces se muestran su nombre, email, foto de perfil y fecha de registro.<br><br>
      <strong>Scenario 2: Error al cargar datos</strong><br>
      Dado que el usuario accede a "Mi cuenta" y ocurre un error de comunicación con el servidor, cuando el sistema intenta obtener los datos, entonces muestra el mensaje "No se pudo cargar tu perfil, inténtalo más tarde".
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>08</td>
      <td><strong>Epic ID</strong></td>
      <td>02</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Actualizar datos personales</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero actualizar mi nombre y datos de contacto para mantener mi cuenta al día.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Actualización exitosa</strong><br>
      Dado que el usuario modifica su nombre en el formulario de perfil y presiona "Guardar", cuando los datos ingresados son válidos, entonces el sistema actualiza la información y muestra un mensaje de confirmación.<br><br>
      <strong>Scenario 2: Campos inválidos</strong><br>
      Dado que el usuario deja el campo nombre vacío y presiona "Guardar", cuando el sistema valida el formulario, entonces resalta el campo con el mensaje "Este campo es obligatorio" y no guarda los cambios.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>09</td>
      <td><strong>Epic ID</strong></td>
      <td>02</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Cambiar contraseña</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero cambiar mi contraseña para mantener segura mi cuenta.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Cambio exitoso</strong><br>
      Dado que el usuario ingresa su contraseña actual y una nueva contraseña válida y presiona "Actualizar", cuando la contraseña actual es correcta, entonces el sistema actualiza la contraseña y muestra un mensaje de confirmación.<br><br>
      <strong>Scenario 2: Contraseña actual incorrecta</strong><br>
      Dado que el usuario ingresa una contraseña actual incorrecta, cuando el sistema valida el dato, entonces muestra el mensaje "La contraseña actual no es correcta" y no realiza el cambio.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>10</td>
      <td><strong>Epic ID</strong></td>
      <td>02</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Configurar idioma y tema</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero configurar el idioma y el tema visual de la aplicación para adaptarla a mis preferencias.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Configuración aplicada</strong><br>
      Dado que el usuario selecciona un idioma y un tema (claro/oscuro) en la sección de preferencias, cuando presiona "Guardar", entonces la interfaz se actualiza inmediatamente con las nuevas preferencias.<br><br>
      <strong>Scenario 2: Preferencia no soportada en el dispositivo</strong><br>
      Dado que el usuario selecciona el tema oscuro en un dispositivo con restricciones del sistema operativo, cuando el sistema detecta la limitación, entonces aplica el tema más cercano disponible y notifica al usuario del ajuste.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>11</td>
      <td><strong>Epic ID</strong></td>
      <td>02</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Configurar notificaciones</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero configurar qué notificaciones recibo para evitar interrupciones innecesarias.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Configuración guardada</strong><br>
      Dado que el usuario desactiva las notificaciones de recomendaciones y mantiene activas las de alertas de crisis, cuando presiona "Guardar", entonces el sistema actualiza las preferencias de notificación.<br><br>
      <strong>Scenario 2: Intento de desactivar alertas críticas</strong><br>
      Dado que el usuario intenta desactivar las notificaciones de alertas de crisis, cuando el sistema valida la acción, entonces impide desactivarlas y muestra el mensaje "Las alertas de crisis no pueden desactivarse".
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>12</td>
      <td><strong>Epic ID</strong></td>
      <td>02</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Eliminar cuenta</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero eliminar mi cuenta si decido dejar de usar la plataforma.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Eliminación confirmada</strong><br>
      Dado que el usuario presiona "Eliminar cuenta", confirma su contraseña y presiona "Confirmar eliminación", cuando la contraseña es correcta, entonces el sistema elimina la cuenta y todos los datos asociados, y cierra la sesión.<br><br>
      <strong>Scenario 2: Cancelación de la eliminación</strong><br>
      Dado que el usuario presiona "Eliminar cuenta" pero luego presiona "Cancelar" en el modal de confirmación, cuando el sistema procesa la acción, entonces cierra el modal sin eliminar la cuenta.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>13</td>
      <td><strong>Epic ID</strong></td>
      <td>03</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Crear perfil del usuario neurodivergente</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero crear el perfil de la persona a mi cargo para comenzar a personalizar la aplicación.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Creación exitosa</strong><br>
      Dado que el cuidador completa el formulario con nombre, edad y condición del usuario y presiona "Crear perfil", cuando los datos son válidos, entonces el sistema registra el perfil y lo muestra en el selector de perfiles.<br><br>
      <strong>Scenario 2: Campos obligatorios vacíos</strong><br>
      Dado que el cuidador deja el campo edad vacío y presiona "Crear perfil", cuando el sistema valida el formulario, entonces resalta el campo con el mensaje "Este campo es obligatorio" y no crea el perfil.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>14</td>
      <td><strong>Epic ID</strong></td>
      <td>03</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Editar perfil del usuario neurodivergente</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero editar el perfil del usuario a mi cargo para mantener su información actualizada.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Edición exitosa</strong><br>
      Dado que el cuidador modifica la edad y presiona "Guardar", cuando los datos son válidos, entonces el sistema actualiza el perfil y muestra un mensaje de confirmación.<br><br>
      <strong>Scenario 2: Edición sin cambios</strong><br>
      Dado que el cuidador presiona "Guardar" sin modificar ningún campo, cuando el sistema procesa la solicitud, entonces no realiza cambios y cierra el formulario normalmente.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>15</td>
      <td><strong>Epic ID</strong></td>
      <td>03</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Registrar sensibilidades sensoriales</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero registrar las sensibilidades sensoriales del usuario para que la app personalice los estímulos ofrecidos.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Registro exitoso</strong><br>
      Dado que el cuidador selecciona sensibilidad alta a ruidos fuertes y baja a estímulos visuales, y presiona "Guardar", cuando el sistema valida la información, entonces almacena las preferencias y las usa para filtrar los estímulos disponibles en autorregulación.<br><br>
      <strong>Scenario 2: Sin selección de sensibilidades</strong><br>
      Dado que el cuidador presiona "Guardar" sin seleccionar ninguna sensibilidad, cuando el sistema valida el formulario, entonces permite guardar el perfil con valores por defecto y sugiere completarlos más adelante.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>16</td>
      <td><strong>Epic ID</strong></td>
      <td>03</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Registrar diagnóstico y condición</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero registrar el diagnóstico del usuario para que las recomendaciones sean más precisas.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Registro exitoso</strong><br>
      Dado que el cuidador selecciona "TEA" de la lista de condiciones y presiona "Guardar", cuando el sistema valida la selección, entonces asocia la condición al perfil y ajusta las recomendaciones por defecto.<br><br>
      <strong>Scenario 2: Condición no listada</strong><br>
      Dado que el cuidador no encuentra la condición específica en la lista, cuando el sistema no tiene esa opción, entonces permite seleccionar "Otra" y describirla en un campo de texto libre.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>17</td>
      <td><strong>Epic ID</strong></td>
      <td>03</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Subir foto de perfil del usuario</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero subir una foto de perfil del usuario para identificarlo fácilmente al cambiar entre perfiles.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Carga exitosa</strong><br>
      Dado que el cuidador selecciona una imagen válida (jpg/png menor a 5MB) y presiona "Subir", cuando el archivo cumple los requisitos, entonces el sistema actualiza la foto de perfil del usuario.<br><br>
      <strong>Scenario 2: Archivo inválido</strong><br>
      Dado que el cuidador intenta subir un archivo de más de 5MB o en un formato no soportado, cuando el sistema valida el archivo, entonces muestra el mensaje "Formato o tamaño de archivo no válido" y no actualiza la foto.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>18</td>
      <td><strong>Epic ID</strong></td>
      <td>03</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Asociar múltiples cuidadores a un perfil</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador principal quiero invitar a otros cuidadores al perfil del usuario para compartir el acompañamiento.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Invitación exitosa</strong><br>
      Dado que el cuidador principal ingresa el email de otro cuidador y presiona "Invitar", cuando el email corresponde a una cuenta válida, entonces el sistema envía la invitación y, al aceptarla, el nuevo cuidador obtiene acceso al perfil.<br><br>
      <strong>Scenario 2: Límite de cuidadores alcanzado</strong><br>
      Dado que el cuidador principal intenta invitar a un quinto cuidador cuando el plan permite máximo cuatro, cuando el sistema valida el límite del plan, entonces muestra el mensaje "Has alcanzado el límite de cuidadores para tu plan" y no envía la invitación.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>19</td>
      <td><strong>Epic ID</strong></td>
      <td>04</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Activar Modo SOS</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero activar el Modo SOS al inicio de una crisis para recibir orientación inmediata.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Activación exitosa</strong><br>
      Dado que el cuidador presiona el botón "Modo SOS" desde cualquier pantalla, cuando el sistema procesa la acción, entonces abre la guía de actuación paso a paso correspondiente al perfil activo.<br><br>
      <strong>Scenario 2: Activación sin perfil seleccionado</strong><br>
      Dado que el cuidador presiona "Modo SOS" sin tener un perfil de usuario seleccionado, cuando el sistema valida el contexto, entonces solicita seleccionar un perfil antes de mostrar la guía.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>20</td>
      <td><strong>Epic ID</strong></td>
      <td>04</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Visualizar guía paso a paso del Modo SOS</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero visualizar los pasos de actuación uno a uno para no sentirme abrumado durante la crisis.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Visualización correcta</strong><br>
      Dado que el cuidador se encuentra dentro del Modo SOS activo, cuando avanza entre los pasos con el botón "Siguiente", entonces el sistema muestra cada paso con texto breve, un ícono ilustrativo y audio opcional.<br><br>
      <strong>Scenario 2: Último paso alcanzado</strong><br>
      Dado que el cuidador llega al último paso de la guía, cuando presiona "Siguiente", entonces el sistema muestra la pantalla de cierre del episodio en lugar de un paso adicional.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>21</td>
      <td><strong>Epic ID</strong></td>
      <td>04</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Personalizar guía SOS según perfil del usuario</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero que la guía SOS se adapte a las sensibilidades registradas del usuario para que sea más efectiva.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Personalización aplicada</strong><br>
      Dado que el perfil del usuario tiene registrada sensibilidad alta a ruidos, cuando el cuidador activa el Modo SOS, entonces el sistema prioriza pasos relacionados con reducir estímulos auditivos.<br><br>
      <strong>Scenario 2: Perfil sin datos de personalización</strong><br>
      Dado que el perfil del usuario no tiene sensibilidades registradas, cuando el cuidador activa el Modo SOS, entonces el sistema muestra la guía genérica por defecto y sugiere completar el perfil.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>22</td>
      <td><strong>Epic ID</strong></td>
      <td>04</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Marcar paso de la guía como completado</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero marcar cada paso como completado para llevar control de las acciones ya realizadas.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Marcado exitoso</strong><br>
      Dado que el cuidador presiona el ícono de check en un paso, cuando el sistema procesa la acción, entonces el paso se muestra como completado y avanza automáticamente al siguiente.<br><br>
      <strong>Scenario 2: Intento de saltar pasos críticos</strong><br>
      Dado que el cuidador intenta marcar como completado un paso marcado como obligatorio sin haberlo revisado, cuando el sistema detecta la omisión, entonces solicita confirmación explícita antes de permitir avanzar.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>23</td>
      <td><strong>Epic ID</strong></td>
      <td>04</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Finalizar episodio desde el Modo SOS</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero finalizar el episodio al terminar la crisis para registrar el evento correctamente.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Finalización exitosa</strong><br>
      Dado que el cuidador presiona "Finalizar episodio" al completar la guía, cuando confirma la acción, entonces el sistema cierra el Modo SOS, calcula la duración total y guarda el episodio en el historial.<br><br>
      <strong>Scenario 2: Finalización anticipada</strong><br>
      Dado que el cuidador presiona "Finalizar episodio" antes de completar todos los pasos, cuando el sistema detecta que la guía no terminó, entonces solicita confirmación y registra el episodio como "finalizado anticipadamente".
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>24</td>
      <td><strong>Epic ID</strong></td>
      <td>04</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Acceder al Modo SOS desde pantalla principal</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero acceder al Modo SOS con un solo toque desde cualquier parte de la app para reaccionar rápido.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Acceso rápido exitoso</strong><br>
      Dado que el cuidador presiona el botón flotante de SOS visible en todas las pantallas, cuando el sistema procesa la acción, entonces abre inmediatamente la guía sin pasos intermedios de navegación.<br><br>
      <strong>Scenario 2: Botón no visible por configuración</strong><br>
      Dado que el cuidador ha ocultado el botón flotante en configuración, cuando intenta buscarlo en la pantalla principal, entonces el sistema muestra un acceso alternativo desde el menú principal.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>25</td>
      <td><strong>Epic ID</strong></td>
      <td>05</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Seleccionar estímulo visual de autorregulación</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario neurodivergente quiero elegir un estímulo visual para ayudarme a calmarme.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Selección exitosa</strong><br>
      Dado que el usuario presiona un estímulo visual de la galería (por ejemplo, burbujas o luces suaves), cuando el sistema procesa la selección, entonces reproduce la animación a pantalla completa con controles simples de pausa.<br><br>
      <strong>Scenario 2: Estímulo no disponible sin conexión</strong><br>
      Dado que el usuario selecciona un estímulo que requiere descarga y no hay conexión a internet, cuando el sistema intenta cargar el recurso, entonces muestra un mensaje breve y ofrece estímulos ya descargados como alternativa.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>26</td>
      <td><strong>Epic ID</strong></td>
      <td>05</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Seleccionar estímulo auditivo de autorregulación</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario neurodivergente quiero elegir un sonido relajante para ayudarme a regular mis emociones.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Reproducción exitosa</strong><br>
      Dado que el usuario presiona un estímulo auditivo (por ejemplo, sonidos de lluvia), cuando el sistema procesa la selección, entonces reproduce el audio en bucle con controles de volumen visibles.<br><br>
      <strong>Scenario 2: Volumen del dispositivo en silencio</strong><br>
      Dado que el usuario selecciona un estímulo auditivo con el dispositivo en modo silencio, cuando el sistema detecta la configuración, entonces muestra un aviso sugiriendo activar el volumen o cambiar a un estímulo visual.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>27</td>
      <td><strong>Epic ID</strong></td>
      <td>05</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Ajustar intensidad del estímulo</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario neurodivergente quiero ajustar la intensidad de los estímulos para adaptarlos a lo que necesito en el momento.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Ajuste exitoso</strong><br>
      Dado que el usuario mueve el control deslizante de intensidad mientras el estímulo está activo, cuando suelta el control, entonces el sistema aplica el cambio de intensidad en tiempo real.<br><br>
      <strong>Scenario 2: Intensidad fuera de rango</strong><br>
      Dado que el usuario intenta forzar el control deslizante más allá del límite máximo, cuando el sistema valida el rango permitido, entonces mantiene la intensidad en el valor máximo configurado.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>28</td>
      <td><strong>Epic ID</strong></td>
      <td>05</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Guardar estímulos favoritos</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario neurodivergente quiero guardar mis estímulos favoritos para acceder a ellos más rápido.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Guardado exitoso</strong><br>
      Dado que el usuario presiona el ícono de estrella sobre un estímulo, cuando el sistema procesa la acción, entonces agrega el estímulo a la sección "Favoritos".<br><br>
      <strong>Scenario 2: Eliminar de favoritos</strong><br>
      Dado que el usuario presiona nuevamente el ícono de estrella sobre un estímulo ya marcado, cuando el sistema procesa la acción, entonces lo retira de la sección "Favoritos".
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>29</td>
      <td><strong>Epic ID</strong></td>
      <td>05</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Activar modo de baja estimulación</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario neurodivergente quiero activar un modo con menos elementos visuales y sonoros cuando estoy sobreestimulado.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Activación exitosa</strong><br>
      Dado que el usuario presiona el interruptor "Modo de baja estimulación", cuando el sistema procesa la acción, entonces reduce colores, animaciones y sonidos en toda la interfaz.<br><br>
      <strong>Scenario 2: Desactivación del modo</strong><br>
      Dado que el usuario presiona nuevamente el interruptor estando el modo activo, cuando el sistema procesa la acción, entonces restaura la interfaz visual y sonora estándar.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>30</td>
      <td><strong>Epic ID</strong></td>
      <td>05</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Usar temporizador de calma</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario neurodivergente quiero usar un temporizador visual mientras me autorregulo para saber cuánto tiempo llevo en la actividad.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Temporizador iniciado</strong><br>
      Dado que el usuario presiona "Iniciar" en el temporizador de calma, cuando el sistema procesa la acción, entonces muestra una cuenta regresiva visual sin números que pueda resultar estresante.<br><br>
      <strong>Scenario 2: Temporizador finalizado</strong><br>
      Dado que el temporizador llega a cero mientras el usuario continúa en la pantalla, cuando el sistema detecta el fin del tiempo, entonces muestra una transición suave preguntando si desea continuar o finalizar.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>31</td>
      <td><strong>Epic ID</strong></td>
      <td>06</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Visualizar tablero de pictogramas</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario neurodivergente quiero visualizar un tablero de pictogramas para comunicar lo que necesito.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Visualización correcta</strong><br>
      Dado que el usuario abre la sección "Comunicación", cuando el sistema carga el tablero, entonces muestra los pictogramas organizados por categorías con íconos claros y grandes.<br><br>
      <strong>Scenario 2: Tablero vacío por configuración incompleta</strong><br>
      Dado que el perfil del usuario no tiene pictogramas configurados, cuando el usuario abre la sección "Comunicación", entonces el sistema muestra un set de pictogramas básicos por defecto.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>32</td>
      <td><strong>Epic ID</strong></td>
      <td>06</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Seleccionar pictograma para comunicar una necesidad</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario neurodivergente quiero presionar un pictograma para comunicar una necesidad a mi cuidador.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Selección exitosa</strong><br>
      Dado que el usuario presiona el pictograma "Necesito silencio", cuando el sistema procesa la selección, entonces reproduce el audio asociado y envía una notificación al cuidador vinculado si está disponible.<br><br>
      <strong>Scenario 2: Sin cuidador vinculado activo</strong><br>
      Dado que el usuario presiona un pictograma y no hay ningún cuidador con la app abierta, cuando el sistema procesa la selección, entonces reproduce el audio localmente y guarda el mensaje para notificarlo cuando el cuidador se conecte.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>33</td>
      <td><strong>Epic ID</strong></td>
      <td>06</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Personalizar pictogramas favoritos</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero marcar los pictogramas más usados como favoritos para que el usuario los encuentre más fácilmente.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Marcado exitoso</strong><br>
      Dado que el cuidador presiona el ícono de estrella sobre un pictograma, cuando el sistema procesa la acción, entonces el pictograma aparece en la sección "Favoritos" del tablero.<br><br>
      <strong>Scenario 2: Límite de favoritos alcanzado</strong><br>
      Dado que el cuidador intenta marcar un noveno pictograma como favorito cuando el límite es ocho, cuando el sistema valida el límite, entonces muestra el mensaje "Has alcanzado el máximo de favoritos" y sugiere quitar uno existente.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>34</td>
      <td><strong>Epic ID</strong></td>
      <td>06</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Agregar pictograma personalizado</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero agregar un pictograma personalizado con una foto real para representar objetos específicos del usuario.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Creación exitosa</strong><br>
      Dado que el cuidador sube una imagen, escribe una etiqueta y presiona "Guardar", cuando los datos son válidos, entonces el sistema agrega el pictograma personalizado a la categoría seleccionada.<br><br>
      <strong>Scenario 2: Imagen no válida</strong><br>
      Dado que el cuidador intenta subir un archivo que no es una imagen, cuando el sistema valida el archivo, entonces muestra el mensaje "Formato de imagen no válido" y no crea el pictograma.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>35</td>
      <td><strong>Epic ID</strong></td>
      <td>06</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Organizar pictogramas por categoría</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero organizar los pictogramas por categorías para que el tablero sea más fácil de navegar.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Organización exitosa</strong><br>
      Dado que el cuidador arrastra un pictograma a la categoría "Emociones", cuando suelta el elemento, entonces el sistema mueve el pictograma a la nueva categoría.<br><br>
      <strong>Scenario 2: Categoría llena</strong><br>
      Dado que el cuidador intenta agregar un pictograma a una categoría que alcanzó su límite de elementos visibles, cuando el sistema valida el límite, entonces sugiere crear una subcategoría o mover otro pictograma antes de continuar.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>36</td>
      <td><strong>Epic ID</strong></td>
      <td>06</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Reproducir audio asociado al pictograma</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario neurodivergente quiero escuchar el audio de un pictograma antes de seleccionarlo para confirmar que es el correcto.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Reproducción exitosa</strong><br>
      Dado que el usuario mantiene presionado un pictograma, cuando el sistema detecta la acción, entonces reproduce el audio asociado sin enviar la comunicación al cuidador.<br><br>
      <strong>Scenario 2: Pictograma sin audio configurado</strong><br>
      Dado que el usuario mantiene presionado un pictograma personalizado sin audio grabado, cuando el sistema detecta la ausencia de audio, entonces reproduce la etiqueta de texto mediante voz sintetizada como alternativa.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>37</td>
      <td><strong>Epic ID</strong></td>
      <td>07</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Enviar solicitud de ayuda al cuidador</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario neurodivergente quiero enviar una solicitud de ayuda con un solo toque cuando necesito apoyo.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Envío exitoso</strong><br>
      Dado que el usuario presiona el botón "Necesito ayuda", cuando el sistema procesa la solicitud, entonces notifica de inmediato a los cuidadores vinculados con la ubicación aproximada si está habilitada.<br><br>
      <strong>Scenario 2: Sin cuidadores vinculados</strong><br>
      Dado que el usuario presiona "Necesito ayuda" y no tiene cuidadores asociados al perfil, cuando el sistema valida la configuración, entonces muestra un mensaje indicando que debe vincular al menos un cuidador para usar esta función.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>38</td>
      <td><strong>Epic ID</strong></td>
      <td>07</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Recibir notificación de solicitud de ayuda</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero recibir una notificación inmediata cuando el usuario solicita ayuda para poder responder a tiempo.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Notificación recibida</strong><br>
      Dado que el usuario a cargo envía una solicitud de ayuda, cuando el sistema procesa la solicitud, entonces el cuidador recibe una notificación push con sonido distintivo y la opción de abrir el Modo SOS directamente.<br><br>
      <strong>Scenario 2: Cuidador sin conexión a internet</strong><br>
      Dado que el usuario envía una solicitud de ayuda y el cuidador no tiene conexión, cuando el sistema intenta enviar la notificación, entonces la entrega en cuanto el dispositivo del cuidador recupera la conexión.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>39</td>
      <td><strong>Epic ID</strong></td>
      <td>07</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Confirmar recepción de la solicitud</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero confirmar que recibí la solicitud de ayuda para que el sistema sepa que ya estoy atendiendo la situación.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Confirmación exitosa</strong><br>
      Dado que el cuidador presiona "Voy en camino" en la notificación recibida, cuando el sistema procesa la acción, entonces actualiza el estado de la solicitud a "Atendida" y lo refleja en el dispositivo del usuario si aplica.<br><br>
      <strong>Scenario 2: Múltiples cuidadores confirman</strong><br>
      Dado que dos cuidadores vinculados confirman la misma solicitud, cuando el sistema procesa ambas confirmaciones, entonces registra a ambos como atendiendo y notifica a cada uno que el otro también está en camino.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>40</td>
      <td><strong>Epic ID</strong></td>
      <td>07</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Cancelar solicitud de ayuda</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario neurodivergente quiero cancelar una solicitud de ayuda si ya no la necesito.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Cancelación exitosa</strong><br>
      Dado que el usuario presiona "Cancelar solicitud" antes de que el cuidador confirme, cuando el sistema procesa la acción, entonces notifica al cuidador que la solicitud fue cancelada.<br><br>
      <strong>Scenario 2: Cancelación tras confirmación del cuidador</strong><br>
      Dado que el usuario intenta cancelar la solicitud después de que el cuidador ya confirmó que va en camino, cuando el sistema valida el estado, entonces permite la cancelación pero notifica al cuidador que la situación se resolvió.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>41</td>
      <td><strong>Epic ID</strong></td>
      <td>07</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Consultar historial de solicitudes de ayuda</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero consultar el historial de solicitudes de ayuda para identificar con qué frecuencia ocurren.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Consulta exitosa</strong><br>
      Dado que el cuidador accede a la sección "Historial de solicitudes", cuando el sistema carga los datos, entonces muestra la lista de solicitudes con fecha, hora y tiempo de respuesta.<br><br>
      <strong>Scenario 2: Sin solicitudes registradas</strong><br>
      Dado que el cuidador accede al historial y no existen solicitudes previas, cuando el sistema procesa la consulta, entonces muestra el mensaje "Aún no se han registrado solicitudes de ayuda".
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>42</td>
      <td><strong>Epic ID</strong></td>
      <td>08</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Visualizar resumen de episodios recientes</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero ver un resumen de los episodios recientes al ingresar a la app para conocer el estado general del usuario.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Visualización correcta</strong><br>
      Dado que el cuidador ingresa a la pantalla de inicio, cuando el sistema carga los datos, entonces muestra el número de episodios de la última semana y su duración promedio.<br><br>
      <strong>Scenario 2: Sin episodios en el periodo</strong><br>
      Dado que no se han registrado episodios en los últimos 7 días, cuando el cuidador ingresa a la pantalla de inicio, entonces el sistema muestra un mensaje positivo indicando que no hubo episodios recientes.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>43</td>
      <td><strong>Epic ID</strong></td>
      <td>08</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Visualizar estado actual del usuario</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero ver si el usuario está en un episodio activo para saber si necesita mi atención inmediata.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Estado activo mostrado</strong><br>
      Dado que el usuario tiene un Modo SOS en curso, cuando el cuidador abre la app, entonces el panel de inicio muestra un banner destacado indicando "Episodio en curso" con acceso directo.<br><br>
      <strong>Scenario 2: Estado normal</strong><br>
      Dado que el usuario no tiene ningún episodio activo, cuando el cuidador abre la app, entonces el panel de inicio muestra el estado "Sin episodios activos".
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>44</td>
      <td><strong>Epic ID</strong></td>
      <td>08</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Acceder a módulos mediante accesos directos</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero acceder rápidamente a los módulos principales desde el home para ahorrar tiempo de navegación.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Acceso exitoso</strong><br>
      Dado que el cuidador presiona el acceso directo "Recomendaciones", cuando el sistema procesa la acción, entonces navega directamente al módulo de recomendaciones personalizadas.<br><br>
      <strong>Scenario 2: Acceso directo deshabilitado por plan</strong><br>
      Dado que el cuidador presiona un acceso directo a una función premium sin tener el plan activo, cuando el sistema valida el plan, entonces muestra un mensaje invitando a actualizar el plan para acceder a la función.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>45</td>
      <td><strong>Epic ID</strong></td>
      <td>08</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Visualizar alertas recientes en el home</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero ver las alertas más recientes en el home para no perder información importante.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Visualización correcta</strong><br>
      Dado que existen alertas generadas en las últimas 48 horas, cuando el cuidador ingresa al home, entonces el sistema muestra las alertas más recientes ordenadas por fecha.<br><br>
      <strong>Scenario 2: Sin alertas recientes</strong><br>
      Dado que no existen alertas generadas en las últimas 48 horas, cuando el cuidador ingresa al home, entonces el sistema muestra el mensaje "No hay alertas recientes".
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>46</td>
      <td><strong>Epic ID</strong></td>
      <td>08</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Visualizar recomendaciones personalizadas en el home</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero ver una recomendación destacada en el home para aplicarla en el día a día.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Recomendación mostrada</strong><br>
      Dado que el sistema ha generado recomendaciones para el perfil activo, cuando el cuidador ingresa al home, entonces se muestra una recomendación destacada con opción de ver más detalle.<br><br>
      <strong>Scenario 2: Sin recomendaciones generadas aún</strong><br>
      Dado que el perfil es nuevo y no tiene suficiente historial, cuando el cuidador ingresa al home, entonces el sistema muestra un mensaje invitando a completar el perfil para generar recomendaciones.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>47</td>
      <td><strong>Epic ID</strong></td>
      <td>08</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Cambiar entre perfiles de usuarios a cargo</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador con varios usuarios a cargo quiero cambiar entre sus perfiles para gestionar a cada uno por separado.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Cambio exitoso</strong><br>
      Dado que el cuidador presiona el selector de perfil y elige otro usuario a cargo, cuando el sistema procesa la selección, entonces actualiza todo el panel de inicio con la información del perfil seleccionado.<br><br>
      <strong>Scenario 2: Un solo perfil disponible</strong><br>
      Dado que el cuidador solo tiene un usuario a cargo, cuando presiona el selector de perfil, entonces el sistema muestra únicamente la opción de agregar un nuevo perfil.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>48</td>
      <td><strong>Epic ID</strong></td>
      <td>09</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Registrar episodio automáticamente al usar el Modo SOS</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como sistema quiero registrar automáticamente cada episodio gestionado mediante el Modo SOS para construir un historial confiable.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Registro exitoso</strong><br>
      Dado que el cuidador finaliza un episodio desde el Modo SOS, cuando el sistema procesa el cierre, entonces guarda fecha, duración, pasos completados y perfil asociado en el historial.<br><br>
      <strong>Scenario 2: Cierre inesperado de la app durante el episodio</strong><br>
      Dado que la aplicación se cierra abruptamente mientras el Modo SOS está activo, cuando el sistema detecta la interrupción, entonces registra el episodio como "incompleto" con la información disponible hasta el momento del cierre.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>49</td>
      <td><strong>Epic ID</strong></td>
      <td>09</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Visualizar historial de episodios</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero visualizar el historial completo de episodios para revisar la evolución del usuario.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Visualización correcta</strong><br>
      Dado que el cuidador accede a la sección "Historial", cuando el sistema carga los datos, entonces muestra la lista de episodios ordenados del más reciente al más antiguo.<br><br>
      <strong>Scenario 2: Historial vacío</strong><br>
      Dado que el perfil del usuario no tiene episodios registrados, cuando el cuidador accede a "Historial", entonces el sistema muestra el mensaje "Aún no se han registrado episodios".
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>50</td>
      <td><strong>Epic ID</strong></td>
      <td>09</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Filtrar historial de episodios por fecha</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero filtrar el historial por rango de fechas para analizar un periodo específico.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Filtrado exitoso</strong><br>
      Dado que el cuidador selecciona un rango de fechas y presiona "Aplicar filtro", cuando existen episodios en ese rango, entonces el sistema muestra únicamente los episodios dentro del periodo seleccionado.<br><br>
      <strong>Scenario 2: Sin resultados en el rango</strong><br>
      Dado que el cuidador selecciona un rango de fechas sin episodios registrados, cuando el sistema aplica el filtro, entonces muestra el mensaje "No se encontraron episodios en el periodo seleccionado".
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>51</td>
      <td><strong>Epic ID</strong></td>
      <td>09</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Ver detalle de un episodio registrado</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero ver el detalle completo de un episodio para entender qué ocurrió y cómo se resolvió.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Visualización correcta</strong><br>
      Dado que el cuidador presiona un episodio de la lista, cuando el sistema carga la información, entonces muestra duración, pasos completados de la guía SOS y notas asociadas.<br><br>
      <strong>Scenario 2: Episodio eliminado previamente</strong><br>
      Dado que el cuidador intenta abrir un episodio que fue eliminado, cuando el sistema busca el registro, entonces muestra el mensaje "Este episodio ya no está disponible".
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>52</td>
      <td><strong>Epic ID</strong></td>
      <td>09</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Agregar notas manuales a un episodio</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero agregar notas a un episodio registrado para complementar la información con mi propia observación.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Nota agregada exitosamente</strong><br>
      Dado que el cuidador escribe una nota en el detalle del episodio y presiona "Guardar nota", cuando el texto no está vacío, entonces el sistema guarda la nota asociada al episodio.<br><br>
      <strong>Scenario 2: Nota vacía</strong><br>
      Dado que el cuidador presiona "Guardar nota" sin escribir ningún texto, cuando el sistema valida el campo, entonces muestra el mensaje "Escribe una nota antes de guardar" y no la registra.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>53</td>
      <td><strong>Epic ID</strong></td>
      <td>10</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Generar recomendaciones según el perfil del usuario</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como sistema quiero generar recomendaciones personalizadas a partir del perfil y el historial de episodios para ayudar al cuidador.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Generación exitosa</strong><br>
      Dado que el perfil cuenta con al menos 3 episodios registrados, cuando el sistema procesa el historial, entonces genera recomendaciones basadas en los patrones detectados y las muestra al cuidador.<br><br>
      <strong>Scenario 2: Datos insuficientes para generar recomendaciones</strong><br>
      Dado que el perfil tiene menos de 3 episodios registrados, cuando el sistema evalúa el historial, entonces muestra recomendaciones generales por defecto en lugar de personalizadas.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>54</td>
      <td><strong>Epic ID</strong></td>
      <td>10</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Visualizar guía de actuación recomendada</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero visualizar el detalle de una recomendación para saber cómo aplicarla.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Visualización correcta</strong><br>
      Dado que el cuidador presiona una recomendación de la lista, cuando el sistema carga el contenido, entonces muestra el detalle con pasos sugeridos y el motivo de la recomendación.<br><br>
      <strong>Scenario 2: Recomendación desactualizada</strong><br>
      Dado que la recomendación fue generada con datos que ya no reflejan el perfil actual, cuando el cuidador la visualiza, entonces el sistema muestra un aviso sugiriendo actualizar las recomendaciones.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>55</td>
      <td><strong>Epic ID</strong></td>
      <td>10</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Calificar la utilidad de una recomendación</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero calificar si una recomendación fue útil para mejorar las futuras sugerencias.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Calificación registrada</strong><br>
      Dado que el cuidador presiona "Útil" o "No útil" sobre una recomendación, cuando el sistema procesa la acción, entonces guarda la calificación y ajusta el peso de recomendaciones similares.<br><br>
      <strong>Scenario 2: Calificación duplicada</strong><br>
      Dado que el cuidador intenta calificar una recomendación que ya calificó previamente, cuando el sistema valida el registro previo, entonces permite modificar la calificación anterior en lugar de duplicarla.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>56</td>
      <td><strong>Epic ID</strong></td>
      <td>10</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Guardar recomendación como favorita</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero guardar una recomendación como favorita para consultarla rápidamente en el futuro.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Guardado exitoso</strong><br>
      Dado que el cuidador presiona el ícono de marcador sobre una recomendación, cuando el sistema procesa la acción, entonces la agrega a la sección "Recomendaciones guardadas".<br><br>
      <strong>Scenario 2: Recomendación ya guardada</strong><br>
      Dado que el cuidador presiona el ícono de marcador sobre una recomendación que ya estaba guardada, cuando el sistema procesa la acción, entonces la retira de la sección "Recomendaciones guardadas".
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>57</td>
      <td><strong>Epic ID</strong></td>
      <td>10</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Actualizar recomendaciones tras nuevos episodios</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como sistema quiero actualizar las recomendaciones cuando se registran nuevos episodios para mantenerlas vigentes.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Actualización exitosa</strong><br>
      Dado que se registra un nuevo episodio con un patrón distinto al histórico, cuando el sistema procesa el nuevo dato, entonces recalcula las recomendaciones y notifica al cuidador que hay novedades.<br><br>
      <strong>Scenario 2: Sin cambios relevantes</strong><br>
      Dado que el nuevo episodio no altera los patrones existentes, cuando el sistema evalúa el impacto, entonces mantiene las recomendaciones actuales sin generar una notificación.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>58</td>
      <td><strong>Epic ID</strong></td>
      <td>11</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Visualizar planes de suscripción disponibles</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero visualizar los planes disponibles para comparar sus beneficios antes de decidir.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Visualización correcta</strong><br>
      Dado que el usuario accede a la sección "Planes", cuando el sistema carga la información, entonces muestra el Plan Free y el Plan Premium con sus respectivas características.<br><br>
      <strong>Scenario 2: Error al cargar planes</strong><br>
      Dado que ocurre un error de comunicación con el servidor al cargar los planes, cuando el usuario accede a la sección "Planes", entonces el sistema muestra el mensaje "No se pudieron cargar los planes, inténtalo más tarde".
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>59</td>
      <td><strong>Epic ID</strong></td>
      <td>11</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Seleccionar plan de suscripción</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario con Plan Free quiero seleccionar el Plan Premium para continuar con el proceso de suscripción.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Selección exitosa</strong><br>
      Dado que el usuario presiona "Elegir plan" en la tarjeta del Plan Premium, cuando el sistema procesa la selección, entonces resalta la tarjeta y habilita el botón "Continuar".<br><br>
      <strong>Scenario 2: Intento de continuar sin seleccionar plan</strong><br>
      Dado que el usuario presiona "Continuar" sin haber seleccionado ningún plan, cuando el sistema valida la selección, entonces muestra un mensaje indicando que debe elegir un plan primero.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>60</td>
      <td><strong>Epic ID</strong></td>
      <td>11</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Registrar datos de facturación</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero registrar mis datos de facturación para completar el proceso de suscripción.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Registro exitoso</strong><br>
      Dado que el usuario completa el formulario de facturación con datos válidos y presiona "Continuar al pago", cuando el sistema valida la información, entonces registra los datos y habilita el resumen previo al cobro.<br><br>
      <strong>Scenario 2: Datos inválidos</strong><br>
      Dado que el usuario ingresa datos incompletos en el formulario, cuando presiona "Continuar al pago", entonces el sistema resalta los campos con error y no permite avanzar.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>61</td>
      <td><strong>Epic ID</strong></td>
      <td>11</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Procesar cobro de suscripción</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero procesar el cobro de mi suscripción para activar el Plan Premium.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Cobro exitoso</strong><br>
      Dado que el usuario presiona "Pagar y activar suscripción" con datos de facturación válidos, cuando el cobro es aprobado, entonces el sistema registra el pago y habilita la activación del plan.<br><br>
      <strong>Scenario 2: Error durante el cobro</strong><br>
      Dado que el usuario presiona "Pagar y activar suscripción" y la tarjeta es rechazada, cuando el sistema procesa el intento de cobro, entonces muestra el motivo del error y no activa la suscripción.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>62</td>
      <td><strong>Epic ID</strong></td>
      <td>11</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Activar suscripción</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero que mi suscripción se active automáticamente tras un pago exitoso para acceder de inmediato a las funciones premium.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Activación exitosa</strong><br>
      Dado que el cobro fue procesado correctamente, cuando el sistema confirma el pago, entonces activa el Plan Premium y redirige al usuario al panel de suscripción.<br><br>
      <strong>Scenario 2: Pago no confirmado</strong><br>
      Dado que el cobro no fue confirmado por la pasarela de pago, cuando el sistema intenta activar la suscripción, entonces mantiene al usuario en el Plan Free y no otorga acceso premium.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>63</td>
      <td><strong>Epic ID</strong></td>
      <td>11</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Cancelar proceso de suscripción antes de confirmar</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero poder salir del flujo de suscripción antes de pagar si cambio de opinión.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Cancelación exitosa</strong><br>
      Dado que el usuario presiona "Cancelar" en cualquier paso previo al pago, cuando el sistema procesa la acción, entonces regresa a la sección "Planes" sin registrar ningún cobro.<br><br>
      <strong>Scenario 2: Cierre accidental de la app durante el proceso</strong><br>
      Dado que la aplicación se cierra mientras el usuario completaba el formulario de facturación, cuando el usuario vuelve a abrir la app, entonces el sistema no conserva datos sensibles de pago y solicita reiniciar el proceso.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>64</td>
      <td><strong>Epic ID</strong></td>
      <td>12</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Visualizar panel de suscripción</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero visualizar el panel de mi suscripción para conocer el estado general de mi plan.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Visualización correcta</strong><br>
      Dado que el usuario accede a la sección "Suscripción", cuando el sistema carga los datos, entonces muestra el plan actual, la fecha de renovación y las acciones disponibles.<br><br>
      <strong>Scenario 2: Usuario con Plan Free</strong><br>
      Dado que el usuario solo tiene el Plan Free asignado por defecto, cuando accede a "Suscripción", entonces el panel muestra el estado del Plan Free y la opción de actualizar al Plan Premium.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>65</td>
      <td><strong>Epic ID</strong></td>
      <td>12</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Consultar estado de suscripción</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero ver una etiqueta clara del estado de mi suscripción para saber si está activa o no.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Estado activo mostrado</strong><br>
      Dado que el usuario tiene una suscripción de pago vigente, cuando ingresa al panel de "Suscripción", entonces el sistema muestra la etiqueta "Activa".<br><br>
      <strong>Scenario 2: Estado cancelado mostrado</strong><br>
      Dado que el usuario tiene una suscripción cancelada, cuando ingresa al panel de "Suscripción", entonces el sistema muestra la etiqueta "Cancelada" junto con la fecha en que perdió el acceso premium.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>66</td>
      <td><strong>Epic ID</strong></td>
      <td>12</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Renovar suscripción</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario con una suscripción activa o próxima a vencer quiero renovarla para mantener el acceso premium.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Renovación exitosa</strong><br>
      Dado que el usuario presiona "Renovar suscripción" y confirma la acción, cuando el cobro es aprobado, entonces el sistema actualiza la nueva fecha de vencimiento en el panel.<br><br>
      <strong>Scenario 2: Renovación no permitida</strong><br>
      Dado que el usuario está en el Plan Free y presiona "Renovar suscripción", cuando el sistema valida el plan actual, entonces muestra un mensaje indicando que primero debe contratar un plan de pago.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>67</td>
      <td><strong>Epic ID</strong></td>
      <td>12</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Actualizar método de pago</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero actualizar mi método de pago para asegurar que futuros cobros se procesen correctamente.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Actualización exitosa</strong><br>
      Dado que el usuario ingresa los datos de una nueva tarjeta y presiona "Guardar método de pago", cuando los datos son válidos, entonces el sistema reemplaza el método de pago anterior por el nuevo.<br><br>
      <strong>Scenario 2: Datos de tarjeta inválidos</strong><br>
      Dado que el usuario ingresa un número de tarjeta incompleto, cuando presiona "Guardar método de pago", entonces el sistema resalta el campo con error y no guarda el método de pago.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>68</td>
      <td><strong>Epic ID</strong></td>
      <td>12</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Descargar historial de pagos</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero descargar el historial de pagos de mi suscripción para mis propios registros.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Descarga exitosa</strong><br>
      Dado que el usuario presiona "Descargar historial" en el panel de suscripción, cuando existen pagos registrados, entonces el sistema genera y descarga un archivo con el detalle de los pagos realizados.<br><br>
      <strong>Scenario 2: Sin pagos registrados</strong><br>
      Dado que el usuario solo ha tenido el Plan Free y presiona "Descargar historial", cuando el sistema valida los registros, entonces muestra el mensaje "No hay pagos registrados para descargar".
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>69</td>
      <td><strong>Epic ID</strong></td>
      <td>12</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Solicitar cancelación de suscripción</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario con una suscripción activa quiero solicitar su cancelación para detener la renovación automática.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Solicitud registrada correctamente</strong><br>
      Dado que el usuario presiona "Solicitar cancelación" y confirma la acción, cuando el sistema procesa la solicitud, entonces registra la cancelación programada y mantiene el acceso hasta la fecha de vencimiento.<br><br>
      <strong>Scenario 2: Cancelación de la solicitud antes de confirmar</strong><br>
      Dado que el usuario presiona "Mantener plan" en el modal de confirmación, cuando el sistema procesa la acción, entonces cierra el modal sin registrar ninguna solicitud de cancelación.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>70</td>
      <td><strong>Epic ID</strong></td>
      <td>13</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Registrar institución</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como representante de una institución quiero registrar a mi institución en la plataforma para acceder al plan B2B.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Registro exitoso</strong><br>
      Dado que el representante completa el formulario institucional con datos válidos y presiona "Registrar institución", cuando el sistema valida la información, entonces crea la cuenta institucional en estado "Pendiente de aprobación".<br><br>
      <strong>Scenario 2: Datos incompletos</strong><br>
      Dado que el representante deja el campo RUC vacío y presiona "Registrar institución", cuando el sistema valida el formulario, entonces resalta el campo con el mensaje "Este campo es obligatorio" y no registra la institución.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>71</td>
      <td><strong>Epic ID</strong></td>
      <td>13</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Gestionar perfiles de estudiantes desde la institución</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como administrador institucional quiero gestionar los perfiles de los estudiantes para mantener organizada la información de cada uno.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Creación exitosa de perfil institucional</strong><br>
      Dado que el administrador completa los datos de un nuevo estudiante y presiona "Agregar estudiante", cuando los datos son válidos, entonces el sistema crea el perfil y lo asocia a la institución.<br><br>
      <strong>Scenario 2: Límite de estudiantes del plan alcanzado</strong><br>
      Dado que el administrador intenta agregar un estudiante cuando ya alcanzó el límite contratado, cuando el sistema valida el plan, entonces muestra un mensaje indicando que debe ampliar el plan para agregar más estudiantes.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>72</td>
      <td><strong>Epic ID</strong></td>
      <td>13</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Asignar perfiles a educadores</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como administrador institucional quiero asignar estudiantes a educadores específicos para delegar el acompañamiento diario.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Asignación exitosa</strong><br>
      Dado que el administrador selecciona un estudiante y un educador y presiona "Asignar", cuando el sistema procesa la asignación, entonces el educador obtiene acceso al perfil del estudiante asignado.<br><br>
      <strong>Scenario 2: Educador sin cuenta activa</strong><br>
      Dado que el administrador intenta asignar un estudiante a un educador que aún no aceptó su invitación, cuando el sistema valida el estado de la cuenta, entonces muestra un mensaje indicando que el educador debe activar su cuenta primero.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>73</td>
      <td><strong>Epic ID</strong></td>
      <td>13</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Visualizar dashboard institucional</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como administrador institucional quiero visualizar un dashboard con el estado general de todos los estudiantes para supervisar la institución.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Visualización correcta</strong><br>
      Dado que el administrador accede al dashboard institucional, cuando el sistema carga los datos, entonces muestra indicadores agregados como número de episodios totales y estudiantes activos.<br><br>
      <strong>Scenario 2: Institución sin estudiantes registrados</strong><br>
      Dado que la institución aún no ha registrado estudiantes, cuando el administrador accede al dashboard, entonces el sistema muestra un mensaje invitando a agregar el primer estudiante.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>74</td>
      <td><strong>Epic ID</strong></td>
      <td>13</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Generar reporte agregado de la institución</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como administrador institucional quiero generar un reporte agregado para presentar resultados a las autoridades del centro.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Generación exitosa</strong><br>
      Dado que el administrador selecciona un rango de fechas y presiona "Generar reporte", cuando existen datos en el periodo seleccionado, entonces el sistema genera un reporte descargable con estadísticas agregadas y anonimizadas.<br><br>
      <strong>Scenario 2: Periodo sin datos suficientes</strong><br>
      Dado que el administrador selecciona un rango de fechas sin episodios registrados, cuando presiona "Generar reporte", entonces el sistema muestra el mensaje "No hay datos suficientes para generar el reporte".
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>75</td>
      <td><strong>Epic ID</strong></td>
      <td>14</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Visualizar el centro de soporte</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero visualizar el centro de soporte para encontrar ayuda sobre el uso de la aplicación.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Visualización correcta</strong><br>
      Dado que el usuario presiona el botón de "Ayuda", cuando el sistema carga la sección, entonces muestra las categorías principales de artículos y un buscador.<br><br>
      <strong>Scenario 2: Error al cargar el centro de soporte</strong><br>
      Dado que ocurre un error de comunicación al abrir el centro de soporte, cuando el usuario presiona el botón de "Ayuda", entonces el sistema muestra el mensaje "No se pudo cargar el centro de soporte, inténtalo más tarde".
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>76</td>
      <td><strong>Epic ID</strong></td>
      <td>14</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Buscar artículo de ayuda</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero buscar un artículo específico para resolver mi duda rápidamente.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Búsqueda exitosa</strong><br>
      Dado que el usuario ingresa "cómo activar el Modo SOS" en el buscador, cuando el sistema procesa la búsqueda, entonces muestra los artículos relacionados ordenados por relevancia.<br><br>
      <strong>Scenario 2: Sin resultados</strong><br>
      Dado que el usuario ingresa un término que no coincide con ningún artículo, cuando el sistema procesa la búsqueda, entonces muestra el mensaje "No se encontraron resultados" y sugiere reportar un problema.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>77</td>
      <td><strong>Epic ID</strong></td>
      <td>14</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Consultar artículo de ayuda</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero abrir un artículo de ayuda para leer la solución completa.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Consulta exitosa</strong><br>
      Dado que el usuario presiona un artículo de la lista, cuando el sistema carga el contenido, entonces muestra el texto completo con imágenes explicativas si están disponibles.<br><br>
      <strong>Scenario 2: Artículo no disponible en el idioma seleccionado</strong><br>
      Dado que el usuario tiene la interfaz configurada en un idioma sin traducción para ese artículo, cuando abre el artículo, entonces el sistema muestra el contenido en el idioma por defecto con un aviso.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>78</td>
      <td><strong>Epic ID</strong></td>
      <td>14</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Reportar un problema</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero reportar un problema técnico para que el equipo de soporte lo revise.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Reporte enviado correctamente</strong><br>
      Dado que el usuario completa el formulario de reporte con una descripción y presiona "Enviar", cuando los datos son válidos, entonces el sistema registra el reporte y lo envía al equipo de soporte.<br><br>
      <strong>Scenario 2: Descripción vacía</strong><br>
      Dado que el usuario presiona "Enviar" sin escribir una descripción del problema, cuando el sistema valida el formulario, entonces muestra el mensaje "Este campo es obligatorio" y no envía el reporte.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>79</td>
      <td><strong>Epic ID</strong></td>
      <td>14</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Confirmar envío del reporte</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero recibir una confirmación tras enviar un reporte para saber que fue registrado.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Confirmación mostrada</strong><br>
      Dado que el usuario envía un reporte válido, cuando el sistema procesa el envío, entonces muestra una pantalla de confirmación con un número de referencia del caso.<br><br>
      <strong>Scenario 2: Error al enviar el reporte</strong><br>
      Dado que ocurre un error de conexión al momento de enviar el reporte, cuando el usuario presiona "Enviar", entonces el sistema muestra el mensaje "No se pudo enviar el reporte, inténtalo nuevamente" y conserva el texto escrito.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>80</td>
      <td><strong>Epic ID</strong></td>
      <td>15</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Visualizar la propuesta de valor</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como visitante quiero ver la propuesta de valor de Nubi al ingresar a la landing page.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Visualización correcta</strong><br>
      Dado que el visitante accede a la landing page, cuando la página carga, entonces muestra un mensaje principal explicando el propósito de Nubi y un llamado a la acción.<br><br>
      <strong>Scenario 2: Carga lenta de la página</strong><br>
      Dado que la conexión del visitante es lenta, cuando accede a la landing page, entonces el sistema muestra primero el contenido textual principal antes que las imágenes.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>81</td>
      <td><strong>Epic ID</strong></td>
      <td>15</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Explorar las funcionalidades principales</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como visitante quiero explorar las funcionalidades principales de Nubi para entender cómo puede ayudarme.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Visualización correcta</strong><br>
      Dado que el visitante se desplaza a la sección "Funcionalidades", cuando la sección carga, entonces muestra el Modo SOS, la interfaz de autorregulación y el tablero CAA con una breve descripción de cada uno.<br><br>
      <strong>Scenario 2: Interacción con una funcionalidad destacada</strong><br>
      Dado que el visitante presiona "Conoce más" sobre el Modo SOS, cuando el sistema procesa la acción, entonces despliega información ampliada sobre esa funcionalidad específica.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>82</td>
      <td><strong>Epic ID</strong></td>
      <td>15</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Revisar los planes de suscripción</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como visitante quiero revisar los planes disponibles antes de registrarme para saber cuál se ajusta a mis necesidades.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Visualización correcta</strong><br>
      Dado que el visitante se desplaza a la sección "Planes", cuando la sección carga, entonces muestra el Plan Free y el Plan Premium con sus beneficios y precios.<br><br>
      <strong>Scenario 2: Comparación de planes</strong><br>
      Dado que el visitante presiona "Comparar planes", cuando el sistema procesa la acción, entonces muestra una tabla comparativa detallada de las funcionalidades de cada plan.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>83</td>
      <td><strong>Epic ID</strong></td>
      <td>15</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Consultar las preguntas frecuentes</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como visitante quiero consultar las preguntas frecuentes para resolver dudas antes de registrarme.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Visualización correcta</strong><br>
      Dado que el visitante se desplaza a la sección "Preguntas frecuentes", cuando presiona una pregunta, entonces el sistema despliega la respuesta correspondiente.<br><br>
      <strong>Scenario 2: Pregunta no cubierta</strong><br>
      Dado que el visitante no encuentra respuesta a su duda en la sección, cuando presiona "¿No encontraste tu respuesta?", entonces el sistema lo redirige al formulario de contacto.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>84</td>
      <td><strong>Epic ID</strong></td>
      <td>15</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Iniciar sesión desde la landing page</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como visitante con cuenta existente quiero iniciar sesión directamente desde la landing page.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Redirección exitosa</strong><br>
      Dado que el visitante presiona "Iniciar sesión" en la barra superior, cuando el sistema procesa la acción, entonces lo redirige a la pantalla de inicio de sesión.<br><br>
      <strong>Scenario 2: Sesión ya iniciada</strong><br>
      Dado que el visitante ya tiene una sesión activa en el navegador, cuando presiona "Iniciar sesión", entonces el sistema lo redirige directamente a su panel de inicio sin pedir credenciales.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>85</td>
      <td><strong>Epic ID</strong></td>
      <td>15</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Acceder mediante el botón de acción principal</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como visitante quiero presionar el botón de acción principal para comenzar el proceso de registro rápidamente.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Redirección exitosa</strong><br>
      Dado que el visitante presiona el botón "Comenzar gratis", cuando el sistema procesa la acción, entonces lo redirige al formulario de registro.<br><br>
      <strong>Scenario 2: Botón presionado en dispositivo móvil</strong><br>
      Dado que el visitante presiona "Comenzar gratis" desde un navegador móvil, cuando el sistema detecta el dispositivo, entonces muestra una versión del formulario de registro optimizada para móvil.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>86</td>
      <td><strong>Epic ID</strong></td>
      <td>16</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Navegar entre módulos desde el menú principal</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario autenticado quiero navegar entre los módulos de la aplicación desde un menú principal consistente.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Navegación exitosa</strong><br>
      Dado que el usuario presiona "Historial" en el menú principal, cuando el sistema procesa la acción, entonces muestra la sección correspondiente resaltando el ítem activo en el menú.<br><br>
      <strong>Scenario 2: Módulo restringido por plan</strong><br>
      Dado que el usuario presiona un módulo disponible únicamente en el Plan Premium, cuando el sistema valida el plan, entonces muestra un mensaje invitando a actualizar el plan para acceder.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>87</td>
      <td><strong>Epic ID</strong></td>
      <td>16</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Cambiar idioma de la interfaz</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario autenticado quiero cambiar el idioma de la interfaz para usar la app en el idioma que prefiera.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Cambio exitoso</strong><br>
      Dado que el usuario selecciona "Inglés" en el selector de idioma, cuando el sistema procesa la selección, entonces actualiza todos los textos de la interfaz al idioma elegido.<br><br>
      <strong>Scenario 2: Idioma parcialmente traducido</strong><br>
      Dado que el usuario selecciona un idioma con traducciones incompletas, cuando el sistema aplica el cambio, entonces muestra los textos disponibles en ese idioma y el resto en el idioma por defecto.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>88</td>
      <td><strong>Epic ID</strong></td>
      <td>16</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Gestionar rutas no encontradas</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero recibir una respuesta clara cuando intento acceder a una ruta que no existe dentro de la aplicación.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Manejo correcto</strong><br>
      Dado que el usuario ingresa a una URL o enlace interno inválido, cuando el sistema procesa la solicitud, entonces muestra una pantalla de "Página no encontrada" con un botón para volver al inicio.<br><br>
      <strong>Scenario 2: Enlace expirado a un recurso eliminado</strong><br>
      Dado que el usuario presiona un enlace guardado hacia un episodio que fue eliminado, cuando el sistema busca el recurso, entonces muestra un mensaje indicando que el contenido ya no está disponible.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>89</td>
      <td><strong>Epic ID</strong></td>
      <td>16</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Activar lectura en voz alta de contenidos</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero activar la lectura en voz alta de los textos principales para facilitar la comprensión.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Activación exitosa</strong><br>
      Dado que el usuario activa la opción "Lectura en voz alta" en configuración, cuando selecciona un texto compatible, entonces el sistema reproduce el contenido mediante voz sintetizada.<br><br>
      <strong>Scenario 2: Función no disponible en el idioma actual</strong><br>
      Dado que el usuario activa la lectura en voz alta en un idioma sin motor de voz disponible, cuando el sistema detecta la limitación, entonces muestra un aviso indicando que la función no está disponible para ese idioma.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>90</td>
      <td><strong>Epic ID</strong></td>
      <td>16</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Usar la aplicación en modo offline básico</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero acceder a las funciones esenciales sin conexión a internet para no depender de la señal durante una crisis.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Acceso offline exitoso</strong><br>
      Dado que el dispositivo pierde la conexión a internet, cuando el usuario abre el Modo SOS o el tablero CAA, entonces el sistema permite usar estas funciones con los recursos previamente descargados.<br><br>
      <strong>Scenario 2: Función que requiere conexión</strong><br>
      Dado que el usuario intenta enviar una solicitud de ayuda sin conexión a internet, cuando el sistema detecta la falta de red, entonces muestra un aviso y encola la solicitud para enviarla en cuanto se recupere la conexión.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>91</td>
      <td><strong>Epic ID</strong></td>
      <td>17</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Configurar preferencias de notificaciones</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero configurar qué tipos de notificaciones push quiero recibir.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Configuración guardada</strong><br>
      Dado que el cuidador activa las notificaciones de "Solicitudes de ayuda" y desactiva las de "Consejos generales", cuando presiona "Guardar", entonces el sistema actualiza las preferencias de notificación push.<br><br>
      <strong>Scenario 2: Permisos del sistema operativo denegados</strong><br>
      Dado que el cuidador intenta activar notificaciones push pero el dispositivo las tiene bloqueadas a nivel de sistema, cuando el sistema detecta la restricción, entonces muestra instrucciones para habilitarlas desde la configuración del dispositivo.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>92</td>
      <td><strong>Epic ID</strong></td>
      <td>17</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Recibir alerta de episodio en curso</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero recibir una notificación cuando comienza un episodio para poder intervenir a tiempo.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Notificación entregada</strong><br>
      Dado que el usuario a cargo activa el Modo SOS, cuando el sistema procesa el evento, entonces envía una notificación push inmediata al cuidador vinculado.<br><br>
      <strong>Scenario 2: Notificaciones silenciadas temporalmente</strong><br>
      Dado que el cuidador tiene las notificaciones silenciadas en ese momento, cuando se activa un episodio, entonces el sistema respeta la configuración pero muestra la alerta dentro de la app al abrirla.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>93</td>
      <td><strong>Epic ID</strong></td>
      <td>17</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Recibir recordatorio de check-in</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero recibir un recordatorio periódico para revisar el estado del usuario si no ha habido actividad reciente.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Recordatorio enviado</strong><br>
      Dado que no se registra actividad en el perfil del usuario durante 3 días, cuando el sistema evalúa la inactividad, entonces envía una notificación sugiriendo revisar el estado del usuario.<br><br>
      <strong>Scenario 2: Actividad reciente detectada</strong><br>
      Dado que el usuario registró actividad en las últimas 24 horas, cuando el sistema evalúa la actividad, entonces no envía el recordatorio de check-in.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>94</td>
      <td><strong>Epic ID</strong></td>
      <td>17</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Recibir alerta de vencimiento de suscripción</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como usuario quiero recibir una alerta antes de que venza mi suscripción para renovarla a tiempo.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Alerta enviada</strong><br>
      Dado que la suscripción del usuario vence en 3 días, cuando el sistema evalúa la fecha de vencimiento, entonces envía una notificación recordando la fecha y ofreciendo renovar.<br><br>
      <strong>Scenario 2: Suscripción ya renovada</strong><br>
      Dado que el usuario ya renovó su suscripción antes del vencimiento, cuando el sistema evalúa el estado, entonces no envía la alerta de vencimiento.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>95</td>
      <td><strong>Epic ID</strong></td>
      <td>17</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Silenciar notificaciones temporalmente</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como cuidador quiero silenciar temporalmente las notificaciones no críticas para descansar sin perder alertas importantes.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Silencio activado</strong><br>
      Dado que el cuidador activa "No molestar" por 8 horas, cuando el sistema procesa la acción, entonces silencia notificaciones no críticas manteniendo activas las de solicitudes de ayuda y episodios.<br><br>
      <strong>Scenario 2: Fin del periodo de silencio</strong><br>
      Dado que transcurren las 8 horas configuradas, cuando el sistema evalúa el tiempo, entonces restaura automáticamente todas las notificaciones a su configuración habitual.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>96</td>
      <td><strong>Epic ID</strong></td>
      <td>18</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Autenticar y autorizar usuarios mediante JWT</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como equipo de desarrollo quiero implementar autenticación basada en JWT para proteger el acceso a los recursos de la API.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Autenticación exitosa</strong><br>
      Dado que un cliente envía credenciales válidas al endpoint de login, cuando el sistema valida las credenciales, entonces genera y retorna un token JWT con un tiempo de expiración definido.<br><br>
      <strong>Scenario 2: Token inválido o expirado</strong><br>
      Dado que un cliente envía una solicitud con un token JWT expirado, cuando el sistema valida el token, entonces retorna un error 401 y exige una nueva autenticación.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>97</td>
      <td><strong>Epic ID</strong></td>
      <td>18</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Exponer API RESTful de episodios y perfiles</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como equipo de desarrollo quiero exponer endpoints RESTful para la gestión de perfiles y episodios para que el frontend pueda consumirlos de forma consistente.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Solicitud exitosa</strong><br>
      Dado que el frontend envía una petición GET al endpoint de episodios con un token válido, cuando el sistema procesa la solicitud, entonces retorna la lista de episodios en formato JSON con código 200.<br><br>
      <strong>Scenario 2: Solicitud sin autorización</strong><br>
      Dado que el frontend envía una petición sin un token válido, cuando el sistema valida la autorización, entonces retorna un código 401 sin exponer datos del perfil.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>98</td>
      <td><strong>Epic ID</strong></td>
      <td>18</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Persistir datos mediante JPA por bounded context</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como equipo de desarrollo quiero persistir los datos de cada bounded context (perfiles, episodios, suscripciones) mediante JPA para mantener un modelo de datos consistente y desacoplado.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Persistencia exitosa</strong><br>
      Dado que el servicio de episodios recibe un nuevo registro válido, cuando el sistema procesa la operación, entonces persiste la entidad en su propio esquema sin afectar otros bounded contexts.<br><br>
      <strong>Scenario 2: Fallo de conexión a la base de datos</strong><br>
      Dado que el sistema intenta persistir un episodio y la base de datos no responde, cuando el sistema detecta el fallo, entonces retorna un error controlado y reintenta la operación según la política configurada.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>99</td>
      <td><strong>Epic ID</strong></td>
      <td>18</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Containerizar y desplegar la API mediante Docker y CI/CD</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como equipo de desarrollo quiero containerizar la API y automatizar su despliegue para reducir errores manuales y acelerar las entregas.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Despliegue exitoso</strong><br>
      Dado que se realiza un push a la rama principal con los tests pasando, cuando el pipeline de CI/CD se ejecuta, entonces construye la imagen Docker, ejecuta las pruebas y despliega automáticamente en el ambiente correspondiente.<br><br>
      <strong>Scenario 2: Fallo en las pruebas automatizadas</strong><br>
      Dado que se realiza un push con pruebas que fallan, cuando el pipeline de CI/CD se ejecuta, entonces detiene el despliegue y notifica al equipo el motivo del fallo.
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td><strong>User Story</strong></td>
      <td>100</td>
      <td><strong>Epic ID</strong></td>
      <td>18</td>
    </tr>
    <tr>
      <td><strong>Title</strong></td>
      <td colspan="3">Desplegar el frontend en hosting estático</td>
    </tr>
    <tr>
      <td><strong>Description</strong></td>
      <td colspan="3">Como equipo de desarrollo quiero desplegar el frontend en un servicio de hosting estático para garantizar disponibilidad y tiempos de carga rápidos.</td>
    </tr>
    <tr>
      <td><strong>Acceptance Criteria</strong></td>
      <td colspan="3">
      <strong>Scenario 1: Despliegue exitoso</strong><br>
      Dado que se genera un nuevo build del frontend tras una fusión a la rama principal, cuando el pipeline de despliegue se ejecuta, entonces publica la nueva versión en el hosting y queda accesible mediante la URL de producción.<br><br>
      <strong>Scenario 2: Error en el build del frontend</strong><br>
      Dado que el build del frontend falla por un error de compilación, cuando el pipeline de despliegue se ejecuta, entonces detiene el proceso y mantiene la versión anterior activa en producción.
      </td>
    </tr>
  </tbody>
</table>

---

## 3.2. Impact Mapping

## 3.3. Product Backlog