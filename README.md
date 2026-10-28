# Pronosticar el éxito en la NFL

Proyecto del curso "Programar con criterio en la era de la IA".
Pregunta: ¿qué características de un jugador, conocidas en el draft,
permiten pronosticar su éxito profesional?

Autor/a: Ximena González Pérez

## Datos
- Archivo: nfl_data.csv del repositorio phcs971/nfl-draft-dataset
  (licencia MIT), leído desde una URL fijada a la versión 54730ea.
- Contenido: 14,163 filas y 59 columnas. Cada fila es un jugador que participó en el proceso del draft de la NFL. Trae sus datos físicos, los resultados de las pruebas del Combine, estadísticas universitarias, su posición y su lugar del draf
- Base de análisis: 3,197 jugadores elegidos en el draft entre 2000 y 2014,

## Variables principales
- Éxito observado: career_av, la suma del valor aproximado que aporta cada jugador. pro_bowl, este vale TRUE, si el jugador fue alguna vez al Pro bowl.
- Predictores: simple_pos (posición), draft_pick (lugar en el que fue elegido), draft_round (ronda en la que el jugador fue elegido), forty, vert_leap, broad_jump, bench_press (estas 5 son las pruebas del Combine) y tambien se encuentran estadisticas universitarias.

## Decisiones de limpieza
1. [decisión y razón]
2. ...

## Carpetas
- sesion-1/ a sesion-5/: trabajos de cada sesión
