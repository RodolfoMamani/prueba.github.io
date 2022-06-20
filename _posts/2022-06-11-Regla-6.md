---
layout: post
author: Ivar Pedro Medrano Callisaya
title: Regla 6-Actualizacion de vistas
---

Todas las vistas que son teóricamente actualizables deben ser actualizables por el sistema, de manera transparente, si en la base de datos se crea una vista de una tabla, se podría añadir un registro a la vista y eso significaría que se daría de alta el registro en la tabla original.

> - Las vistas tienen que mostrar información actualizada
- No puede haber diferencia entre los datos de las vistas y
los datos de las tablas base

Algunos gestores caen en problemas en esta regla, ya que, a pesar de tener vistas actualizables el RDBMS manda error al realizar una modificación.