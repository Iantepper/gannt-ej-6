# gantt-ej-6
Project Manager (PM): $400,000 (fijo)
Analistas de Sistemas (2): $2,800/hora cada uno
DBA (1): $5,050/hora
Programadores (4): $3,000/hora cada uno
Analista Jr. (1): $2,070/hora + $500 viáticos por día
trabajo de 8 horas por día
Cálculo de Costos por Tarea
| Tarea | Descripción                                   | Días | Horas/Día | Cantidad | Tarifa      | Costo Total |
|-------|-----------------------------------------------|------|-----------|----------|-------------|-------------|
| A     | Análisis del problema                         | 2    | 8         | 2 analistas | $2,800     | $89,600     |
| B     | Formulación de preguntas para entrevista      | 2    | 8         | 1 analista | $2,800      | $44,800     |
| C     | Realización de entrevista a la administración | 1    | 8         | 1 analista | $2,800      | $22,400     |
| D     | Análisis de la entrevista (necesidades)       | 1    | 8         | 1 PM       | $400,000 fijo | $400,000  |
| E     | Creación y revisión del "Data Flow Diagram"   | 4    | 8         | 1 analista | $2,800      | $89,600     |
| F     | Diagrama de procedimiento                     | 2    | 8         | 1 analista Jr. + viáticos | $2,070 + $500 | $16,920 |
| G     | Creación de Base de Datos                     | 2    | 8         | 1 DBA      | $5,050      | $80,800     |
| H     | Diseño básico de pantalla de usuarios         | 5    | 8         | 1 programador | $3,000   | $120,000    |
| I     | Creación manual del sistema                   | 5    | 8         | 1 programador | $3,000   | $120,000    |
| J     | Pruebas al sistema                            | 3    | 8         | 1 analista Jr. + viáticos | $2,070 + $500 | $10,720 |
| K     | Presentación a la gerencia                    | 1    | 8         | 1 analista | $2,800      | $22,400     |
| L     | Realización de cambios (si es necesario)      | 3    | 8         | 1 programador | $3,000   | $72,000     |
| M     | Presentación a los usuarios                   | 2    | 8         | 1 analista Jr. + viáticos | $2,070 + $500 | $10,720 |
| N     | Informe de cambios solicitados                | 1    | 8         | 1 analista Jr. + viáticos | $2,070 + $500 | $10,720 |
| O     | Realización de cambios (si es necesario)      | 3    | 8         | 1 programador | $3,000   | $72,000     |
| P     | Creación manual de usuario                    | 5    | 8         | 1 programador | $3,000   | $120,000    |
| Q     | Adiestramiento a usuarios y gerencia          | 1    | 8         | 1 analista | $2,800      | $22,400     |

| Tarea | Recursos Asignados | Horas Totales | Costo ($) |
|-------|---------------------|---------------|-----------|
| A     | 2 Analistas        | 32            | 89,600    |
| B     | 1 Analista         | 16            | 44,800    |
| C     | 1 Analista         | 8             | 22,400    |
| D     | 1 PM               | 8             | 400,000   |
| E     | 1 Analista         | 32            | 89,600    |
| F     | 1 Analista Jr.     | 16            | 16,920    |
| G     | 1 DBA              | 16            | 80,800    |
| H     | 1 Programador      | 40            | 120,000   |
| I     | 1 Programador      | 40            | 120,000   |
| J     | 1 Analista Jr.     | 24            | 10,720    |
| K     | 1 Analista         | 8             | 22,400    |
| L     | 1 Programador      | 24            | 72,000    |
| M     | 1 Analista Jr.     | 16            | 10,720    |
| N     | 1 Analista Jr.     | 8             | 10,720    |
| O     | 1 Programador      | 24            | 72,000    |
| P     | 1 Programador      | 40            | 120,000   |
| Q     | 1 Analista         | 8             | 22,400    |


