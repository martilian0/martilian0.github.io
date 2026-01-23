---
layout: post
title: CYBERPUNK Assault Rifle
description: Cyberpunk Assault Rifle Modeling
pin: true
categories: [PORTFOLIO, GAME ART]
tags: [3D Art, Game Art, Weapons]
date: 2026-01-08 11:56 -0300
lang: en
permalink: /posts/cyberpunk-ar/
image:
  path: /assets/cyberpunkar/cyberpunkrifle.jpg
  alt: Side view of Cyberpunk AR
---
Este fue un proyecto de modelado 3D inspirado en un concepto de vista lateral realizado por **[Dipo Muh](https://www.artstation.com/nomansnodead)** .
Siempre me han inspirado los mundos de ciencia ficción, y decidí que iba a intentar recrear uno de los muchos e increíbles diseños conceptuales realizados por Dipo. Así que elegí el segundo de los tres que aparecían en el concepto.

![img-description](https://cdna.artstation.com/p/assets/images/images/031/861/748/large/dipo-muh-guns-36-work.jpg?1604823616){: .left }{: .shadow }{: width="300" height="400" }

Pero también sabía que quería ir mucho más allá de la idea de hacer un modelo, quería hacer un [Viewmodel](https://developer.valvesoftware.com/wiki/Viewmodel) del arma (básicamente una vista en primera persona) y añadir algunas animaciones para ver cómo se vería dentro de un motor de juego... solo por diversión 😂.

Me tomó un poco más de lo esperado porque fui aprendiendo algunos aspectos técnicos del proyecto a medida que avanzaba. \
 Descubrí que los accesorios de superficie dura podían saltarse las reglas del modelado por subdivisión siempre que mantuvieran un buen sombreado en superficies planas. También tuve que reimaginar los otros lados del arma, ya que solo tenía una imagen como referencia y no provenía de un arma de la vida real. Me costó un poco descifrar cómo resolver eso, pero al final, para el propósito del proyecto, creo que cumplió bien su cometido.

![Desktop View](/assets/cyberpunkar/cyberpunk-ar-anim.gif){: .right }{: .shadow }{: w="300" }

Otro aspecto del proyecto fue cómo iba a realizar el rig del modelo para las partes móviles del arma, pero como eran piezas mecánicas, los movimientos no eran tan complicados y solo se movían en sus ejes correspondientes. La única excepción en este caso fue el cable enrollado, que tuvo un joint dinámico dedicado que se calculó después de terminar la animación base.

Durante la realización de este proyecto estuve fuera de mi casa por un tiempo, pero por suerte mi hermano tenía una computadora disponible donde pude trabajar, así que pude avanzar algo en la animación allí (:


  Cuando me acercaba a las etapas finales del proceso, decidí meterme en el diseño de audio y otros elementos, como añadir un elemento emisivo en la textura para que pudiera indicar al jugador que se estaba quedando sin munición, cambiando el color de la pantalla a rojo.

  <video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/392/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/226/martin-abarca-dipogun-vid00.mp4" type="video/mp4"></video>


Este proyecto me ayudó a descubrir la importancia de prestar atención a cómo se comportan los mapas de roughness y metallic con la luz reflejada en la superficie. A veces, un buen trabajo de pintura puede enmascararlo haciendo que el modelo se vea bien, pero tener aspectos acuosos o brillantes en el modelo que no reaccionan realmente a la luz hace que la ilusión se rompa muy rápido.


{%
  include embed/video.html
  src='https://video.gumlet.io/696069beac93fe085655e2c9/696e9c5a6f4a3a8ce103d397/main.mp4'
  title='Proceso de texturizado del mapa de roughness'
  autoplay=true
  loop=true
  muted=true
%}

<!-- Section pendient to edit

Maecenas et tortor consectetur, malesuada leo sed, placerat diam. Integer pellentesque tortor et tellus interdum, ut blandit metus sodales. Aenean dolor est, blandit et facilisis et, viverra in ipsum. Sed bibendum auctor dolor, vitae efficitur sem laoreet eget. Duis nec congue turpis, vel aliquet sapien. Donec eget venenatis ante. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Vivamus sodales ipsum nec dolor scelerisque tincidunt.
![Desktop View](/assets/pavelproskurin/lee-enfield-no4.jpg){: .left }{: .shadow }{: width="256" height="140" }


Gathering reference material and trying to understand from what real life weapon this concept was based on,I found that the Lee Enfield No.4 was the closest design.
Aliquam tincidunt dapibus velit, in consectetur ipsum facilisis in. Maecenas interdum odio arcu, quis eleifend ante tincidunt nec. Fusce non tristique orci. Vivamus hendrerit viverra risus et porttitor. Nam vel dolor vestibulum libero tincidunt scelerisque id non mi. In rhoncus vitae mi non porta. Cras viverra tellus ut mollis lacinia. Donec imperdiet lacinia blandit.

-->


![img-description](https://cdnb.artstation.com/p/assets/images/images/059/692/109/large/martin-abarca-martin-abarca-dipogun-00.jpg?1676946580)
_Marmoset Toolbag 5 Render_

<!--  Excluded FPV Section

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/392/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/226/martin-abarca-dipogun-vid00.mp4" type="video/mp4"></video>

-->


<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/394/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/228/martin-abarca-dipogun-vid01.mp4" type="video/mp4"></video>

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/400/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/232/martin-abarca-dipogun-vid02.mp4" type="video/mp4"></video>

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/404/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/237/martin-abarca-dipogun-vid03.mp4" type="video/mp4"></video>

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/405/thumb.jpg" tabindex="-1" preload="auto" muted="muted"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/239/martin-abarca-dipogun-vid04.mp4" type="video/mp4"></video>

> Si deseas ver el artículo completo, puedes visitar el post de**[Artstation](https://www.artstation.com/artwork/8blvAn)**.
{: .prompt-info }
