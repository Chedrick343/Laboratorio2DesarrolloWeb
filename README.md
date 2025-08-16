# Evento super-tecnológico
## Descripción
El sitio web que se ha desarrollado es para un evento tecnológico que está desarrollando 
el Tecnológico de Costa Rica en el centro académico de limón con el fin de atraer nuevos
estudiantes al CAL.
Se nos pidió un sitio web sencillo, desarrollado en HTML puro, pero con una semántica
impecable para eventualmente agregarle mejoras visuales con CSS.
## Estructura semántica
Para desarrollar esta pagina web utilizamos elementos como:
- a: Que nos ayudó a mostrar enlaces tanto externos como internos
- section: Muy util para dividir la página web en varias secciones
- ul y ol: listas para premios y para patrocinadores
- form: para el formulario de inscripción

## URL de Netlify

Para poder ver el sitio web desarrollado visita [Evento super-tecnológico](https://merry-torte-bcddc7.netlify.app/) soportado 
por [Netlify](https://app.netlify.com/)

## Validación W3C
Pese a realizar cautelosamente el sitio web, aún hay margen de mejora a nivel de escritura del lenguaje
de etiquetado. Como veremos en las siguientes imágenes la gran mayoría de errores lanzados son por
espacios dejados en los id's y en imagenes.
![imagen de errores 1](Errores%201.png) 
![imagen de errores 2](Errores%202.png)

## Lighthouse
A continuación mostramos la puntuación general de Lighthouse.
![Puntuacion Lighthouse](General%20Light.png)

Tenemos también la puntuación a nivel de accesibilidad.
![puntuacion accesibilidad](accesibilidad%20light.png)

Y además la puntuación de SEO 
![Puntuación de SEO](SEO%20light.png)

Con la experiencia que hemos recolectado desarrollando este pequeño proyecto web sabemos
que estas cifras nos son favorables, podemos implementar las mejoras rápida y facilmente, ya que no son faltas tan graves.
Para proyectos venidores las correcciones que nos señala el programa serán implementados sin lugar a dudas.

## Accesibilidad aplicada
Como vimos anteriormente las puntuaciones no son del todo malas pero sí hay margen de mejora, sin embargo, podemos 
resaltar algunas de las herramientas que usamos y por qué.
tabindex fue utilizado en imágenes y en la agenda, creemos que las imágenes son bastante descriptivas y 
llaman la atención, además la agenda es algo a lo que si alguien necesita consultar debería de 
poder hacerlo lo más rápido posible. Aunque las imágenes son bastantes descriptivas, 
usamos aria-label para dar una descripción detallada de lo que se mira en las imágenes.
Sabemos que hay muchas más herramientas para implementar aún más accesibilidad y estas
serán agregadas en siguientes versiones del programa. 