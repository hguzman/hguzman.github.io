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

## Remplazar información dentro de paréntesis

Para remplazar la información dentro de () se usa la instrucción:


```shell
ci)
```
## Realizar paginación en VIM

Para paginar hacia abajo se usa (page down) **CTRL-D** y para moverse hacia arriba page up **CTRL-U**

## Plegado de lineas de codigo

Para realizar el pegado se debe estar en modo visual y seleccionar el código que se desea plegar **zf** y para colocarlo como estaba se usa **za**

## Comandos para comentar código con tcomment_vim

**gcir / gcar** comment inside/around Ruby do/end block. **gcim / gcam** comment inside/around Ruby method. **gciM / gcaM** comment inside/around Ruby class.

Plus normal Commentary maps like **gcc** to comment a line, or 5: to comment 5 lines
Para ver un tutorial en consola **vimtutorial**

### Escribir después de una palabra

**wi** o **ea**

## Quitar el highlights despues de buscar
nmap <Leader><CR> :nohlsearch<cr>




[canva]: https://www.canva.com
