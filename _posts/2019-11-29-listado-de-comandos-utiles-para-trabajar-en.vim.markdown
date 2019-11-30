---
layout: post
title:  "Listado de comandos útiles para trabajar con VIM"
date:   2019-11-29 22:03:36 +0530
categories: Herramientas vim
---
Una de las herramientas que mas trabajo me ha dado para aprender a utilizar es VIM, en este documento describo algunos tips y comentarios para el manejo de la herramienta.

## Duplicar un archivo

```shell
:saveas %:h/nuevo_archivo
```

## Remplazar texto dentro de un archivo

Muchas veces se requiere remplazar textos dentro de un archivo, el comando para realizarlo desde VIM es:

```shell
:%s/texto_a_sustituir/texto_nuevo/g

:6,10s/texto_a_sustituir/text_nuevo/g
```

[canva]: https://www.canva.com
