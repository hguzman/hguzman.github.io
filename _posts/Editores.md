# **Configurar editores de texto en Git**

Git trae por defecto el editor de texto Vim, pero comparandolo con otros resulta más complicado manejarlo y no ofrece todas la herramientas para el desarrollo de proyectos, por eso hoy les estare presentando como configurar editores de texto en git sin más preámbulo comencemos.

---
1. Verificar las configuraciones de nuestro git.

![](https://www.chipsypc.com/wp-content/uploads/2017/03/git5.png)

2. Una vez verificada las configuraciones de git procedemos ha configurar nuestro editor:

* **Visual code:** Este es uno de los editores de texto más utilizados por los desarrolladores, por lo completo que es con las herramientas que brinda, para configurarlo es muy sencillo utilizamos el siguiente comando.

```shell
git config --global core.editor "code --wait"
```

Luego en la consola colocamos

```shell
code .
```

* **Atom:** Este editor es muy famoso por la facilidad que tenemos para trabajar proyectos por git y github, ya que nos brinda herramientas que hacen más sencillo controlar las versiones del proyecto.

```shell
git config --global core.editor "atom --wait"
```

Luego en la consola colocamos

```shell
atom .
```

* **Notepad ++:** Aunque no es tan popular hay muchos desarrolladores que lo usan y se sienten comodos con su interfaz sencilla y facil de comprender.
<br>Para configurarlo es algo diferente a los otros, debemos localizar donde se encuentra el editor.

![](https://static.platzi.com/media/user_upload/ruta%20notepad%2B%2B-7dfcf51d-f0eb-410d-9ef9-4b1dd5f9212c.jpg)

Una vez localizada la carpeta colocamos el siguiente comando

```shell
git config --global core.editor "'C:\Program Files (x86)\Notepad++\notepad++.exe'"
```

Luego en la consola colocamos el siguiente comando

```shell
git commit
```

Para que nos abra el editor y podamos trabajar en nuestro proyecto.

* **Brackets:** Brackets es un editor de código fuente con un enfoque principal en el desarrollo web.para configurarlo es muy sencillo.

```shell
git config --local core.editor "brackets --wait"
```

Luego en la consola colocamos

```shell
git commit --amend
```
* **Sublime:** Al igual que sucede con notepad debemos localizar la ruta de la carpeta donde se encuentra el programa.

![](https://static.platzi.com/media/user_upload/ruta%20de%20sublime2-cf7c964b-6646-46b9-9673-4b2abd4a7353.jpg)

Luego nos dirigimos a la consola de git

```shell
git config --global core.editor "‘C:\Program Files (x86)\Sublime Text 3\sublime_text.exe’ --wait"
```

Luego en la consola colocamos

```shell
git commit o sublime .
```

Se usan dos formas depende la configuración del dispositivo o el sistemas operativo.

---

## **Nota:** 
como pudierón analizar en muchas casos se usaron en la configuración los siguientes comandos ``` "Nombre del editor" + . , git commit --amend o git commit```, estos comandos los utilizamos para esperar que se realicen los cambios para guardar y cerrar la ventana.
Una vez realizados los cambios y para regresar a Git.

