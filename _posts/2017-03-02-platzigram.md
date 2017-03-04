---
layout: post
title: platzigram - Front-end JavaScript
category: projects
tags: HTML css JavaScript NodeJS
image: /images/platzigram.png
link: https://teanocrata.github.io/platzigram/
---

Proyecto para aprender Javascript para Front-end

## Código

Todo el código del proyecto está disponible en [el repositorio de Github teanocrata/platzigram](https://github.com/teanocrata/platzigram)

## Objetivo

Intentaremos crear el Front-end de Instagram utilizando HTML, CSS y Javascript.

El desarrollo está realizado siguiendo la primera parte el ["Curso Definitivo de JavaScript"](https://platzi.com/clases/javascript/). En particular la parte que da [Sacha Lifszyc](https://twitter.com/slifszyc).

Utilizamos Sass, Browserify, Gulp, Babel.js, npm, Node.js.

FormatJS para manejar multiples idiomas.

Las fotos se subirán a Amazon S3.

## Herramientas

* [NodeJS](https://nodejs.org) para desarrollar
* [npm](https://www.npmjs.com/) como gestor de paquetes
* [materializecss](http://materializecss.com/) como framework ligero basado en material design
* [express](http://expressjs.com/) como servidor web
* [browserify](http://browserify.org/)  como ensamblador de paquetes
* [gulp](http://gulpjs.com/) para automatizar las tareas
* [Sass](http://sass-lang.com/) como preprocesador de css
* [Babel](https://babeljs.io/) como compilador para usar las ultimas funcionalidades de JavaScript
* [vinyl-source-stream](https://www.npmjs.com/package/vinyl-source-stream) para poder procesar lo que genera el bundle
* [page](https://github.com/visionmedia/page.js) para cargar solo lo que cambia en la página
* [watchify](https://github.com/substack/watchify) Para recargar automáticamente los cambios
* [concurrently](https://www.npmjs.com/package/concurrently) Para ejecutar el watch y el server a la vez
* [yo-yo](https://www.npmjs.com/package/yo-yo) Sigue la filosofía de react, para enriquecer el lado del cliente
* [empty-element](https://www.npmjs.com/package/empty-element) Para vaciar elementos
* [title](https://www.npmjs.com/package/title) Para gestionar los títulos de las páginas
* [format-js](https://formatjs.io/) Para traducir los textos
* [superagent](https://github.com/visionmedia/superagent) Lo probamos para usar callbacks en las peticiones a servidor
* [axios](https://github.com/mzabriskie/axios) Para hacer request pero con promesas
* [Fetch polyfill](https://github.com/github/fetch) Fetch no está soportado por todos los navegadores, usamos este polyfill
* [Async/await de EcmaScript 2016]() Tiene pinta de que este será el standard para las llamadas a servidor
* [multer](https://www.npmjs.com/package/multer) Para subir archivos al servidor
