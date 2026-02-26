**📋 Cosas raras e inesperadas**
---
Como mencionamos en varias ocasiones a lo largo del proyecto, lo que más nos hizo pensar en diferentes hipótesis y lo que más raro se nos hacía era que el dataset solo hiciese referencia a un préstamo diario. Después de analizar más a fondo también fueron surgiendo las siguientes rarezas y cosas inesperadas:

- Los libros de las categorías poesía, divulgación y ensayo son los que tardan más en devolver. Hemos de pensar que se debe a la densidad de su contenido. Por otro lado que los cómics y los libros infantiles tengan las devoluciones más tempranas confirma la hipótesis ya que sus lecturas son ligeras y poco complicadas aunque llama la atención que la novela gráfica siendo una lectura equiparable al cómic tenga una devolución de casi el triple de tiempo. ¿Se debe a un fallo?

- Más del doble de los usuarios de la biblioteca hacen uso del servicio por las tardes imaginamos que debido a los estudios o el trabajo. Los usuarios por la mañana pueden ser jubilados, parados, trabajadores con turno de tarde etc.. pero, ¿una biblioteca que abre los domingos? Además formando parte de uno de los días con más afluencia y donde más se concentran los préstamos que es en la tarde de este mismo día. 


- Nos llamó la atención el "triunfo" del catalán por encima del inglés.

- Y por último, que por el patrón que vemos temporal reducen a servicios mínimos pero no dejan de abrir en agosto y lo que es más sorprendente, también los domingos, esto se mantiene todo el año. 


**👤Bitácora personal**
---
PRIMERAS OBSERVACIONES:

Lo primero que observo en los datos aportados es que son demasiado pocos y no muy especificos. Que habra que con la ayuda de google sheet crear nuevas tablas para obtener datos mas especificos y asi pasar al siguiente punto del analisis. Una vez mejoradas las tablas y tener nuevos datos, tanto mis compañeros como yo empezamos a ver datos que nos llaman la atencion.

---CUESTIONES:

- ¿Porque hay un solo dato diario los dias de prestamo? 
- ¿Porque ninguna mañana de los lunes hay existencia de datos?
- ¿Cual es el motivo de las cantidades obtenidas de prestamos de libros en catalán?
- ¿Motivo de la bajada de prestamos a partir del mes de mayo y el porque de los domingos tiene el mayor indice de prestamos?

---ANALISIS E HIPOTESIS:

- Se baraja la posibilidad de que se trate de un unico prestamo diaro, barajando la posibilidad de que se trate de un registro personal.
- Otra hipotesis es si los lunes de mañanas la biblioteca descansa.
- Tambien se baraja la posibilidad de que tal biblioteca este ubicada en Cataluña, por el alto prestamo de libros en ese idioma
- Y que al comenzar el verano, puede que los clientes esten de vacaciones u otras razones.git 

**📌Conclusión final**
---

Conclusiones:

El dataset nos muestra 261 registros de préstamos entre el 3 de enero y el 30 de diciembre de 2025. Observamos que los registros son más altos los cinco primeros meses, de enero a mayo, aquí tenemos el 56,7% del total de registros, con una media de 29,6 préstamos mensuales, frente a los 16 préstamos de media del resto del año. Agosto es el mes con menos datos registrados, solo 13.
Ficción es la categoría con más préstamos, 103 préstamos (39.5% del total), seguida de infantil (21,1%), cómic (13,4%) y ensayo (13,0%). Poesía es la categoría menos registrada, con solo 3 préstamos en todo el año.  
La duración de los préstamos varía según la categoría: el cómic es el único con un plazo fijo de devolución de 7 días en el 100% de sus préstamos. La categoría infantil tiene una media de 10,5 días, mientras que poesía y divulgación superan los 25 días de media, siendo las categorías de mayor duración de préstamo.
El ratio de devolución fuera de plazo es del 5,7% (15 préstamos sobre 261). Estos datos de fuera de plazo se concentran en las categorías de plazo más largo: poesía tiene la tasa más alta (66,7%), seguida de divulgación (28,6%) y ensayo (8,8%). Por el contrario, infantil, cómic y novela gráfica registran un 0% de devoluciones en fuera de plazo durante todo el período del dataset. Los libros en inglés presentan la tasa de mora más elevada por idioma (13,0%), frente al 5,3% del español y el 3,4% del catalán. La duración media de los préstamos con mora es de 23,9 días, frente a los 14,3 días de los devueltos a tiempo.
El español es el idioma con más préstamos registrados,  el 80,1% de los préstamos, seguido del catalán con el 11,1% e inglés con el 8,8%. Esta distribución refleja el perfil lingüístico de la comunidad local y la importancia de mantener un fondo diverso en múltiples idiomas.
Respecto al uso horario y temporal, la franja de tarde concentra el 66,3% de los préstamos, aunque la franja de mañana presenta una tasa de devolución tardía ligeramente superior (8,0% frente al 4,6%). Los días de mayor actividad de registros son martes y domingo, con 52 préstamos cada uno, mientras que lunes y sábado son los menos activos, con 21 registros cada uno. En cuanto a la mora mensual, Enero y Marzo presentan las incidencias más altas (10,7% y 9,7% respectivamente), siendo Junio y Octubre los únicos meses sin ningún retraso registrado.
