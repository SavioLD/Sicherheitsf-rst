Logo austauschen
================

Wenn du das Original-Logo (PNG/JPG) verwenden möchtest:

1. Datei in diesen Ordner legen, z.B. assets/logo.png
2. In index.html beide <svg class="logo"><use href="#logoFuerst"/></svg>
   ersetzen durch:
   <img class="logo" src="assets/logo.png" alt="Fürst Metallbau" />

Die aktuelle SVG-Variante (logo.svg) wird inline im HTML eingebettet,
damit das Logo bei jeder Größe scharf bleibt und keine externe
Bilddatei geladen werden muss.
