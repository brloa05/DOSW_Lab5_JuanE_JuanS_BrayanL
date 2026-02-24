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

| Campo | Descripción |
|------|-------------|
| **ID** | HU-01 |
| **Título** | Inicio de sesión en el sistema |
| **Descripción** | *Como [Cliente] quiero [ingresar mi usuario y contraseña] para [usar el sistema segun mis funciones de forma adecuada]* |
| **Prioridad** | *[Alta] [Media] [Baja]* |
| **Estimación** | *Puntos de historia* |

| Campo | Descripción |
|------|-------------|
| **ID** | HU-02 |
| **Título** | Control de acceso por roles |
| **Descripción** | *Como [Cliente] quiero [que el sistema me muestre únicamente las funcionalidades permitidas según mi rol] para [beneficio u objetivo]* |
| **Prioridad** | *[Alta] [Media] [Baja]* |
| **Estimación** | *Puntos de historia* |

| Campo | Descripción |
|------|-------------|
| **ID** | HU-03 |
| **Título** |Protección de contraseñas|
| **Descripción** | *Como [Supervisor] quiero [necesidad o acción] para [garantizar la seguridad de la información de los usuarios]* |
| **Prioridad** | *[Alta] [Media] [Baja]* |
| **Estimación** | *Puntos de historia* |

| Campo | Descripción |
|------|-------------|
| **ID** | HU-04 |
| **Título** | Cierre de sesión |
| **Descripción** | *Como [usuario] quiero [cerrar sesión en la plataforma] para [proteger el acceso a mi información]* |
| **Prioridad** | *[Alta] [Media] [Baja]* |
| **Estimación** | *Puntos de historia* |

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
| **Descripción** | Como [Cliente] quiero [que mis credenciales sean validadas] para [acceder de forma segura a la plataforma] |
| **Tareas requisito** | TR-01 |

| Campo | Descripción |
|------|-------------|
| **ID** | TR-03 |
| **Título** | Gestión de sesión |
| **ID de la Historia de Uso asociada** | HU-01 |
| **Descripción** | Como [Cliente] quiero [que mi sesión permanezca activa mientras uso el sistema] para [evitar iniciar sesión repetidamente] |
| **Tareas requisito** | TR-02 |
