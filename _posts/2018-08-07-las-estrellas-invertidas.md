---
layout: posts
title:  Las Estrellas de Cabeza
date:   2018-08-07 
categories: [tierra] 
published: true
pinned: true
---

Te has dado cuenta de que la constelación de Orión está dada vuelta? Sabes por qué?  



{% include toc %}

<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>


***
***

Se le atribuye al pensador griego Eratóstenes [(artículo en Wikipedia)](https://es.wikipedia.org/wiki/Eratóstenes) la primera medición del radio de la Tierra. Sin embargo, Eratóstenes vivió durante el siglo 3 A.C., y a esa altura los griegos ya tenían una idea clara de que la Tierra no era plana. Según historiadores de la Grecia Antigua y Clásica [(en este libro, por ejemplo)](https://www.amazon.com/Early-Greek-Astronomy-Aristotle-Aspects/dp/0801493102), ya en la época de Aristóteles, todo "pensador de reputación estaba convencido de la que Tierra era redonda" (traducción mía). Entonces, antes de la medición precisa de Erastóstenes (que revisaremos en algún futuro post), cómo llegaron los griegos a concluir sobre la forma de la Tierra?

Los griegos de la Epoca Clásica (siglos 5to y 4to A.C.) eran -- junto con los fenicios y los cartaginenses -- los más avezados navegantes del Mediterráneo. Tal vez, eso de que "los barcos desaparecen bajo el horizonte" fue suficiente prueba de que la superficie del Mundo tenía algún grado de curvatura. Sin embargo, los griegos tenían otra fuente de convincente evidencia: el cielo.

La Astronomía occidental (al igual que la, ejem, Astrología) tiene sus cimientos en la Grecia Clásica y Helénica. Los griegos eran entusiastas observadores del Firmamento! Los astros jugaron un rol muy importante tanto en su ciencia como en su mitología. La extensión Norte-Sur de los territorios que estaban bajo influencia griega (desde el Mar Negro hasta Egipto, unos 1300 kilómetros) les permitió percatarse de que ciertos astros en el cielo no eran visibles desde todas partes. Aristóteles afirmó que ciertas estrellas visibles desde Chipre no serían visibles desde el norte de Grecia [(página 489 de este libraco de acá)](https://books.google.com/books?id=MLbmAgAAQBAJ&pg=PA489&lpg=PA489&dq=aristotle+Cyprus+%22which+are+not+seen+in+the+northerly+regions%22&source=bl&ots=kkNGn4Emks&sig=v4Z-OAVqtj8_cRokvpRxCxI1f8Q&hl=en&sa=X&ved=2ahUKEwj81bHuntzcAhWSyoUKHdG0DEIQ6AEwAnoECAkQAQ#v=onepage&q=aristotle%20Cyprus%20%22which%20are%20not%20seen%20in%20the%20northerly%20regions%22&f=false).

Así como una persona parada en una loma (ver figura) no puede ver los objetos localizados más allá de cierto ángulo (sin importar la distancia a la que dicho objeto se encuentre!), dos personas situadas en distintas partes de la Tierra, no ven exactamente las mismas estrellas. Para notar este efecto a simple vista, se necesitan algunos cientos de kilómetros de distancia entre los dos puntos de observación.


{% capture fig_img %}
![Foo]({{ "/images/curved_surface_observer.png" | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption> Superficies curvas bloquean objetos de nuestro campo de visión (figure credit D.J.Munoz). </figcaption>
</figure>


## El Cielo a lo Largo del Territorio Chileno

La siguiente figura (obtenida del sitio [skyviewcafe.com](http://www.skyviewcafe.com/)) consiste de un mapa del cielo visto desde dos lugares de Chile al mismo tiempo (12 de enero de 2019 a las 23:59:00). Cada mapa del cielo es representado como un círculo. El **horizonte** (que en la práctica puede estar bloqueado por cerros, árboles u otro obstáculo) es la circunferencia del círculo. El centro del círculo corresponde a mirar directamente arriba (por ejemplo, acostados sobre el suelo), es decir, a un ángulo de noventa grados ($$ 90^\circ $$) respecto del horizonte. Esta ubicación se conoce como el **cénit**. El ángulo entre alguna estrella y el horizonte, se conoce como la **elevación**.  

En la figura, he marcado la posición de tres constelaciones: La **Cruz del Sur** o Crux (en azul), parte de **Centauro** (en verde) y la famosa **Orión** (rojo), que discutiremos en más detalle luego. Además, he destacado una de las estrellas más brillantes en el cielo de verano, Canopus (en morado).

 

{% capture fig_img %}
![Foo]({{ "/images/two_skies.png" | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption> El cielo visto desde dos ubicaciones separadas por 3000 kilómetros. (figure credit skyviewcafe.com).</figcaption>
</figure>

Lo primero que uno puede notar es que, al ir desde Arica a Puerto Montt, las constelaciones de han movido hacia arriba. En particular, la elevación de Alfa Crux -- el extremo inferior (o más a la derecha) de la cruz -- es de 12 grados vista desde Arica (apenas por sobre el horizonte). En cambio, vista desde Puerto Montt, la elevación de Alfa Crux es de 31 grados: **18 grados de diferencia**! Análogo es el caso de Canopus. Canopus está casi bajo la línea Norte-Sur en el mapa (al igual que Arica-Puerto Montt). La elevación de Canopus vista desde Arica es de 55 grados, mientras que desde Puerto Montt es de 76 grados: **21 grados de diferencia**, mas o menos lo mismo que en el caso de Alfa Crux. De donde vienen estos **20 grados de rotación**? Pues simplemente de la **diferencia en latitud entre Arica y Puerto Montt**, que es de 23 grados aproximadamente (Arica tiene latitud sur de 18 grados, y Puerto Montt de 41 grados). Por qué la diferencia no es exactamente igual en todos los casos? Porque no solamente importa la diferencia Norte-Sur, sino que la diferencia Este-Oeste. El hecho de que Chile esté extendido aproximadamente a lo largo del eje Norte-Sur ayuda en este ejercicio, pero aún hay un par de grados extra que se nos quedan en el bolsillo.

Por último, hablemos un poco de las estrellas en el círculo verde. Éstas son parte de la constelación de Centauro. Las dos más brillantes son Alfa y Beta Centauri, pero en el cielo de Arica sólo Beta Centauri es visible. Es precisamente éste el fenómeno que comentó Aristóteles en sus[ apuntes](https://books.google.com/books?id=MLbmAgAAQBAJ&pg=PA489&lpg=PA489&dq=aristotle+Cyprus+%22which+are+not+seen+in+the+northerly+regions%22&source=bl&ots=kkNGn4Emks&sig=v4Z-OAVqtj8_cRokvpRxCxI1f8Q&hl=en&sa=X&ved=2ahUKEwj81bHuntzcAhWSyoUKHdG0DEIQ6AEwAnoECAkQAQ#v=onepage&q=aristotle%20Cyprus%20%22which%20are%20not%20seen%20in%20the%20northerly%20regions%22&f=false). Según sus comentarios, la Tierra tenía que ser curva, y probablemente esférica. Más aún, dijo que no podía ser muy grande, dado lo notorio del efecto al moverse uno solamente algunos cientos de kilómetros.


 
## Orión de Patas Arriba
 
Ahora, enfoquémonos en Orión. Esta constelación también se ha movido, pero es interesante por un motivo adicional: está de cabeza. En ambos mapas del cielo que puse arriba -- o si van afuera durante el verano y la buscan -- Orión aparece así:

{% capture fig_img %}
![Foo]({{ "/images/orion_observer_south.png" | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption> Las estrellas de la constelación de Orión y estrellas colindantes como sería vista desde el hemisferio sur (figure credit D.J.Munoz).</figcaption>
</figure>

Sin embargo, si buscan en Google imágenes de Orión, encontrarán algo así:

{% capture fig_img %}
![Foo]({{ "/images/orion_observer_north.png" | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption> Estrellas en y alrededor de Orión (izquierda) y el diagrama de la constelación (derecha) como son presentadas frecuentemente en libros de texto y fuentes de internet (figure credit D.J.Munoz).</figcaption>
</figure>

Bueno, en esta figura, claramente Orión está al revés de como la podríamos ver en Chile. Sin embargo, ésa es la orientación "oficial", es decir, la que le dieron los griegos al identificar este conjunto de estrellas con la figura mitológica del arquero.

Resulta que esta **inversión de Orión** no es más que otra consecuencia de la curvatura de la Tierra.  En la siguiente imagen, pueden apreciar que Orión no está "de cabeza", si no que lo estamos nosotros en el hemisferio sur!

{% capture fig_img %}
![Foo]({{ "/images/orion_upside_down.png" | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption> La orientación de la constelación de Orión depende de si estamos en el hemisferio
norte o sur. (figure credit D.J.Munoz).</figcaption>
</figure>

***
***

Estos fenómenos del cielo son pura consecuencia de **la curvatura de la Tierra**, y pueden ser corroborados por ti hoy mismo, esta noche, simplemente saliendo a mirar las estrellas.


