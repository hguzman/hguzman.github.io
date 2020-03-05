---
layout: post
title:  "Colaborar en un proyecto open source GitHub"
date:   2020-04-05 13:00:00 +0530
categories: git GitHub
---

En este post quiero incluir algunas notas sobre el manejo de CSS.

1. **Fork del repositorio**: Realiza un copia exacta del repositorio en el perfil del usuario colaborador
2. **Clonar el repositorio**: Una vez se realiza el Fork, se debe clonar el repositorio forkeado

```shell
git clone https://github.com/User/NombreRepo.git
```

3. **Entrar en la carpeta clonada**: Para entrar a la carpeta clonada desde una consola ubuntu use el comando

```shell
cd NombreRepo
```

4. **Verificar las conexiones con fuentes remotas**: por defecto se mostrara la conexión realizada cuando se clono el repositorio, por defecto es llamada origin

```shell
git remote -v
```
