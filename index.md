---
title: Despliegue
layout: home
nav_order: 1
description: "Documentación de Despliegue de Aplicaciones Web."
---


# Bienvenidos a Despliegue de Aplicaciones Web

Aquí encontrarás la documentación necesaria para el curso de Despliegue de Aplicaciones Web.

## Introducción

El contenido de esta sección es el que se proporciona durante el curso de 2º año de DAW, en el que se tratan temas como SSH, servidores web y DNS

## Sección 1: SSH

Documentación sobre SSH
[Conexion remota y SSH] (https://www.lunium.com/blog/conexion-remota-ssh-y-configuracion-de-sshconfig-/ "documentación orientativa")

## Sección 2: Herramientas de despliegue de aplicaciones web

Discusión sobre diferentes estrategias de despliegue y sus ventajas.

[Introducción a Docker para desarrolladores] (https://fjrnopzzm23qttuzha7zra.on.drv.tw/AA_Cursos/Curso%20Docker/1_Introduccion/ "Curso de Docker")

[Ejecutando y gestionando contenedores] (https://fjrnopzzm23qttuzha7zra.on.drv.tw/AA_Cursos/Curso%20Docker/2_Ejecutando_y_gestionando_contenedores_Docker/ "Ejecutanco y gestionando contenedores")

[Gestión de imágenes] (https://fjrnopzzm23qttuzha7zra.on.drv.tw/AA_Cursos/Curso%20Docker/3_Gestin_de_imgenes_Docker/?authuser=0 "Gestión de imágenes")

[Persistencia en docker] (https://fjrnopzzm23qttuzha7zra.on.drv.tw/AA_Cursos/Curso%20Docker/4_Volmenes_enDocker/?authuser=0 "Persistencia")

[Redes en docker] (https://fjrnopzzm23qttuzha7zra.on.drv.tw/AA_Cursos/Curso%20Docker/5_Redes_en_Docker/?authuser=0"Redes")

[Aplicaciones multicapa] (https://fjrnopzzm23qttuzha7zra.on.drv.tw/AA_Cursos/Curso%20Docker/7_Docker-Compose._Aplicaciones_multicapa/?authuser=0 "Aplicaciones multicapa")
### Sección 3: Servidor Apache

[Servidor Apache] (https://www.evernote.com/shard/s201/client/snv?noteGuid=2d0a817d-4cf7-44cb-b40e-6c70f188d262&noteKey=bba8501aef906f82172d58fe54b292b0&sn=https%3A%2F%2Fwww.evernote.com%2Fshard%2Fs201%2Fsh%2F2d0a817d-4cf7-44cb-b40e-6c70f188d262%2Fbba8501aef906f82172d58fe54b292b0&title=Servidor%2BHTTP%2BApache%2B-%2BWikipedia%252C%2Bla%2Benciclopedia%2Blibre&authuser=0 "Servidor HTTP Apache")

### Subsección 4: Apache Tomcat

[Apache Tomcat] (https://www.evernote.com/shard/s201/u/0/client/snv?isnewsnv=true&noteGuid=36c0ab6d-63a7-43fa-b9f4-197d2b31628e&noteKey=Oj7gDlCf8ePc77k65n1opkN0zdG0LRCkq6vgd-vQUIXEHsBN3fWuNTRfUw&sn=https%3A%2F%2Fwww.evernote.com%2Fshard%2Fs201%2Fsh%2F36c0ab6d-63a7-43fa-b9f4-197d2b31628e%2FOj7gDlCf8ePc77k65n1opkN0zdG0LRCkq6vgd-vQUIXEHsBN3fWuNTRfUw&title=How%2BTo%2BInstall%2BApache%2BTomcat%2B10%2Bon%2BUbuntu%2B20.04%2B%257C%2BDigitalOcean "Instalación de Apache Tomcat")


## Sección 5: DNS

[Servicios de nombres de dominio] (https://ubuntu.com/server/docs/service-domain-name-service-dns "DNS")



This is a *bare-minimum* template to create a Jekyll site that uses the [Just the Docs] theme. You can easily set the created site to be published on [GitHub Pages] – the [README] file explains how to do that, along with other details.

If [Jekyll] is installed on your computer, you can also build and preview the created site *locally*. This lets you test changes before committing them, and avoids waiting for GitHub Pages.[^1] And you will be able to deploy your local build to a different platform than GitHub Pages.

More specifically, the created site:

- uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
- uses the [GitHub Pages / Actions workflow] to build and publish the site on GitHub Pages

Other than that, you're free to customize sites that you create with this template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

[Browse our documentation][Just the Docs] to learn more about how to use this theme.

To get started with creating a site, simply:

1. click "[use this template]" to create a GitHub repository
2. go to Settings > Pages > Build and deployment > Source, and select GitHub Actions

If you want to maintain your docs in the `docs` directory of an existing project repo, see [Hosting your docs from an existing project repo](https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md#hosting-your-docs-from-an-existing-project-repo) in the template README.

----

[^1]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

[Just the Docs]: https://just-the-docs.github.io/just-the-docs/
[GitHub Pages]: https://docs.github.com/en/pages
[README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[Jekyll]: https://jekyllrb.com
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[use this template]: https://github.com/just-the-docs/just-the-docs-template/generate
