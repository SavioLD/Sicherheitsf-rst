# sicherheitsfuerst.de — Redesign-Vorschau

Modernes Redesign der bestehenden Webseite **www.sicherheitsfuerst.de** (Karl-Georg Fürst Metallbau, Rottweil).
Inhalte 1:1 übernommen — Design, Layout, Typografie und Struktur komplett neu.

## Vorschau im Browser

Drei Optionen, um sich das Ergebnis vor dem Kundengespräch anzuschauen:

### 1. htmlpreview.github.io (sofort, ohne Setup)

Diesen Link öffnen — er rendert die HTML-Datei live von GitHub:

```
https://htmlpreview.github.io/?https://github.com/saviold/laendle-digital/blob/claude/sweet-faraday-c0HbR/sicherheitsfuerst/index.html
```

### 2. GitHub Pages (optional, schönere URL)

Im Repo-Setting → Pages → Branch `claude/sweet-faraday-c0HbR`, Folder `/sicherheitsfuerst` auswählen.

### 3. Lokal

```
cd sicherheitsfuerst
python3 -m http.server 8000
# dann http://localhost:8000 öffnen
```

## Inhalte

Alle Inhalte (Adresse, Telefon, E-Mail, Öffnungszeiten, Leistungen, Firmengeschichte, LKA-Registrierung)
sind 1:1 von **sicherheitsfuerst.de** übernommen. Texte können nach dem Kundentermin angepasst werden.

## Tech

Eine einzige `index.html` mit eingebettetem CSS und Vanilla-JS — keine Abhängigkeiten, kein Build,
funktioniert auf jedem Webspace.
