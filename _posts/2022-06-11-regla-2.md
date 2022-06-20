---
layout: post
author: Ivar Pedro Medrano Callisaya
title: Regla 2-Acceso garantizado.
---

Todos los datos deben ser accesibles sin ambigüedad. Cada valor individual en la base de datos debe ser direccionable especificando el nombre de la tabla, la columna que lo contiene y la llave primaria. Eso significa que todo dato puede ser ubicado teniendo el nombre de la tabla, el nombre del campo y el registro del que se trate.


> No debe existir ambigüedad en los datos.


Un SGBD debe garantizar que todos los datos de una DB deben ser accesibles de manera lógica e inequívoca, a través de:

- Nombre de la tabla.
- Valor de la llave primaria.
- Nombre del atributo o columna..
