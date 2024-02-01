# Dataverse

## Índice

* [1. Introducción](#1-introducción)
<<<<<<< HEAD
* [2. Descripción del proyecto](#2-Descripción-del-proyecto)
* [3. Funcionalidades](#3-funcionalidades)
* [4. Historia de usuario](#4-Historia-de-usuario)
* [5.Tecnologías utilizadas](#5-Tecnologías-utilizadas)
* [6. Diseño y Desarrollo del Prototipo](#6-Diseño-y-Desarrollo-del-Prototipo)


## 1. Introducción
¡Bienvenido a WikiNook 🏡!</br>
Este proyecto es una aplicación web dedicada a los amantes del videojuego Animal Crossing, específicamente diseñada para explorar y conocer más sobre los adorables vecinos del juego. Con un diseño inspirado en la estética de Animal Crossing, WikiNook ofrece una experiencia interactiva para descubrir información detallada sobre cada vecino, clasificándolos según su especie, personalidad y género.

## 2. Descripción del proyecto
WikiNook tiene como objetivo proporcionar a los jugadores de Animal Crossing una plataforma intuitiva y atractiva para explorar información detallada sobre sus vecinos favoritos. Desde clasificar a los vecinos por personalidad y especie hasta la posibilidad de buscarlos por nombre, WikiNook es la guía perfecta para conocer a fondo la comunidad animal de tu isla.

![Imagen página completa gif](dataverse.gif)

## 3. Funcionalidades

* Exploración por Filtros: Filtra a los vecinos por personalidad, especie y género, esta sección cuenta con un botón de limpiado de dichos filtros y devuelve los datos a su estado inicial.
* Orden Alfabético: Explora la lista de vecinos de manera ascendente o descendente por orden alfabético a través de un selector.
* Barra de Búsqueda: Encuentra rápidamente a tu vecino favorito por su nombre, cuenta con un botón que limpia la búsqueda realizada.
* Estadísticas: Muestra porcentualmente en un modal la cantidad de vecinos del género femenino y del género masculino existentes en la plataforma. 

## 4. Historia de usuario

Se realizo un documento con las funcionalidades del proyecto, pedidas desde el punto de vista de un usuario, simulando una situación en la que podría ser usada. 
Aquí mostramos el enlace del documento realizada para el usuario que nos permite conocer los pasos en los que se desarrollo el proyecto.
[Enlace del documento](https://docs.google.com/document/d/1K8NoQyA83kZ_FGCIBDcJ6XyT0XXSpx40iVrrJk-1XwY/edit)

## 5. Tecnologías utilizadas
El desarrollo de WikiNook se benefició de un conjunto diverso de tecnologías y herramientas que permitieron una implementación robusta y una experiencia de usuario enriquecedora. 

### Prompt utilizado
Se utiliza chatGPT como IA requerida, este nos facilito la extración de información que requeriamos para mostrar la data de las tarjetas.

![chatGPT para generar la data](promptingImage.png)
![chatGPT para generar la data](chat.png)

### HTML
Utilizado para la estructura y marcado del contenido de la aplicación web.

### CSS
Se empleó CSS con la técnica de Flexbox para crear un diseño adaptable (responsive) y atractivo que se alinea con la estética de Animal Crossing.

### JavaScript
JavaScript fue esencial en WikiNook, no solo para la manipulación dinámica del DOM, sino también para implementar diversas funcionalidades clave. Desde la gestión de filtros hasta la interactividad con tarjetas de vecinos y la lógica de búsqueda, JavaScript proporcionó una base sólida para una experiencia de usuario fluida y receptiva. Su versatilidad se extendió más allá de la manipulación del DOM, abarcando diversas interacciones y dinámicas presentes en la aplicación.

### Testing
Se utilizó Jest para realizar pruebas unitarias, asegurando la integridad y funcionalidad correcta de las distintas partes del código. Las pruebas unitarias contribuyeron a mantener la calidad del código y facilitaron futuras actualizaciones y expansiones del proyecto.

## 6. Diseño y Desarrollo del Prototipo
El proceso de diseño y desarrollo del prototipo de WikiNook fue llevado a cabo con atención meticulosa, centrándonos en la experiencia del usuario y la estética inspirada en Animal Crossing. Utilizamos la plataforma de diseño colaborativo Figma para crear prototipos de media y alta fidelidad que sirvieron como guía visual y funcional antes de la implementación final.

### Prototipo fidelidad media 
=======
* [2. Descripción del proyecto](#2-Descripción-del-proeyecto)
* [3. Funcionalidades](#3-funcionalidades)
* [4. Historia de usuario](#4-Historia-de-usuario)
* [5.Tecnologías utilizadas](#5-Tecnologías-utilizadas)
* [6. Prototipo de alta y media fidelidad](#6-Prototipo-de-alta-y-media-fidelidad)
* [7. Objetivos de aprendizaje](#7-objetivos-de-aprendizaje)


## 1. Introducción
Bienvenido a data Dataverse, la página donde encontraras información de personajes del video juego animal crossin en forma de tarjetas.

## 2. Descripción del proyecto.
Dataverse es un proyecto para la diversión del público en general, es una página que tiene un estilo adaptable, para laptop, tablet y celular, en el que podras encontrar las tarjetas de tu personaje favorito, pero no solo eso, puedes hacer una búsqueda por nombre de tu personaje favorito, también puedes filtrar las tarjetas por orden, especie, etc.

<img src="paginaTerminada2.png" alt="dataverse1" width="400" height="250">
<img src="paginaTerminada3.png" alt="dataverse3" width="400" height="250">
<img src="dataverse.gif" alt="Gif dataverse" width="500" height="350">



## 3. Funcionalidades

* Cuenta con una barra de búsqueda y esta contiene un botón de limpiar.
* tiene un espacio que te permite filtrar por especie, personalidad y género.
* Tiene un botón que permite organizar las tarjetas en orden ascendente y descendente.
* Tiene un botón que te permite borrar todos los filtros antes seleccionados.
* Tiene un botón que te permite ver la estadistica encuanto a personajes por su género.

## 4. Historias de ususario

Se realizo un documento con las funcionalidades del proyecto, pedidas desde el punto de vista de un usuario, simulando una situación en la que podría ser usada. 
Aquí mostramos el enlace del documento realizada para el usuario que nos permite conocer los pasos en los que se desarrollo el proyecto.
[Enlace del documento](https://docs.google.com/document/d/1K8NoQyA83kZ_FGCIBDcJ6XyT0XXSpx40iVrrJk-1XwY/edit)


## 5. Tecnologías utilizadas

### Prompt utilizado
Se utiliza chatGPT como IA requerida, este nos facilito la extración de información que requeriamos para mostrar la data de las tarjetas.

![chatGPT para generar la data](chat1.png)
![chatGPT para generar la data](chat.png)

### `index.html`

Se uso index como página principal de la estructura del proyecto.

### `src/view.js`

En este archivo se relizaron interacciones con el HTML, creando la estructura de las tarjetas mostradas.

### `main.js, dataFunctions.js`

En el main se realiza el llamado del DOM que nos permite la interacción con los filtros mostrados en la página.
En cuanto al dataFunction es el apartado que se utilizo para realizar las tres funciones que nos permiten realizar la parte dinamica de la página.

### `data.js`

Aquí se puden encontrar los datos generados con ayuda de la IA.

### `dataFunctions.spec.js`

Aquí se realizaron test de prueba unitaria que nos ayudan con el buen funcionamiento de las tres funciones realizadas.

### `test/data.js`

Este archivo no ayuda en la prueba de los test realizados en el archivo dataFunction.spec.js.


## 6. Prototipo de alta y media fidelidad

>>>>>>> 80a2df238d431db9d9bd6354558f482e251797ad
Se diseñaron dos prototipos uno de media fidelidad que nos muestras las funcionalidades esperamos tuviera el proyecto.

<img src="prototipoMediaFidelidad.png" alt="Prototipo media fidelidad" width="500" height="350">

<<<<<<< HEAD
### Prototipo fidelidad alta
Encuanto al prototipo de alta fidelidad es la culminación del proyecto, en cuanto a interacción con el usuario, así como los acabados que debe tener la página y las tarjetas mostradas.

<img src="prototipoAltaFidelidad.png" alt="Prototipo alta fidelidad" width="500" height="350">

### Implementación
* Transición a Desarrollo.
* Adaptación a Tecnologías Seleccionadas. </br>
¡Tú también puedes echarle un vistazo a nuestro prototipo! clic aquí [Link al prototipo](https://www.figma.com/proto/lw0HfZvfVOoTsurPPYlpeL/Prototipo%2FDataverse?page-id=0%3A1&type=design&node-id=168-26302&viewport=928%2C-200%2C0.59&t=zLZEgt3rNaGcR8uG-1&scaling=contain&starting-point-node-id=36%3A103&mode=design)

#### Testeos de usabilidad

Se realizo una prueba de usabilidad con usuarios elegidos al azar para ayudarnos a generar información que nos fue de utilidad para el mejoramiento dinámico y visual de la página.
=======

Encuanto al prototipo de alta fidelidad es la culminación del proyecto, en cuanto a interacción con el usuario, así como los acabados quedebe tener la página y las tarjetas mostradas.
<img src="prototipoAltaFidelidad.png" alt="Prototipo alta fidelidad" width="500" height="350">

#### Testeos de usabilidad

Se realizo una prueba de usabilidad con usarios elegidos al azar para ayudarnos a generar información que nos fue de utilidad para el mejoramiento dinámico y visual de la página.
>>>>>>> 80a2df238d431db9d9bd6354558f482e251797ad

[Enlace del documento](https://docs.google.com/document/d/1moavw2dL9eJssKzZC8Xq0elcS4KpEhgRxF3GcTFZ-sI/edit#heading=h.icq4iwform4o)
  