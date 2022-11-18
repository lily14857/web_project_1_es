# Welcome to the official repository of Aprender a aprender!!

Este proyecto ha sido creado con la finalidad de aprender a crear una página web desde 0 utilizando metodología BEM. Al mismo tiempo tiene el propósito de enseñar al usuario un método de aprendizaje eficiente y rápido enfocándose en adquirir nuevas habilidades y perfeccionar las ya obtenidas.

## Style guidelines

- CSS BEM

## Stack

- HTML
- CSS
  - [normalize](github.com/necolas/normalize.css)

## Project structure

- `blocks/` - contiene todos los estilos css por bloque (BEM)
- `animation/` - guarda los estilos de animaciones no relacionados a bloques
- `images/` - todas las imagenes contenidas del proyecto
- `pages/` - encontramos los estilos por pagina, solo estos estilos son cargados desde html, a su vez, cada archivo css debe cargar los bloques que necesita
- `styles/` - pendiente de refactorizar (\*)
- `vendor/` - aqui se guardan todos las librerias externas (no nuestras)
