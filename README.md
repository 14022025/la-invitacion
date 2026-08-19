# Invitación · Taller de flores y cena de rebranding

Página de invitación para el evento de Thallo Digital del viernes 28 de agosto
de 2026, 5:00 pm, en Botero's Café.

Quien la abre escribe su nombre, elige uno de los tres platos fuertes y al
confirmar se le abre WhatsApp con el mensaje ya redactado hacia Cami. El
invitado todavía tiene que apretar enviar en WhatsApp: hasta ahí no llega la
confirmación.

## Qué hay acá

```
index.html          la página entera — estructura, estilos y lógica en un archivo
img/hero.jpg        foto de fondo del encabezado y del pie
img/flor.png        isotipo de Thallo
img/plato-*.jpg     fotos de los tres platos
img/preview.jpg     imagen que se ve al compartir el enlace
```

## Cosas que se cambian a mano

**El número de WhatsApp** está al final de `index.html`, en la constante
`WHATSAPP`, en formato internacional y sólo dígitos. Si queda con un valor que
no sean 8 a 15 dígitos, la página se frena y avisa en vez de mandar a nadie a
un chat equivocado.

**La imagen de vista previa** (`og:image`) tiene que ser una URL absoluta para
que WhatsApp y Facebook la muestren; una ruta relativa no les sirve.

## Diseño

Es la réplica en HTML del diseño de Canva "Invitación evento Thallo Digital"
(lienzo de 800 × 1782). Entre 800 y 1099px de ancho la página coincide con ese
lienzo; en pantallas más grandes se ensancha a 1120px y los tres platos pasan a
una fila, sin cambiar ningún tamaño de letra. Debajo de 800px se reordena en
una columna.

Las tipografías son las tres del archivo de Canva —Inter, Space Mono e
Instrument Serif— y se cargan desde Google Fonts. Ojo que **no** son Satoshi,
la tipografía del manual de marca de Thallo.
