# Proyecto HTML Y CSS con Metodología BEM

Este es un proyecto local que muestra una página web utilizando HTML y CSS, con la implementación de la metodología BEM (Block Element Modifier).

<img src="img/captura1.jpeg" alt="pic" class="producto-img"/>

## Descripción

El proyecto consiste en una página web que muestra tres tarjetas con diferentes características y precios. Se utiliza la metodología BEM para organizar y nombrar las clases de CSS de manera estructurada y mantenible.

## Metodología BEM

La metodología BEM (Block Element Modifier) se utiliza para nombrar las clases de CSS de una manera coherente y comprensible. En este proyecto, las clases siguen la siguiente estructura:

- **Bloque**: Representa una entidad independiente. En este caso, los bloques son "tarjeta" y "container".

  - `.tarjeta`
  - `.container__image`

- **Elemento**: Partes de un bloque que tienen significado propio. Los elementos se nombran siguiendo la estructura `bloque__elemento`.

  - `.tarjeta__imagen`
  - `.tarjeta__contenido`
  - `.tarjeta__titulo`
  - `.tarjeta__descripcion`
  - `.tarjeta__valor`

- **Modificador**: Se utiliza para aplicar variaciones al bloque o elemento. Los modificadores se nombran siguiendo la estructura `bloque--modificador`.

  - `.tarjeta--individual`
  - `.tarjeta--team`
  - `.tarjeta--enterprise`

## Uso

1. Clona este repositorio en tu máquina local.
2. Abre el archivo `index.html` en tu navegador para ver las tarjetas.
3. El archivo `estilo.css` contiene los estilos CSS siguiendo la metodología BEM.

¡Disfruta explorando el proyecto!



### FORMA DE UTILIZACIÓN

DEBES UTILIZAR LA EXTENSION DE VSCODE `LIVE SHARED` 
EJECUTARLO DE FROMA LOCAL.

