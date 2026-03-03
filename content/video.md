+++
date = '2026-02-23T17:30:01+01:00'
draft = false
title = 'Video'
+++

U ovom projektu koristio sam [Kdenlive](https://kdenlive.org/), besplatni softver otvorenog koda za obradu videa. Video je snimljen putem [OBS-a](https://obsproject.com/) (Open Broadcaster Software), besplatnog alata za snimanje zaslona.

## Ideja

Na kolegiju programiranja dobili smo zadatke za vježbu, te sam odlučio snimiti rješavanje i objašnjenje zadataka. Video je sniman u kontinuitetu te ga je bilo potrebno obraditi na način da se određeni segmenti (priprema zadataka, dugotrajne implementacije) izrežu kako bi se dobio efekt fluidnosti i preglednosti.

## Postupak

### Audio

Prvo je bilo potrebno normalizirati audio kako bih dobio jednaku, standardnu razinu zvuka. Napravio sam to tako što sam označio videoklip te odabrao opciju **Ungroup Clips**, a zatim klikom na audio traku odabrao **Save part clip to bin**. Audio klip smjestio sam u projektnu mapu te ga u Audacityju normalizirao i vratio na audio traku u Timeline-u.

![](/video_1.png)

### Speech to text

Kdenlive ima moćnu opciju **Speech Editor** koja putem lokalnog AI modela može izvući tekst iz audio datoteke. Koristio sam [Whisper](https://github.com/openai/whisper) Turbo model s obzirom da ima podršku za Hrvatski jezik. Funkciju sam iskoristio jer sam tijekom snimanja govorio određene ključne riječi poput `STOP`, `PONOVO` i `PAUZA`, kako bih na sekvencijskoj traci lakše pronašao željeni trenutak u vremenu.

![](/video_2.png)

### Rezanje (Cut)

Nakon što sam imao vremenske oznake iz transkripta, uzeo sam alat škare koji se nalazi na Timeline-u te izrezao nepotrebne dijelove videa.

![](/video_3.png)

## Završna obrada

Video je izvezen i objavljen na YouTubeu s vremenskim oznakama (chapters) koje označavaju gdje se nalazi pojedini zadatak, kako bi studenti lako mogli prijeći na zadatak koji ih zanima.

<iframe width="560" height="315" src="https://www.youtube.com/embed/0vDPfBkd8k4?si=dUsRkdcoHBifS08g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/z8Claoj07ko?si=-uo09xhCsoReVme6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/8RV5R3kYRvQ?si=d0nN2Lvm7clsEBsa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/i9LYntcn-20?si=crvOcgawvUrxsLJE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/WcEA2aNeF8o?si=URHRMRogqj7qCKxE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
