---
layout: post
author: Ivar Pedro Medrano Callisaya
title: Regla 9-Independencia lógica de datos.
---

Los cambios al nivel lógico (tablas, columnas, filas, etc.) no deben requerir un cambio a una solicitud basada en la estructura. La independencia de datos lógica es más difícil de lograr que la independencia física de datos, pero también debe ser posible que los querys que ya están escritos (si se modifica un tipo de dato, se añaden campos, se eliminan campos que no se requieren) no requieran cambios.

> Los cambios a nivel lógico, no modifican la estructura física de la base de datos.

![A test image](https://www.dataprix.com/files/uploads/2/UOCBBDD/IntroBBDD/UOC_OpenSource_Introduccion_a_las_bases_de_datos_html_6.png)