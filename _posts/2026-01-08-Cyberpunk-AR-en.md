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






This was a 3D modeling project inspired by a side view concept made by **[Dipo Muh](https://www.artstation.com/nomansnodead)** .
I've always been inspired by Sci-fi worlds, and I decided that I was going to try to recreate one of the many awesome concepts designs made by Dipo. So I picked the second of the three displayed in the concept.

![img-description](https://cdna.artstation.com/p/assets/images/images/031/861/748/large/dipo-muh-guns-36-work.jpg?1604823616){: .left }{: .shadow }{: width="300" height="400" }

But I also knew that I wanted to go far beyond the idea of making a model of it, I wanted to make a [Viewmodel](https://developer.valvesoftware.com/wiki/Viewmodel) of the weapon, (basically a first person view of it) and add some animations to see how it would look inside a game engine... just for fun 😂.

It took me a bit longer than I expected because I was learning some technical aspects of the project as i was moving forward. \
 I discovered that hard surface props could skip the rules of subdivition modeling as long as it keeps good shading in flat surfaces. Also I had to re imagine the other sides of the weapon, since it was just one picture as reference, and not from a real life weapon. It took me a bit to figure out how to solve that, but in the end, for what the purpose of the project was, I think it kinda did the job ok.

![Desktop View](/assets/cyberpunkar/cyberpunk-ar-anim.gif){: .right }{: .shadow }{: w="300" }

Another aspect of the project was how I was gonna rig the model for the moving parts of the weapon, but since they were mechanical parts, the movements were not that complicated and just moved in their corresponding axis.The only one exception in this case was the coiled cable, which got a dedicated dynamic joint that was calculated after the base animation was done.

During the making of this project I was out of my house for some time but luckily my brother had a computer available where I can work so I was able to make some progress on the animation there (:


  When I was getting close to the final stages of the process, I decided to jump into the audio design and other elements, like adding a emissive element in the texture so it can signal to the player that it was running out of ammo, by changing the display color to red.

  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam vulputate iaculis magna, ut cursus orci. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Nam pretium sodales enim a laoreet. Suspendisse fermentum finibus orci, feugiat vestibulum elit porttitor eget. Aenean ultricies mauris eu nisl tempor, et consectetur eros pretium. Cras vel scelerisque lacus. In at nisi non felis dapibus porta. Vestibulum arcu mi, venenatis non quam ac, accumsan mollis lorem.

  <video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/392/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/226/martin-abarca-dipogun-vid00.mp4" type="video/mp4"></video>

## Titulardo

This project helped me discover the importance of paying attention to how your roughness and metallic maps behave with light reflecting on the surface. Sometimes a good paint job can mask it making the model look good but having water or shiny aspects on the model that dont actually react to the light, makes the illusion fall really quick.


{%
  include embed/video.html
  src='https://video.gumlet.io/696069beac93fe085655e2c9/696e9c5a6f4a3a8ce103d397/main.mp4'
  title='Roughness map texturing process'
  autoplay=true
  loop=true
  muted=true
%}

Maecenas et tortor consectetur, malesuada leo sed, placerat diam. Integer pellentesque tortor et tellus interdum, ut blandit metus sodales. Aenean dolor est, blandit et facilisis et, viverra in ipsum. Sed bibendum auctor dolor, vitae efficitur sem laoreet eget. Duis nec congue turpis, vel aliquet sapien. Donec eget venenatis ante. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Vivamus sodales ipsum nec dolor scelerisque tincidunt.
![Desktop View](/assets/pavelproskurin/lee-enfield-no4.jpg){: .left }{: .shadow }{: width="256" height="140" }


Gathering reference material and trying to understand from what real life weapon this concept was based on,I found that the Lee Enfield No.4 was the closest design.
Aliquam tincidunt dapibus velit, in consectetur ipsum facilisis in. Maecenas interdum odio arcu, quis eleifend ante tincidunt nec. Fusce non tristique orci. Vivamus hendrerit viverra risus et porttitor. Nam vel dolor vestibulum libero tincidunt scelerisque id non mi. In rhoncus vitae mi non porta. Cras viverra tellus ut mollis lacinia. Donec imperdiet lacinia blandit.


![img-description](https://cdnb.artstation.com/p/assets/images/images/059/692/109/large/martin-abarca-martin-abarca-dipogun-00.jpg?1676946580)
_Marmoset Toolbag 5 Render_

<!--  Excluded FPV Section

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/392/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/226/martin-abarca-dipogun-vid00.mp4" type="video/mp4"></video>

-->


<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/394/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/228/martin-abarca-dipogun-vid01.mp4" type="video/mp4"></video>

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/400/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/232/martin-abarca-dipogun-vid02.mp4" type="video/mp4"></video>

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" muted="muted" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/404/thumb.jpg" tabindex="-1" preload="auto"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/237/martin-abarca-dipogun-vid03.mp4" type="video/mp4"></video>

<video autoplay="" class="vjs-tech" controlslist="nodownload" id="video_html5_api" width="765" loop="" playsinline="playsinline" poster="https://cdn.artstation.com/p/thumbnails/001/168/405/thumb.jpg" tabindex="-1" preload="auto" muted="muted"><source media="(min-width: 0px)" src="https://cdn.artstation.com/p/video_sources/001/197/239/martin-abarca-dipogun-vid04.mp4" type="video/mp4"></video>

> If you wish to see the full article, you can visit the post by **[Artstation](https://www.artstation.com/artwork/8blvAn)**.
{: .prompt-info }
