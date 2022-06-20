---
layout: post
author: Ivar Pedro Medrano Callisaya
title: Regla 3-Representación de valores nulos.
---

El sistema debe ser capaz de representar
valores nulos en una forma sistemática, sin importar el tipo de datos del ítem.
Los valores nulos deben ser distintos de cero o cualquier otro número, y de cadenas
vacías.


> Soporte total de valores nulos.


Un SGBD debe soportar en su totalidad el manejo de valores nulos, entendemos como nulo, aquello que representa la información no disponible o inaplicable, por ejemplo, los valores distintos a:

    - Vacío
    - Blanco
    - Cero
    - Cualquier otro dato numérico.

Aun cuando el SGBD soporte valores nulos, se debe evitar la utilización de este tipo de datos.
