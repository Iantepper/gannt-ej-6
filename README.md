# gannt-ej-6


```mermaid
gantt
    title Proyecto de Desarrollo
    dateFormat  YYYY-MM-DD
    section Análisis del Problema
     Análisis del problema               :task1, 2024-11-04, 2d
     Formulación de preguntas             :task2, after task1, 2d
     Realización de entrevista             :task3, after task2, 1d
     Análisis de la entrevista            :task4, after task1, after task3, 1d
     Creación y revisión del "Data Flow Diagram" :task5, after task4, 4d
     Diagrama de procedimiento             :task6, after task5, 2d
     Creación de Base de Datos            :task7, after task5, 2d
     Diseño básico de pantalla            :task8, after task6, 5d
     Creación manual del sistema          :task9, after task7, 5d
     Pruebas al sistema                   :task10, after task7, 3d
     Presentación a la gerencia           :task11, after task9, 1d
     Realización de cambios               :task12, after task10, 3d
     Presentación a los usuarios          :task13, after task9, after task12, 2d
     Informe de cambios solicitados       :task14, after task13, 1d
     Realización de cambios (si es necesario) :task15, after task14, 3d
     Creación manual usuario              :task16, after task15, 5d
     Adiestramiento a usuarios            :task17, after task16, 1d
