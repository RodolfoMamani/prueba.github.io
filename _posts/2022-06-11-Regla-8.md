---
layout: post
author: Ivar Pedro Medrano Callisaya
title: Regla 8-Independencia física de datos.
---

Los clientes (aplicaciones, sistemas) permanecen inalterados a nivel lógico cuando se realicen cambios en las representaciones de almacenamiento o métodos de acceso. Ante cualquier cambio en la ubicación física de los datos, los querys escritos y probados no deben requerir modificaciones por dichos cambios en la ubicación física.

> La organización física de los datos, no debe afectar a las aplicaciones externas ni a los esquemas lógicos.

![A test image](https://www.dataprix.com/files/uploads/2/UOCBBDD/IntroBBDD/UOC_OpenSource_Introduccion_a_las_bases_de_datos_html_5.png)