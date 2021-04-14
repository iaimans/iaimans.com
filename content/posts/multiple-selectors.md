---
title: Multicursores en IntelliJ
date: "2021-04-14T17:30:00.000Z"
template: "post"
description: ""
draft: false
socialImage: /photo.jpg
slug: "multicursores-intellij"
category: "Tech"
tags:
  - "Tech"
  - "IntelliJ"
---

En ocasiones resulta de gran utilidad poder editar múltiples partes de un fichero a la vez. Para las tareas más sencillas normalmente basta con hacer uso de las utilidades de refactor que nos proporciona IntelliJ, pero no siempre nos pueden ofrecer la solución que buscamos. Es por ello que IntelliJ implementó en 2014 los famosos multicursores que ya exisitían en otros editores de texto como Sublime Text. 


## Selección múltiple con teclado

### Seleccionar todas las ocurrencias
Atajo de teclado: `Alt` + `Ctrl` + `J`

![todas-ocurrencias.gif](/media/todas-ocurrencias.gif)

### Selecionar la siguiente ocurrencia
Atajo de teclado: `Alt` + `J`

![siguiente-ocurrencia.gif](/media/siguiente-ocurrencia.gif)


### Eliminar la ocurrencia
Atajo de teclado: `Alt` + `Shift` + `J`

![eliminar-ocurrencia.gif](/media/eliminar-ocurrencia.gif)


## Selección múltiple con ratón

### Selección en bloque
Seleccionamos un bloque de texto mientras mantenemos pulsado `Alt` + `Ctrl` + `Shift`. Esto nos creará tanttos selectores como líneas hayamos seleccionado.

![seleccion-bloque.gif](/media/seleccion-bloque.gif)


### Selección libre
Podemos pulsar con el ratón en cualquier parte mientras mantenemos pulsado `Alt` + `Shift`  y se creará un selector en ese punto.

![seleccion-libre.gif](/media/seleccion-libre.gif)