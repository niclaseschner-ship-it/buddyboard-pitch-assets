# Pitch-Bilder — Gamma-URL-Mapping

Raw-URLs aller Bilder mit Kurzbeschreibung. URL → in Gamma per *Bild von URL* einsetzen.

**Base-URL:** `https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master`

**Hinweis zur Wiederverwendung:** Viele Slide-Icons (geometrische Spielfiguren) sind in mehreren Slides eingebettet. Sie sind unten unter [Spielfiguren-Symbole](#spielfiguren-symbole-wiederverwendet) gebündelt — die Slide-Sektionen verweisen darauf, statt sie zu duplizieren.

---

## Originale (hochauflösend)

| Bild | Inhalt | URL |
|---|---|---|
| `prototyp.png` | **Foto:** Echter BuddyBoard-Prototyp an der Wand, zeigt PlanBuddy-Wochenplan, davor orange NFC-Spielfigur (Fuchs-Form) | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/originals/prototyp.png |
| `rendering-buddyboard.png` | **3D-Rendering:** BuddyBoard im hellen Holzrahmen mit Logo-Screen ("BuddyBoard" + Hügel-Hintergrund), grüner Kegel als Spielfigur | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/originals/rendering-buddyboard.png |
| `geometrische-formen.png` | 8 pastellfarbene Spielzeug-Geometrieformen (Kugel, Kegel, Zylinder, Würfel, Pyramide, abgerundeter Würfel, Ikosaeder, Dodekaeder) — Spielfiguren-Set | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/originals/geometrische-formen.png |
| `uk-beispiel.png` | **Foto:** Analoge Vorbild-Magnetwand mit Wochentagen Mo–Fr, bunten Holzklötzchen und kleinen Foto-Buttons (UK = Unterstützte Kommunikation) | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/originals/uk-beispiel.png |
| `screenshot-board.png` | **App-Screenshot:** AdminBuddy-Backlog — Raster aus Bug-/Feature-Tickets mit Status-Filter | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/originals/screenshot-board.png |
| `screenshot-ticket.png` | **App-Screenshot:** AdminBuddy-Ticket-Detail (FEAT-2026-0047 „PlanBuddy wichenplan…") mit Notizen + System-Log | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/originals/screenshot-ticket.png |
| `screenshot-2026-04-30.png` | **Negativbeispiel-Foto:** Blaues Amazon Fire Kids Tablet mit App-Raster (Frozen, Disney+, My Little Pony, Pete the Cat) | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/originals/screenshot-2026-04-30.png |

### Cover

| Bild | Inhalt | URL |
|---|---|---|
| `covers/cover.jpeg` | BuddyBoard-Cover-Mockup von vorne — Buddy-Avatar-Logo, Tagline „Dein Tag. Deine Buddys. Dein Plan." + 5 Icons, Holzfigur seitlich an der Front | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/originals/covers/cover.jpeg |
| `covers/master-img-2.jpeg` | Selbe Cover-Variante als 3D-Schrägansicht (etwas weicheres Render) | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/originals/covers/master-img-2.jpeg |
| `covers/master-img-4.jpeg` | **Foto:** Echter BuddyBoard mit PlanBuddy-Wochenplan, orange NFC-Fuchs-Figur davor, weitere Spielfiguren am unteren Rand | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/originals/covers/master-img-4.jpeg |

---

## Spielfiguren-Symbole (wiederverwendet)

Pastellfarbene 3D-Geometrieformen, einzeln freigestellt — vermutlich aus `geometrische-formen.png` zerlegt. Werden quer über die Decoration-Slides (s1-cover, s3-loesung, s5-prototyp, s8-business-model, s12-close) immer wieder eingestreut. Pro Form ist nur **eine** kanonische URL nötig — die anderen Vorkommen sind byteidentisch.

| Form | Beschreibung | Kanonische URL | Weitere Vorkommen (selbe Bytes) |
|---|---|---|---|
| 🟦 Blaue Kugel | Hellblaue, matte Pastellkugel | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s12-close_img_1.png | `s1-cover_img_2.png`, `s3-loesung_img_3.png`, `s8-business-model_img_1.png` |
| 🟢 Grüner Kegel | Hellgrüner Pastellkegel | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s12-close_img_2.png | `s3-loesung_img_4.png`, `s5-prototyp_img_2.png`, `s8-business-model_img_2.png` |
| 🟫 Beiger Würfel | Sandfarbener, kantiger Würfel | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s12-close_img_3.png | `s3-loesung_img_5.png`, `s3-loesung_img_7.png`, `s8-business-model_img_3.png` |
| 🟡 Gelber Zylinder | Senf-/dottergelber Zylinder | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s12-close_img_4.png | `s5-prototyp_img_3.png`, `s8-business-model_img_4.png` |
| 🟪 Lila Pyramide | Flieder-/lavendelfarbene Tetraeder-Pyramide | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s12-close_img_5.png | `s8-business-model_img_5.png` |
| 💎 Blaues Ikosaeder | Stahlblaue, facettierte Form | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s12-close_img_6.png | `s5-prototyp_img_4.png` |
| 🟩 Mintgrüner Kissenwürfel | Mintfarbene, weich abgerundete Würfelform | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s12-close_img_7.png | (nur hier) |
| 🟧 Oranges Dodekaeder | Terrakotta-orangenes 12-Flächen-Polyeder | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s12-close_img_8.png | `s3-loesung_img_1.png`, `s3-loesung_img_2.png`, `s3-loesung_img_6.png` |

---

## Aus HTML-Slides extrahiert (pro Slide)

### s1-cover — Cover

| Bild | Inhalt | URL |
|---|---|---|
| `s1-cover_img_1.jpg` | BuddyBoard-Cover-Mockup ähnlich `originals/covers/`, Logo-Screen + grüner Kegel-Spielfigur davor — **identisch zu** `s13-device-render_img_1.jpg` | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s1-cover_img_1.jpg |
| `s1-cover_img_2.png` | Spielfigur **🟦 Blaue Kugel** (siehe oben) | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s1-cover_img_2.png |

### s3-loesung — Lösung

Sieben Spielfiguren-Icons als Decoration. Jeweils eine Form aus dem Set oben:

| Bild | Inhalt | URL |
|---|---|---|
| `s3-loesung_img_1.png` | 🟧 Oranges Dodekaeder | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s3-loesung_img_1.png |
| `s3-loesung_img_2.png` | 🟧 Oranges Dodekaeder | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s3-loesung_img_2.png |
| `s3-loesung_img_3.png` | 🟦 Blaue Kugel | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s3-loesung_img_3.png |
| `s3-loesung_img_4.png` | 🟢 Grüner Kegel | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s3-loesung_img_4.png |
| `s3-loesung_img_5.png` | 🟫 Beiger Würfel | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s3-loesung_img_5.png |
| `s3-loesung_img_6.png` | 🟧 Oranges Dodekaeder | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s3-loesung_img_6.png |
| `s3-loesung_img_7.png` | 🟫 Beiger Würfel | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s3-loesung_img_7.png |

### s5-prototyp — Prototyp live

| Bild | Inhalt | URL |
|---|---|---|
| `s5-prototyp_img_1.png` | **Foto:** BuddyBoard im Holzrahmen mit PlanBuddy-Wochenplan, davor orange NFC-Fuchs-Figur (= `originals/prototyp.png`) | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s5-prototyp_img_1.png |
| `s5-prototyp_img_2.png` | 🟢 Grüner Kegel | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s5-prototyp_img_2.png |
| `s5-prototyp_img_3.png` | 🟡 Gelber Zylinder | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s5-prototyp_img_3.png |
| `s5-prototyp_img_4.png` | 💎 Blaues Ikosaeder | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s5-prototyp_img_4.png |
| `s5-prototyp_img_5.png` | **App-Screenshot PlanBuddy:** „Guten Morgen, Paula!" Morgen-Routine — Aufstehen, Anziehen, Pippi, Frühstücken, Vesper, Zähne putzen — rechts großer 0:00-Timer | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s5-prototyp_img_5.png |
| `s5-prototyp_img_6.png` | Identisch zu `s5-prototyp_img_5.png` | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s5-prototyp_img_6.png |
| `s5-prototyp_img_7.jpg` | **App-Screenshot Wetter:** „BuddyBoard · Wetter, Freiburg" — Temperatur-/Wind-/Wetter-/Regen-Slider links, Outfit-Empfehlung pro Tageszeit (Langarmshirt, Pullover, T-Shirt …) rechts | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s5-prototyp_img_7.jpg |
| `s5-prototyp_img_8.jpg` | Identisch zu `s5-prototyp_img_7.jpg` | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s5-prototyp_img_8.jpg |
| `s5-prototyp_img_9.jpg` | **App-Screenshot KIBuddy:** Roboter-Avatar zentriert, „→ Zum Sprechen ziehen"-Mikrofon-Button unten | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s5-prototyp_img_9.jpg |
| `s5-prototyp_img_10.jpg` | Identisch zu `s5-prototyp_img_9.jpg` (KIBuddy) | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s5-prototyp_img_10.jpg |

### s8-business-model — Business Model

Ausschließlich Spielfiguren-Decoration:

| Bild | Inhalt | URL |
|---|---|---|
| `s8-business-model_img_1.png` | 🟦 Blaue Kugel | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s8-business-model_img_1.png |
| `s8-business-model_img_2.png` | 🟢 Grüner Kegel | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s8-business-model_img_2.png |
| `s8-business-model_img_3.png` | 🟫 Beiger Würfel | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s8-business-model_img_3.png |
| `s8-business-model_img_4.png` | 🟡 Gelber Zylinder | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s8-business-model_img_4.png |
| `s8-business-model_img_5.png` | 🟪 Lila Pyramide | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s8-business-model_img_5.png |

### s12-close — Close

Komplettes Spielfiguren-Set als Decoration (alle 8 Formen, Quelle der „kanonischen URLs" oben):

| Bild | Inhalt | URL |
|---|---|---|
| `s12-close_img_1.png` | 🟦 Blaue Kugel | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s12-close_img_1.png |
| `s12-close_img_2.png` | 🟢 Grüner Kegel | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s12-close_img_2.png |
| `s12-close_img_3.png` | 🟫 Beiger Würfel | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s12-close_img_3.png |
| `s12-close_img_4.png` | 🟡 Gelber Zylinder | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s12-close_img_4.png |
| `s12-close_img_5.png` | 🟪 Lila Pyramide | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s12-close_img_5.png |
| `s12-close_img_6.png` | 💎 Blaues Ikosaeder | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s12-close_img_6.png |
| `s12-close_img_7.png` | 🟩 Mintgrüner Kissenwürfel | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s12-close_img_7.png |
| `s12-close_img_8.png` | 🟧 Oranges Dodekaeder | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s12-close_img_8.png |

### s13-device-render — Device Render (Appendix)

| Bild | Inhalt | URL |
|---|---|---|
| `s13-device-render_img_1.jpg` | BuddyBoard-Cover-Mockup, Holzrahmen + Logo-Screen + grüner Kegel-Spielfigur (identisch zu `s1-cover_img_1.jpg`) | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/s13-device-render_img_1.jpg |

### sc-screenshots — Screenshots (Appendix)

App-Galerie — wichtigste Quelle für „echte Produkt-Screens":

| Bild | Inhalt | URL |
|---|---|---|
| `sc-screenshots_img_1.jpg` | **PlanBuddy Wochenansicht:** 7 Tage als Spalten, Bringen/Holen-Slots mit Familienmitgliedern (Niclas, Vera, Sophia, Julian), Events „Capoeira"/„Klettern", Tagesablauf-Balken, Abendessen, Bett-Zeit | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/sc-screenshots_img_1.jpg |
| `sc-screenshots_img_2.jpg` | **PlanBuddy Profilauswahl:** „Guten Morgen!" — zwei runde Profile (Paula, Neko) | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/sc-screenshots_img_2.jpg |
| `sc-screenshots_img_3.jpg` | **PlanBuddy „Gute Nacht!"-Routine:** 5 Karten — Pyjama, Zähne putzen, Aufräumen, Buch lesen, Licht aus | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/sc-screenshots_img_3.jpg |
| `sc-screenshots_img_4.jpg` | Wetter-Screen (= `s5-prototyp_img_7.jpg`) | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/sc-screenshots_img_4.jpg |
| `sc-screenshots_img_5.jpg` | **Wetter 7-Tage-Vorhersage:** Spalten Heute/Do–Di mit Wetter-Icon + Temperatur-Slider | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/sc-screenshots_img_5.jpg |
| `sc-screenshots_img_6.jpg` | **Regenradar:** OpenStreetMap-Karte Region Freiburg/Schwarzwald, rechts „Wahrscheinlichkeit 0%, Niederschlag 0 mm" | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/sc-screenshots_img_6.jpg |
| `sc-screenshots_img_7.jpg` | KIBuddy Sprach-Interface (= `s5-prototyp_img_9.jpg`) | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/sc-screenshots_img_7.jpg |
| `sc-screenshots_img_8.jpg` | **ShopBuddy:** Leere Einkaufsliste rechts, „Tippe Produkte an um sie hinzuzufügen", Buttons „Einkauf abschließen / Liste leeren" | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/sc-screenshots_img_8.jpg |
| `sc-screenshots_img_9.jpg` | **KinoBuddy:** Dunkles UI, „Die Sendung mit dem Elefanten" (3 Folgen), Einzelfolgen „Die Maus"/„Cat Videos 2025" | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/sc-screenshots_img_9.jpg |
| `sc-screenshots_img_10.jpg` | **PhotoBuddy:** Vollbild-Foto „Niclas" (25. Apr.) — zwei Personen auf einem großen Felsen im Wald | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/sc-screenshots_img_10.jpg |
| `sc-screenshots_img_11.jpg` | **AdminBuddy Backlog-Screen:** Karten-Raster mit FEAT-/BUG-Tickets, Status-Filter oben (= `originals/screenshot-board.png` thematisch, anderes Frame) | https://raw.githubusercontent.com/niclaseschner-ship-it/buddyboard-pitch-assets/master/slides/sc-screenshots_img_11.jpg |
