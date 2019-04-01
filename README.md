# Presentation Template

## Objetivo

Plantilla para crear un repositorio de presentaciones.

Simplemente descarga (o clona) este proyecto en tu máquina y modifica a tu gusto
los ficheros `src/docs/asciidoc/` con extensión `.adoc` (se include index.adoc y tutorial.adoc
a modo de ejemplo)

Puedes crear tantas presentaciones como desees. Por cada fichero `.adoc` el sistema creará
una presentación independiente


## Generar

`./gradlew build`

## Resultado

en la carpeta `build/docs(slides` encontrarás un `html` por cada `adoc`


## Publicar

Si dispones de una cuenta en Gitlab, simplemente crea un fork de este proyecto y crea
tus presentaciones. Cuando publiques los cambios Gitlab generará y publicará tus slides
usando la funcionalidad de `pages`

## Main

Template to create a repository of slides

Download (or clone) this repository and change `src/docs/asciidoc/` files with `.adoc`
extension (index.adoc and tutorial.adoc are examples)

You can create as many presentations you want. Each `.adoc` file will have an indepenent
slide

## Build

`./gradlew build`

## Result

In the `build/docs(slides` folder you'll your slides


## Publish

If you have a Gitlab account simply fork this repo and create your slides. Once you
publish your changes, Gitlab will build and publish your slides using `pages` feature

