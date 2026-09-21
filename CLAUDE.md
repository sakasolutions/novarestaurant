# NOVA – Website-Entwurf für ein echtes Restaurant

Live: https://sakasolutions.github.io/novarestaurant/

## Status: Entwurf für einen echten Kunden

- **Kunde:** NOVA, italienisches Restaurant, Hauptstraße 65, Wunstorf-Luthe (nova-restaurant.de). Echte Daten: Tel. +49 5031 517345, info@nova-restaurant.de, Mi–Mo ab 17 Uhr, Di Ruhetag.
- **Hintergrund:** Die Inhaberin wurde bei ihrer aktuellen Website „abgezogen“ und hat kaum Budget. Der Entwurf wurde ihr am 2026-09-21 geschickt, eine Antwort steht aus. Preis wurde noch nicht genannt.
- **Wichtig:** Diese Seite **nicht öffentlich bewerben** (TikTok/Instagram), solange die Inhaberin nicht zugestimmt hat. Name, Logo und Fotos gehören ihr.
- **Inhalte:** Logo und Fotos stammen von ihrer Website, die Speisekarte aus ihrem PDF (Antipasti, Pasta & Risotto, Pizza, Dolci & Caffè, Aperitivo, Bambini). Die Wein- und Getränkekarte bleibt als Link auf ihr PDF.
- **Farben:** Gold `#b8894d` (aus dem Logo), Espresso `#2a211a`, Creme `#f8f4ee`. Schriften: Cormorant Garamond + Work Sans.
- **Offen:** Die Kundenstimmen sind Platzhalter, hier echte Google-Bewertungen von ihr einsetzen. Beim Hero-Innenraumfoto klären, ob es wirklich ihr Restaurant ist.
- **SEO:** Hier ist **kein** `noindex` gesetzt, weil es ein echter Betrieb ist. Vor einem Go-live Impressum und Datenschutz ergänzen.

## Arbeitsweise (gilt für Mac, Web und Handy)

- **Zu Beginn:** `git pull`, damit du auf dem neuesten Stand bist (es wird von mehreren Geräten aus gearbeitet).
- **Diese Datei ist das gemeinsame Gedächtnis.** Chats werden nicht zwischen Geräten synchronisiert. Wenn eine grundsätzliche Entscheidung getroffen wird (Farben, Stil, Inhalte, Regeln, was der Kunde will oder nicht will), trage sie unten unter **Entscheidungen & Verlauf** mit Datum ein und committe sie zusammen mit der Änderung.
- **Veröffentlichung:** GitHub Pages aus Branch `main`, Ordner `/ (root)`. Alles, was auf `main` landet, ist nach ein bis zwei Minuten live.
- **Aufbau:** eine einzige `index.html` mit Inline-CSS und -JS, Bilder in `img/`. Kein Framework, kein Build-Schritt.
- **Alle Farben** stehen als CSS-Variablen in `:root`. Neue Farben nur dort anlegen.

## Stil-Regeln des Inhabers (Sinan, SAKA Solutions)

- **Ruhig und seriös statt verspielt.** Keine Laufbänder/Ticker, keine schwebenden oder wippenden Elemente, keine Hover-Effekte mit Anheben/Zoomen, keine dekorativen „Chips“ um Personen herum. Erlaubt: dezente Farbübergänge, Aufklappen von FAQ/Menü/Reitern.
- **Farben nie selbst erfinden:** immer aus einer Vorlage (Dribbble-Shot) oder aus bestehenden Markenfarben ableiten. Abgelehnt wurden z. B. Dunkelgrün + Senfgelb und erdig-matte Kombinationen.
- **Personen im Hero:** sauber angeordnet (zentriert, nichts über dem Gesicht, Kopf unter der Navigation). Lieber weglassen als verspielt.
- **Keine erfundenen Bewertungen** als echt ausgeben: Bewertungen sind als „Beispielbewertung“ markiert, keine vollen Namen.
- **Handy zuerst prüfen:** Bei 375 px darf nichts breiter als der Bildschirm sein (`document.documentElement.scrollWidth === innerWidth`). Grid-Spalten mit `minmax(0,1fr)` statt `1fr`, wenn darin scrollende Leisten stecken.
- **Navigation** bleibt am Desktop (1200–1440 px) einzeilig (`white-space: nowrap`).
- **Sprache:** Deutsch, echte Texte, kein Lorem ipsum.

## SEO-Standard

`lang="de"`, Title ca. 55–60 Zeichen mit Leistung + Ort, Meta-Description ca. 150 Zeichen, Canonical, Open Graph, genau eine H1 mit Keyword + Ort, saubere H2/H3, Alt-Texte, width/height an Bildern, `loading="lazy"` unterhalb des sichtbaren Bereichs, JSON-LD passend zur Branche (plus FAQPage, wenn es eine FAQ gibt).

## Entscheidungen & Verlauf

- 2026-09-21: Entwurf erstellt und an die Inhaberin geschickt.
