---
layout: post
title: Filtrar únicos
date: 2022-08-29 09:05 -0400
---

Usando Google Spreadsheets se quiere filtrar todos los elementos únicos.

### Pasos

Encabezado columna, click en ícono de filtro, filtrar con condición `=COUNTIF(B2:B,B2:B)=1`

![](/assets/img/filtra-unicos.png)

### Bonus

Si luego de filtrar se quiere contar el total de filas: `=SUBTOTAL(103,B2:B96)`

¿Por qué ese «103»? — es un _mapeo_ que usa google para representar una
función determinada, es como un ID. Para el caso 103 representa `COUNTA`.

[Relacionado](https://support.google.com/docs/answer/3093649?hl=en)



