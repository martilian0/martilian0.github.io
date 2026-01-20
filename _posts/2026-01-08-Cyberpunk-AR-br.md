---
layout: post
title: Rifle de Assalto CYBERPUNK
description: Modelagem de Rifle de Assalto Cyberpunk
pin: true
categories: [PORTFOLIO, GAME ART]
tags: [3D Art, Game Art, Weapons]
date: 2026-01-08 11:56 -0300
lang: br
permalink: /posts/cyberpunk-ar/
image:
  path: /assets/cyberpunkar/cyberpunkrifle.jpg
  alt: Vista lateral do AR Cyberpunk
---

Este foi um projeto de modelagem 3D inspirado em um conceito de vista lateral feito por **[Dipo Muh](https://www.artstation.com/nomansnodead)**.
Sempre fui inspirado por mundos de ficção científica e decidi que tentaria recriar um dos muitos conceitos incríveis feitos pelo Dipo. Então, escolhi o segundo dos três exibidos no conceito.

![img-description](https://cdna.artstation.com/p/assets/images/images/031/861/748/large/dipo-muh-guns-36-work.jpg?1604823616){: .left }{: .shadow }{: width="300" height="400" }

Mas eu também sabia que queria ir muito além da ideia de apenas fazer um modelo; eu queria fazer um [Viewmodel](https://developer.valvesoftware.com/wiki/Viewmodel) da arma (basicamente uma visão em primeira pessoa) e adicionar algumas animações para ver como ficaria dentro de um motor de jogo... só por diversão 😂.

Levei um pouco mais de tempo do que o esperado porque fui aprendendo alguns aspectos técnicos do projeto conforme avançava.
Descobri que props de "hard surface" poderiam pular as regras de modelagem por subdivisão, desde que mantivessem um bom sombreamento (shading) em superfícies planas. Além disso, tive que reimaginar os outros lados da arma, já que havia apenas uma imagem como referência, e não era baseada em uma arma da vida real. Levei um tempo para descobrir como resolver isso, mas no fim, para o propósito do projeto, acho que o resultado ficou ok.

![Desktop View](/assets/cyberpunkar/cyberpunk-ar-anim.gif){: .right }{: .shadow }{: w="300" }

Outro aspecto do projeto foi como eu iria "rigar" o modelo para as partes móveis da arma, mas como eram partes mecânicas, os movimentos não eram tão complicados e apenas se moviam em seus eixos correspondentes. A única exceção neste caso foi o cabo enrolado, que recebeu uma junta dinâmica dedicada calculada após a finalização da animação base.

Durante a realização deste projeto, fiquei fora de casa por algum tempo, mas felizmente meu irmão tinha um computador disponível onde eu podia trabalhar, então consegui progredir na animação por lá (:

Quando estava chegando perto das fases finais do processo, decidi mergulhar no design de áudio e outros elementos, como adicionar um elemento emissivo na textura para sinalizar ao jogador que a munição estava acabando, mudando a cor do visor para vermelho.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam vulputate iaculis magna, ut cursus orci. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nam pretium sodales enim a laoreet. Suspendisse fermentum finibus orci, feugiat vestibulum elit porttitor eget. Aenean ultricies mauris eu nisl tempor, et consectetur eros pretium. Cras vel scelerisque lacus. In at nisi non felis dapibus porta. Vestibulum arcu mi, venenatis non quam ac, accumsan mollis lorem.

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/392/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/226/martin-abarca-dipogun-vid00.mp4" type="video/mp4"></video>

## Titulardo

Este projeto me ajudou a descobrir a importância de prestar atenção em como seus mapas de roughness e metallic se comportam com a luz refletindo na superfície. Às vezes, uma boa pintura pode mascarar o modelo e fazê-lo parecer bom, mas ter aspectos molhados ou brilhantes que não reagem de fato à luz faz com que a ilusão caia muito rápido.

{%
  include embed/video.html
  src='https://video.gumlet.io/696069beac93fe085655e2c9/696e9c5a6f4a3a8ce103d397/main.mp4'
  title='Processo de texturização do mapa de Roughness'
  autoplay=true
  loop=true
  muted=true
%}

Maecenas et tortor consectetur, malesuada leo sed, placerat diam. Integer pellentesque tortor et tellus interdum, ut blandit metus sodales. Aenean dolor est, blandit et facilisis et, viverra in ipsum. Sed bibendum auctor dolor, vitae efficitur sem laoreet eget. Duis nec congue turpis, vel aliquet sapien. Donec eget venenatis ante. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Vivamus sodales ipsum nec dolor scelerisque tincidunt.
![Desktop View](/assets/pavelproskurin/lee-enfield-no4.jpg){: .left }{: .shadow }{: width="256" height="140" }

Ao reunir material de referência e tentar entender em qual arma da vida real este conceito foi baseado, descobri que o Lee Enfield No.4 era o design mais próximo.
Aliquam tincidunt dapibus velit, in consectetur ipsum facilisis in. Maecenas interdum odio arcu, quis eleifend ante tincidunt nec. Fusce non tristique orci. Vivamus hendrerit viverra risus et porttitor. Nam vel dolor vestibulum libero tincidunt scelerisque id non mi. In rhoncus vitae mi non porta. Cras viverra tellus ut mollis lacinia. Donec imperdiet lacinia blandit.

![img-description](https://cdnb.artstation.com/p/assets/images/images/059/692/109/large/martin-abarca-martin-abarca-dipogun-00.jpg?1676946580)
_Render no Marmoset Toolbag 5_

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/394/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/228/martin-abarca-dipogun-vid01.mp4" type="video/mp4"></video>

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/400/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/232/martin-abarca-dipogun-vid02.mp4" type="video/mp4"></video>

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/404/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/237/martin-abarca-dipogun-vid03.mp4" type="video/mp4"></video>

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/405/thumb.jpg" tabindex="-1" preload="auto" muted="muted"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/239/martin-abarca-dipogun-vid04.mp4" type="video/mp4"></video>

> Se você deseja ver o artigo completo, pode visitar o post no **[Artstation](https://www.artstation.com/artwork/8blvAn)**.
{: .prompt-info }
