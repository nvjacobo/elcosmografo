---
title: "Error 451: Censura a la vista"
date: "2015-12-23"
coverImage: "451.jpg"
---

Tal vez recuerdes _Fahrenheit 451_, la famosa novela de Ray Bradbury publicada en 1953 donde por instrucciones del gobierno los bomberos se dedican a quemar libros. Pues algo similar sucede en internet con un código que lleva por nombre **_error 451_**, en honor a la novela antes mencionada y que fue aprobado por el Internet Engineering Steering Group (IESG) responsable del manejo técnico del [Internet Engineering Task Force](https://www.ietf.org/), órgano encargado de regular las propuestas y los estándares de Internet, conocidos como Petición de Comentarios (RFC).

Este código fue propuesto inicialmente en 2012, cuando el gobierno del Reino Unido [ordenó bloquear el acceso a The Pirate Bay](http://www.csmonitor.com/Technology/Latest-News-Wires/2012/0430/UK-Internet-service-providers-ordered-to-block-Pirate-Bay-file-sharing-site); sin embarfo en aquella ocasión fue utilizado el código "403: Forbidden".

El estado de error 451 del protocolo HTTP **pretende ser mostrado cuando el usuario solicita un recurso que no está disponible por motivos legales**, como una recurso web censurados por un _gobierno_. Como lo indica la descripción de la Petición de Comentarios:

> Este código de estado indica que el servidor está negando el acceso a la de recursos como consecuencia de una demanda legal.

Tim Bray quien propuso por primera vez el error al interior del [IETF](https://www.ietf.org) y quienes lo han motivado indican que se trata de una forma de destacar **la censura en línea**.

A pesar de que el código de error puede utilizarse, [Mark Nottingham, miembro del IETF, señala](https://www.rt.com/news/326814-error-451-government-blocked/):

> In some jurisdictions, I suspect that censorious governments will disallow the use of 451, to hide what they're doing. We can't stop that (of course), but if your government does that, it sends a strong message to you as a citizen about what their intent is.

Traducción:

> En algunas jurisdicciones, me parece que los gobiernos que censuran no permitirán el uso de 451 para ocultar lo que hacen. No podemos detener eso (desde luego), pero si tu gobierno lo hace te manda como ciudadano un fuerte mensaje sobre las intenciones que tiene.

[New HTTP error code 451 to signal censorship](http://www.theregister.co.uk/2015/12/21/censorship_415_error_code_approved_by_ietf) / \[Kieren McCarthy - The Register\]