| Tarea | Nombre                                     | Duración | Fecha de Inicio | Fecha de Fin | Predecesores | Recurso Asignado          |
|-------|--------------------------------------------|----------|-----------------|--------------|--------------|---------------------------|
| A     | Análisis del problema                      | 2 días   | 04/11/24        | 05/11/24     |              | Analista de sistemas 1    |
| B     | Formulación de preguntas para entrevista   | 2 días   | 04/11/24        | 05/11/24     |              | Analista de sistemas 2    |
| C     | Realización de entrevista a la administración | 1 día | 06/11/24        | 06/11/24     | B            | Analista de sistemas 1    |
| D     | Análisis de la entrevista (análisis necesidades) | 1 día | 07/11/24        | 07/11/24     | A, C         | Project Manager (PM)      |
| E     | Creación y revisión del "Data Flow Diagram" | 4 días  | 08/11/24        | 13/11/24     | D            | Analista de sistemas 2    |
| F     | Diagrama de procedimiento                  | 2 días   | 14/11/24        | 15/11/24     | E            | Analista Jr. + Viáticos   |
| G     | Creación de Base de Datos                  | 2 días   | 14/11/24        | 15/11/24     | E            | DBA                       |
| H     | Diseño básico de pantalla de usuarios      | 5 días   | 18/11/24        | 22/11/24     | G            | Programador 1             |
| I     | Creación manual del sistema                | 5 días   | 25/11/24        | 29/11/24     | F, H         | Programador 3             |
| J     | Pruebas al sistema                         | 3 días   | 25/11/24        | 27/11/24     | F, H         | Analista Jr. + Viáticos   |
| K     | Presentación a la gerencia, aceptación de cambios | 1 día | 28/11/24 | 28/11/24 | J            | Analista de sistemas 1    |
| L     | Realización de cambios (si es necesario)   | 3 días   | 29/11/24        | 03/12/24     | K            | Programador 2             |
| M     | Presentación a los usuarios, aceptación cambios | 2 días | 04/12/24 | 05/12/24 | I, L         | Analista Jr. + Viáticos   |
| N     | Informe de cambios solicitados a la gerencia | 1 día   | 06/12/24        | 06/12/24     | M            | Analista Jr. + Viáticos   |
| O     | Realización de cambios (si es necesario)   | 3 días   | 09/12/24        | 11/12/24     | N            | Programador 4             |
| P     | Creación manual de usuario                 | 5 días   | 12/12/24        | 18/12/24     | O            | Programador 1             |
| Q     | Adiestramiento a usuarios y gerencia       | 1 día    | 19/12/24        | 19/12/24     | P            | Analista de sistemas 2    |




```mermaid
gantt
    title Proyecto de Desarrollo
    dateFormat  YYYY-MM-DD
    section Análisis del Problema
    A. Análisis del problema               :task1, 2024-11-04, 2d
    B. Formulación de preguntas             :task2, after task1, 2d
    C. Realización de entrevista             :task3, after task2, 1d
    D. Análisis de la entrevista            :task4, after task3, 1d
    E. Creación y revisión del "Data Flow Diagram" :task5, after task4, 4d
    F. Diagrama de procedimiento             :task6, after task5, 2d
    G. Creación de Base de Datos            :task7, after task5, 2d
    H. Diseño básico de pantalla            :task8, after task6, 5d
    I. Creación manual del sistema          :task9, after task7, 5d
    J. Pruebas al sistema                   :task10, after task7, 3d
    K. Presentación a la gerencia           :task11, after task9, 1d
    L. Realización de cambios               :task12, after task10, 3d
    M. Presentación a los usuarios          :task13, after task12, 2d
    N. Informe de cambios solicitados       :task14, after task13, 1d
    O. Realización de cambios (si es necesario) :task15, after task14, 3d
    P. Creación manual usuario              :task16, after task15, 5d
    Q. Adiestramiento a usuarios            :task17, after task16, 1d

