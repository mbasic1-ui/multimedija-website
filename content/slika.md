+++
date = '2026-02-23T17:29:46+01:00'
draft = false
title = 'Slika'
+++

U ovom projektu koristio sam [GIMP](https://www.gimp.org) za obradu fotografije. Na fotografiji sam primijenio sepia efekt te dodao watermark kao oznaku autorstva.

Originalna fotografija:

![](/slika.jpg)

---

## Sepia efekt

### Postupak

Fotografiju smo pretvorili u crno-bijelu pomoću `Colors → Desaturate → Desaturate`, odabirom opcije **Luminance**.

![](/slika_1.png)

Sepia ton dodali smo putem `Colors → Hue-Saturation...`, gdje smo postavili **Hue** na `35`, **Saturation** na `50`, **Lightness** na `5`.

![](/slika_2.png)

---

## Watermark

### Postupak

Alatom **Text** dodali smo tekstualni sloj s imenom. Odabrali smo odgovarajući font i veličinu.

![](/slika_3.png)

![](/slika_4.png)

U panelu **Layers** smanjili smo **Opacity** tekstualnog sloja na `50%` kako bi watermark bio vidljiv, ali nenametljiv. Zatim smo spojili slojeve putem `Image → Flatten Image` i fotografiju izvezli kao `File → Export As...`.

---

## Završna obrada

Fotografija obrađena sepia efektom i označena watermarkom:

![](/slika_rezultat.jpeg)
