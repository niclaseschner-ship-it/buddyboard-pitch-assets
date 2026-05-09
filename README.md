# buddyboard-pitch-assets

Original-Bilder für das BuddyBoard-Pitch-Deck, gehostet als Raw-URLs für die
Übergabe an [Gamma](https://gamma.app).

**Quell-Repo:** [buddyboard-knowledge](https://github.com/niclaseschner-ship-it/buddyboard-knowledge)
(privat) — `buddyboard/pitch/`. Workflow-Doku siehe dort
([pitch/CLAUDE.md](https://github.com/niclaseschner-ship-it/buddyboard-knowledge/blob/master/buddyboard/pitch/CLAUDE.md)).

## Verzeichnisstruktur

| Pfad | Inhalt |
|---|---|
| `originals/` | Hi-Res-Originale (Prototyp-Foto, Rendering, Screenshots, Diagramme) |
| `originals/covers/` | Cover-Master-Bilder |
| `slides/` | Aus den HTML-Slides extrahierte Bilder (Naming: `<slide_id>_img_<n>.<ext>`) |

## Verwendung in Gamma

1. Hauptdeck oder Appendix in Gamma generieren (siehe Pitch-Workflow im Quell-Repo).
2. Beim Bild-Auswahl-Dialog statt KI-generiertem Bild **"Bild von URL"** wählen.
3. URL aus [`IMAGE_URLS.md`](IMAGE_URLS.md) für die jeweilige Slide kopieren.

Raw-URL-Schema:

```
https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/<pfad>
```

## Aktualisieren

Bilder werden lokal in `buddyboard-knowledge/buddyboard/pitch/` gepflegt
(SSoT). Wenn sich dort etwas ändert: hier neu kopieren, committen, pushen.
Filename-Konsistenz beachten — sonst brechen die URLs in
ggf. schon befüllten Gamma-Decks.
