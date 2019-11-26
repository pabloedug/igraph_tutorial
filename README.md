# Resumen

Este repositorio incluye un conjunto de ficheros .Rmd con introducción a conceptos y funciones básicas del Análisis de Redes Sociales mediante igraph.

Los ficheros son los siguientes:

- **Igraph_objetografo.Rmd**: cómo generar una red en igraph (lo que da lugar al objeto de R *igraph*), así como obtener algunas de sus propiedades básicas.
- **Igraph_centralidad.Rmd**: cómo calcular las tres  medidas clásicas de centralidad (grado, intermediación y cercanía), así como entender sus diferencias.
- **Igraph_red.Rmd**: Cómo calcular métricas de red y entender su aplicación.


# Uso

Cada fichero .Rmd es un tutorial autocontenido, en que se combinan explicaciones, ejercicios en R y breves cuestiones de elección forzosa. Se trata de ficheros RMarkdown, con salida learnr::tutorial. Para ejecutarlos, hacer click en el botón *Run Document* de RStudio, o bien desde consola ejecutar la función *rmarkdown::run()*
Se trata de aplicaciones Shiny (con interfaz RMarkdown), de manera que existe una sesión de R ejecutándose en tanto el usuario interactúa con el tutorial.