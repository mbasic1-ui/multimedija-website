+++
date = '2026-02-23T17:29:55+01:00'
draft = false
title = 'Zvuk'
+++

U ovom dijelu ću koristiti [audacity](https://www.audacityteam.org/) kako bih normalizirao glasovni zapis, pozadinsku glazbu i iskoristio `ducking` kako glazba ne bi nadglasala moj glas.

### Normalizacija

Normalizacija je proces kojim se glasnoća audio zapisa prilagođava na standardnu razinu kako bi zapis bio konzistentan i ugodan za slušanje.
U Audacityju se normalizacija provodi putem izbornika _Effect > Volume and Compression > Normalize_.

![](/zvuk_prije.png)
![](/zvuk_poslije.png)

### Glazba

Za pozadinsku glazbu sam iskoristio stranicu [pixabay](https://pixabay.com/sound-effects/) koja sadrži veliku kolekciju `royalty-free` glazbe.

### Ducking

Bitno je staviti pozadinsku traku kao prvu na listi s obzirom da nam je zadnja traka `kontrolna traka` te će služiti kao referenca za smanjenje pozadinske glazbe.

Auto Ducking se u Audacityju provodi putem izbornika _Effect > Volume and Compression > Auto Duck_. Efekt automatski analizira kontrolnu traku (glasovni zapis) i svaki put kada detektira zvuk iznad zadanog praga, stišava pozadinsku glazbu.
![](/zvuk_ducking.png)

### Zavrsna obrada

Za kraj je bilo potrebno izvesti audio zapis kao `wav` te ga prenijeti u drugi software za obradu videa.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/sprHcIFnWd8?si=orR4MzinN3U2h0dk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
