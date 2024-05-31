# Éxito de los juegos a través del tiempo

El dataset contiene información sobre videojuegos de tres regiones diferentes: Norte América (NA), Union Europea (UE) y Japón (JP). Los datos incluyen las reseñas de usuarios y expertos, los géneros, las plataformas (por ejemplo, Xbox o PlayStation) y los datos históricos sobre las ventas de juegos. La tarea es identificar si un juego tiene éxito o no para una posible campaña publicitaria para una tienda online que vende videojuegos.

Los datos se remontan al año 2016, además el dataset contiene una columna "rating" que almacena la clasificación ESRB de cada juego. El Entertainment Software Rating Board (la Junta de clasificación de software de entretenimiento) evalúa el contenido de un juego y asigna una clasificación de edad como Adolescente o Adulto.

Este proyecto integra varios conocimientos vistos en el bootcamp de TripleTen, esto involucara el uso de librearías como Pandas, Matplotlib, Seaborn, Numpy y scipy. Para el logro del análisis, el proyecto está dividido en 4 áreas: Preparación de los datos, análisis de los datos, creación de un perfil de usuario para cada región y prueba de hipótesis.

## Preparación de los datos
Se realizan tareas como:
* Reemplazar los nombres de las columnas (ponerlos en minúsculas).
* Convertir los datos en los tipos necesarios y describir el porqué se cambiaron en las columnas que se realizó dicho cambio.
* Describir la razón de como se eligió la manera de tratar los valores ausentes.
* Calcular las ventas totales (la suma de las ventas en todas las regiones) para cada juego y colocar estos valores en una columna separada.

## Análisis de los datos
* ¿Cuántos juegos fueron lanzados en diferentes años? ¿Son significativos los datos de cada período?
* Elegir las plataformas con las mayores ventas totales y se construyó una distribución basada en los datos de cada año. Se buscó a las plataformas que solían ser populares pero que ahora no tienen ventas. ¿Cuánto tardan generalmente las nuevas plataformas en aparecer y las antiguas en desaparecer?
* Determinar para qué período se deben tomar datos y trabajar sólo con esos datos relevantes.
* ¿Qué plataformas son líderes en ventas? ¿Cuáles crecen y cuáles se reducen?
* Se creó un diagrama de caja para las ventas globales de todos los juegos, desglosados por plataforma y se responden las preguntas ¿Son significativas las diferencias en las ventas? ¿Qué sucede con las ventas promedio en varias plataformas?
* ¿Las reseñas de usuarios y profesionales afectan las ventas de una plataforma popular?.
* Teniendo en cuenta las conclusiones se comparan las ventas de los mismos juegos en otras plataformas.
* ¿Qué se puede decir de los géneros más rentables? ¿Puedes generalizar acerca de los géneros con ventas altas y bajas?

## Perfil de usuario para cada región
* ¿Cuáles son las cinco plataformas principales? Se describen las variaciones en sus cuotas de mercado de una región a otra.
* Se explica porqué son las plataformas principales.
* Se investiga si las clasificaciones de ESRB afectan a las ventas en regiones individuales.

## Prueba de hipótesis
Se comprueban las siguientes hipótesis:
* Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son las mismas.

* Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.