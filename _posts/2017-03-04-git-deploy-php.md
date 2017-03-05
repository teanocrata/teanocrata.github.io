---
layout: post
title: git-deploy (fork)- php-based tool that deploys and keeps updated git repository to FTP/SFTP server
category: projects
tags: php git TravisCI
image: /images/git-deploy-php.png
link: https://github.com/teanocrata/git-deploy-php
---

Fork del proyecto [Git-deploy-php](http://brunodebarros.github.io/git-deploy-php/) de [BrunoDeBarros](https://github.com/BrunoDeBarros) adaptado para poder desplegar carpetas del repositorio y no el repositorio completo e integrado con [TravisCI](https://travis-ci.org/) para poder hacer el despliegue automático.

## Código

Todo el código del proyecto está disponible en [el repositorio de Github teanocrata/git-deploy-php](https://github.com/teanocrata/git-deploy-php)

## Objetivo

La primera versión de [Open Smart Country](https://opensmartcountry.com/) empezó en wordpress desarrollando en php toda la funcionalidad. Estaba alojado utilizando un proveedor de hosting de worpress y para poder automatizar los despliegues utilicé esta herramienta desarrollada por [Bruno De Barros](https://github.com/BrunoDeBarros). No se adaptaba del todo ya que hacia falta alguna cosilla para poder desplegar con TravisCI. Además por la estructura de carpetas con la que trabajaba no acababa de funcionar bien. Por esto modifiqué ligeramente el código.

Es muy sencillo, utiliza comandos de git para saber qué ha cambiado y eso es lo que despliega, deja unos archivos en el servidor para poder saber qué es lo último que se desplegó y porder hacer rollback en caso necesario. Muy recomendable ver cómo se hace algo así para entender bien un despliegue con herramientas estándar.

## Utilizando

* [php](https://secure.php.net/)
* [TravisCI](https://travis-ci.org/)
* [GIT](https://git-scm.com/)
