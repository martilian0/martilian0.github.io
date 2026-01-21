---
layout: post
title: Fusil d'Assaut CYBERPUNK
description: Modélisation d'un Fusil d'Assaut Cyberpunk
pin: true
categories: [PORTFOLIO, GAME ART]
tags: [3D Art, Game Art, Weapons]
date: 2026-01-08 11:56 -0300
lang: fr
permalink: /posts/cyberpunk-ar/
image:
  path: /assets/cyberpunkar/cyberpunkrifle.jpg
  alt: Vue latérale de l'AR Cyberpunk
---
C'était un projet de modélisation 3D inspiré par un concept de vue latérale réalisé par **[Dipo Muh](https://www.artstation.com/nomansnodead)** .
J'ai toujours été inspiré par les mondes de science-fiction, et j'ai décidé de recréer l'un des nombreux designs de concepts géniaux réalisés par Dipo. J'ai donc choisi le deuxième des trois présentés dans le concept.

![img-description](https://cdna.artstation.com/p/assets/images/images/031/861/748/large/dipo-muh-guns-36-work.jpg?1604823616){: .left }{: .shadow }{: width="300" height="400" }

Mais je savais aussi que je voulais aller bien au-delà de l'idée d'en faire un modèle, je voulais faire un [Viewmodel](https://developer.valvesoftware.com/wiki/Viewmodel) de l'arme, (essentiellement une vue à la première personne) et ajouter quelques animations pour voir comment elle rendrait à l'intérieur d'un moteur de jeu... juste pour le plaisir 😂.

Cela m'a pris un peu plus de temps que prévu parce que j'apprenais certains aspects techniques du projet au fur et à mesure que j'avançais. \
 J'ai découvert que les accessoires de type hard surface pouvaient ignorer les règles de modélisation par subdivision tant qu'ils conservaient un bon ombrage sur les surfaces planes. J'ai également dû réimaginer les autres côtés de l'arme, car il n'y avait qu'une seule image de référence, et non une arme de la vie réelle. Il m'a fallu un peu de temps pour comprendre comment résoudre cela, mais au final, pour l'objectif du projet, je pense que cela a plutôt bien fonctionné.

![Desktop View](/assets/cyberpunkar/cyberpunk-ar-anim.gif){: .right }{: .shadow }{: w="300" }

Un autre aspect du projet était la manière dont j'allais rigger le modèle pour les parties mobiles de l'arme, mais comme il s'agissait de pièces mécaniques, les mouvements n'étaient pas si compliqués et se déplaçaient simplement dans leurs axes correspondants. La seule exception dans ce cas était le câble spiralé, qui a reçu un joint dynamique dédié calculé après que l'animation de base a été terminée.

Pendant la réalisation de ce projet, j'ai été absent de chez moi pendant un certain temps mais heureusement mon frère avait un ordinateur disponible où je pouvais travailler, j'ai donc pu faire quelques progrès sur l'animation là-bas (:


  Lorsque je me suis rapproché des étapes finales du processus, j'ai décidé de me lancer dans la conception audio et d'autres éléments, comme l'ajout d'un élément émissif dans la texture pour signaler au joueur qu'il n'avait plus de munitions, en changeant la couleur de l'affichage en rouge.

  <video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/392/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/226/martin-abarca-dipogun-vid00.mp4" type="video/mp4"></video>


Ce projet m'a aidé à découvrir l'importance de prêter attention à la façon dont vos cartes de roughness et de metallic se comportent avec la lumière se reflétant sur la surface. Parfois, un bon travail de peinture peut le masquer en rendant le modèle beau, mais avoir de l'eau ou des aspects brillants sur le modèle qui ne réagissent pas réellement à la lumière fait que l'illusion s'estompe très rapidement.


{%
  include embed/video.html
  src='https://video.gumlet.io/696069beac93fe085655e2c9/696e9c5a6f4a3a8ce103d397/main.mp4'
  title='Roughness map texturing process'
  autoplay=true
  loop=true
  muted=true
%}


<!-- Excluded section


Maecenas et tortor consectetur, malesuada leo sed, placerat diam. Integer pellentesque tortor et tellus interdum, ut blandit metus sodales. Aenean dolor est, blandit et facilisis et, viverra in ipsum. Sed bibendum auctor dolor, vitae efficitur sem laoreet eget. Duis nec congue turpis, vel aliquet sapien. Donec eget venenatis ante. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Vivamus sodales ipsum nec dolor scelerisque tincidunt.
![Desktop View](/assets/pavelproskurin/lee-enfield-no4.jpg){: .left }{: .shadow }{: width="256" height="140" }

En rassemblant du matériel de référence et en essayant de comprendre sur quelle arme réelle ce concept était basé, j'ai trouvé que le Lee Enfield No.4 était le design le plus proche.
Aliquam tincidunt dapibus velit, in consectetur ipsum facilisis in. Maecenas interdum odio arcu, quis eleifend ante tincidunt nec. Fusce non tristique orci. Vivamus hendrerit viverra risus et porttitor. Nam vel dolor vestibulum libero tincidunt scelerisque id non mi. In rhoncus vitae mi non porta. Cras viverra tellus ut mollis lacinia. Donec imperdiet lacinia blandit.

-->

![img-description](https://cdnb.artstation.com/p/assets/images/images/059/692/109/large/martin-abarca-martin-abarca-dipogun-00.jpg?1676946580)
_Rendu Marmoset Toolbag 5_

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/394/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/228/martin-abarca-dipogun-vid01.mp4" type="video/mp4"></video>

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/400/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/232/martin-abarca-dipogun-vid02.mp4" type="video/mp4"></video>

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/404/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/237/martin-abarca-dipogun-vid03.mp4" type="video/mp4"></video>

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/405/thumb.jpg" tabindex="-1" preload="auto" muted="muted"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/239/martin-abarca-dipogun-vid04.mp4" type="video/mp4"></video>

> Si vous souhaitez voir l'article complet, vous pouvez visiter le post sur **[Artstation](https://www.artstation.com/artwork/8blvAn)**.
{: .prompt-info }
