# Media-assets

## Hero-achtergrondfoto

De header (hero) gebruikt een full-bleed achtergrondfoto op dit pad:

    assets/hero.jpg

Plaats hier de gewenste foto onder exact die naam (`hero.jpg`). De foto wordt
automatisch:

- full-bleed getoond achter het "GLOW"-woordmerk;
- getint in het neon paars/blauw (duotone) zodat hij bij de huisstijl past;
- links en onderaan verdonkerd (scrim) zodat de tekst leesbaar blijft.

Aanbevolen: liggend, minimaal ~1600px breed. Een zwart-witfoto werkt het mooist
met de duotone-tint. Wil je een andere uitsnede op mobiel? Pas
`.hero-photo{background-position:…}` aan in `index.html`.

Ontbreekt het bestand, dan valt de hero netjes terug op de neon-gradient.
