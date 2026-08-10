# Laboratorio: Scrum, Kanban y Estimación

Laboratorio de planeación ágil aplicado al caso de estudio Bankify: desglose de trabajo en historias de usuario, construcción del backlog en Jira y estimación por puntos de historia con Planning Poker.

## Autores

BRAYAN LOAIZA LEAL (Desarrollador), JUAN ESTEBAN CRUZ RICO (Owner) y JUAN SEBASTIÁN GUAYAZÁN CLAVIJO (Scrum Master)
Desarrollo y Operaciones Software (ISIS DOSW-301)
Decanatura Ingeniería de Sistemas
Ingeniería de Sistemas
Escuela Colombiana de Ingeniería Julio Garavito
2026-1

## Estructura del proyecto

```
DOSW_Lab5_JuanE_JuanS_BrayanL/
├── pom.xml
├── src/
│   ├── main/java/edu/dosw/lab/App.java
│   └── test/java/edu/dosw/lab/AppTest.java
└── docs/
    ├── planning/
    │   ├── scrum_work_breakdown.md   # Desglose de trabajo (épica, historias, tareas)
    │   ├── jira.md                    # Backlog en Jira, capturas y cronograma
    │   └── img*.png                   # Evidencias
    ├── requirements/
    └── uml/
```

## Cómo ejecutar

```bash
mvn compile
mvn test
```

## Contexto y conceptos clave

### Resumen del laboratorio

Caso de estudio Bankify, una fintech que necesita una primera versión de su sistema de cuentas bancarias en 5 sprints (autenticación, gestión de clientes y cuentas, consulta de saldo, depósitos por PSE y reportes tributarios a la DIAN). A partir de ese caso, el equipo aplicó el ciclo de planeación ágil con Jira:

- **Desglose del trabajo** (`docs/planning/scrum_work_breakdown.md`): épica seleccionada, 4 historias de usuario con sus tareas, prioridad (Alto/Medio/Bajo) y justificación.
- **Product backlog en Jira** (`docs/planning/jira.md`): épica, historias de usuario y tareas creadas en Jira, con capturas de pantalla y el cronograma.
- **Estimación por puntos de historia (Planning Poker)**: votación en equipo de las 4 historias de usuario, con un video de la dinámica de estimación.
- **Planeación del primer sprint**: selección de historias de usuario para el sprint 1 y asignación de tareas por integrante.

### Conceptos clave

- Scrum: épicas, historias de usuario, backlog, sprints
- Estimación ágil: Planning Poker, puntos de historia
- Jira: gestión de backlog y cronograma
- Roles de equipo: Product Owner, Scrum Master, Desarrollador

### Resultados

Reflexión del equipo sobre la Parte 4 (Estimación por puntos de historia):

- **¿Cuál fue la mayor dificultad a la hora de estimar?** Ponerse de acuerdo en el número de puntos de historia de usuario.
- **¿Fue fácil llegar a un consenso?** En la mayoría de los casos sí.
- **¿Cómo resolvieron los escenarios donde las estimaciones no fueron cercanas?** Un diálogo entre quien dio la estimación menor y quien dio la mayor, explicando el porqué de cada puntaje, hasta llegar a un acuerdo.
