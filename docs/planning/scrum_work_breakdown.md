# 📄 Planeación del Sistema

## Desglose de trabajo: Épicas, Historias de Usuario y Tareas

La implementación de los requerimientos identificados de Bankify se desglosa de la siguiente manera:

### 1. Épica:

| Campo | Descripción |
|------|-------------|
| **ID** | EP-01 |
| **Título** | Autenticación de usuarios |
| **Descripción** | *Explique el por qué Bankify necesita esta épica* |
| **Stakeholder** | *¿Quién es el stakeholder interesado en que se implemente esta épica?* |

### 2. Historias de usuario:

| Campo | Descripción                                                                                                            |
|------|------------------------------------------------------------------------------------------------------------------------|
| **ID** | HU-01                                                                                                                  |
| **Título** | Inicio de sesión en el sistema                                                                                         |
| **Descripción** | *Como [Cliente] quiero [ingresar mi usuario y contraseña] para [usar el sistema segun mis funciones de forma adecuada]* |
| **Prioridad** | Alta                                                                                                                   |                                                                                                                  |
| **Estimación** | *8 puntos*                                                                                                             |


https://github.com/user-attachments/assets/0cd33d7a-3dc0-4851-b394-f5046743c382



Justificación
Es un habilitador crítico. Sin autenticación no es posible acceder a módulos como gestión de cuentas, depósitos o reportes. El sistema no puede operar sin esta funcionalidad.

| Campo | Descripción                                                                                                                            |
|------|----------------------------------------------------------------------------------------------------------------------------------------|
| **ID** | HU-02                                                                                                                                  |
| **Título** | Control de acceso por roles                                                                                                            |
| **Descripción** | *Como [Cliente] quiero [que el sistema me muestre únicamente las funcionalidades permitidas según mi rol] para [beneficio u objetivo]* |
| **Prioridad** | Alta                                                                                                                                   |
| **Estimación** | *13 puntos*                                                                                                                            |

Justificación:

El sistema maneja diferentes actores (cliente, asesor, supervisor, gerente financiero). Sin control por roles se romperían reglas del negocio y se comprometería la seguridad de la información.

| Campo | Descripción                                                                                                     |
|------|-----------------------------------------------------------------------------------------------------------------|
| **ID** | HU-03                                                                                                           |
| **Título** | Protección de contraseñas                                                                                       |
| **Descripción** | *Como [Supervisor] quiero [necesidad o acción] para [garantizar la seguridad de la información de los usuarios]* |
| **Prioridad** | Alta                                                                                                            |
| **Estimación** | *13 puntos*                                                                                                     |

Justificación
Bankify es una fintech. La seguridad no es opcional. El almacenamiento seguro de contraseñas es indispensable para evitar riesgos legales y reputacionales en la validación del modelo de negocio.



| Campo | Descripción                                                                                         |
|------|-----------------------------------------------------------------------------------------------------|
| **ID** | HU-04                                                                                               |
| **Título** | Cierre de sesión                                                                                    |
| **Descripción** | *Como [usuario] quiero [cerrar sesión en la plataforma] para [proteger el acceso a mi información]* |
| **Prioridad** | Alta                                                                                                |
| **Estimación** | *5 puntos*                                                                                          |

Justificación:
Aumenta la seguridad y experiencia del usuario, pero no bloquea la validación inicial del modelo de negocio. Puede desarrollarse después de garantizar autenticación y control por roles.

### 3. Tareas:

| Campo | Descripción |
|------|-------------|
| **ID** | TR-01 |
| **Título** | Diseño de interfaz de inicio de sesión |
| **ID de la Historia de Uso asociada** | HU-01 |
| **Descripción** | *Como [Cliente] quiero [visualizar un formulario de inicio de sesión] para [ingresar mis credenciales]* |
| **Tareas requisito** | - |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-02 |
| **Título** | Validación de credenciales |
| **ID de la Historia de Uso asociada** | HU-01 |
| **Descripción** | *Como [Cliente] quiero [que mis credenciales sean validadas] para [acceder de forma segura a la plataforma]* |
| **Tareas requisito** | TR-01 |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-03 |
| **Título** | Gestión de sesión |
| **ID de la Historia de Uso asociada** | HU-01 |
| **Descripción** | *Como [Cliente] quiero [que mi sesión permanezca activa mientras uso el sistema] para [evitar iniciar sesión repetidamente]* |
| **Tareas requisito** | TR-02 |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-04 |
| **Título** | Definición de roles y permisos |
| **ID de la Historia de Uso asociada** | HU-02 |
| **Descripción** | *Como [Supervisor] quiero [definir los permisos de cada rol] para c[ontrolar el acceso a las funcionalidades]* |
| **Tareas requisito** | — |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-05 |
| **Título** | Asignación de roles a usuarios |
| **ID de la Historia de Uso asociada** | HU-02 |
| **Descripción** | *Como [Supervisor] quiero [asignar roles a los usuarios] para [que accedan solo a las funciones autorizadas]* |
| **Tareas requisito** | TR-04 |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-06 |
| **Título** | Visualización de módulos según rol |
| **ID de la Historia de Uso asociada** | HU-02 |
| **Descripción** | *Como [Cliente] quiero [visualizar únicamente los módulos permitidos según mi rol] para [evitar accesos no autorizados]* |
| **Tareas requisito** | TR-05 |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-07 |
| **Título** | Encriptación de contraseñas |
| **ID de la Historia de Uso asociada** | HU-03 |
| **Descripción** | *Como [Supervisor] quiero [que las contraseñas se almacenen de forma encriptada] para [proteger la información de los usuarios]* |
| **Tareas requisito** | — |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-08 |
| **Título** | Definición de políticas de contraseña |
| **ID de la Historia de Uso asociada** | HU-03 |
| **Descripción** | *Como [Supervisor] quiero [establecer reglas de complejidad para las contraseñas] para [aumentar la seguridad del acceso]* |
| **Tareas requisito** | — |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-09 |
| **Título** | Cambio seguro de contraseña |
| **ID de la Historia de Uso asociada** | HU-03 |
| **Descripción** | *Como [Cliente] quiero [cambiar mi contraseña] para [proteger mi cuenta]* |
| **Tareas requisito** | TR-08 |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-10 |
| **Título** | Opción visible para cerrar sesión |
| **ID de la Historia de Uso asociada** | HU-04 |
| **Descripción** | *Como [Cliente] quiero [visualizar la opción de cerrar sesión] para [salir del sistema fácilmente]* |
| **Tareas requisito** | — |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-11 |
| **Título** | Finalización de la sesión activa |
| **ID de la Historia de Uso asociada** | HU-04 |
| **Descripción** | *Como [Cliente] quiero [que mi sesión se cierre completamente] para [evitar accesos no autorizados]* |
| **Tareas requisito** | TR-10 |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-12 |
| **Título** | Redirección a pantalla de inicio de sesión |
| **ID de la Historia de Uso asociada** | HU-04 |
| **Descripción** | *Como [Cliente] quiero [ser redirigido a la pantalla de inicio de sesión al cerrar la sesión] para [confirmar que salí correctamente]* |
| **Tareas requisito** | TR-11 |
