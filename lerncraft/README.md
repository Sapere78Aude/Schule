# ⛏️ LernCraft – Deutschland-Lernspiel

Ein komplettes, **offline spielbares** HTML-Lernspiel im Minecraft-Look – gemacht für die Klassenarbeit **„Deutschland" am 26.11.2026** (4. Klasse, Hamburg).

## Dateien

- `index.html` – das komplette Spiel in **einer einzigen Datei** (kein Internet, keine Installation, keine externen Dateien nötig)

## So kommt das Spiel aufs Handy

1. Die Datei `index.html` vom Computer aufs Handy übertragen, z. B. per
   - **WhatsApp** (an sich selbst senden),
   - **E-Mail** (als Anhang) oder
   - **USB-Kabel** (in den Download- oder Dokumente-Ordner kopieren).
2. Auf dem Handy die Datei antippen und mit **Chrome** öffnen
   („Öffnen mit" → **Chrome** wählen, falls ein anderer Browser vorgeschlagen wird).
3. Optional als App auf den Startbildschirm legen:
   Chrome-Menü (⋮) → **„Zum Startbildschirm hinzufügen"** → Name bestätigen.
   Danach startet LernCraft wie eine richtige App – auch **offline**.

## Spielmodi

| Modus | Beschreibung |
|---|---|
| ⏱️ 5-Minuten-Runde | So viele Fragen wie möglich in 5 Minuten (Rekord wird gespeichert) |
| 🔥 10-Minuten-Challenge | Ganze 10 Minuten – Rekord knacken! |
| 🎯 Alle Themen (Endlos) | Endlos-Quiz über alle Themen |
| 🧠 Themen-Buttons | Nur ein Thema üben: Bundesländer, Nachbarländer, Städte, Flüsse, Gebirge, Fakten |
| 👾 Bosskampf: Enderdrache | Der Boss hat 100 HP – jede richtige Antwort macht 20 Schaden. Sieg = +150 XP! |
| 📖 Spickzettel | Alle Fakten auf einen Blick |

## Regeln & Gamification

- **Richtig** = +10 XP (ab Combo ×3 zusätzlich +5 Bonus-XP)
- **Falsch** = 1 Herz weg (3 Herzen pro Runde); die richtige Antwort + Erklärung wird angezeigt, und die falsche Frage kommt **später noch einmal** dran
- **Level** mit Minecraft-Mob-Namen: Schleim → Zombie → Skelett → Spinne → Creeper → Enderman → Ghast → Wither → **Enderdrache**
- **Tägliche Serie** mit +25 XP Tagesbonus fürs tägliche Spielen
- **Countdown** „Tage bis 26.11.2026" im Header
- Fortschritt (XP, Level, Serie, Rekorde, Boss-Kills) wird lokal im Browser gespeichert (`localStorage`)
- Sounds (WebAudio) und Vibration auf dem Handy, alles auf Deutsch, große Touch-Buttons
- Minecraft-Look komplett per reinem CSS (Creeper-Kopf, Grasblock, XP-Leiste)

## Prüfungsstoff (alles als Quizfragen enthalten)

- 16 Bundesländer + Hauptstädte (in beide Richtungen gefragt)
- 9 Nachbarländer Deutschlands (inkl. „5 nennen"-Frage)
- 6 größte Städte: Berlin, Hamburg, München, Köln, Frankfurt am Main, Stuttgart
- Flüsse: Rhein (längster in DE, → Nordsee), Elbe (durch Hamburg, → Nordsee bei Cuxhaven), Donau (entspringt im Schwarzwald, → Schwarzes Meer), Main (→ Rhein bei Mainz)
- Gebirge: Alpen, Schwarzwald, Erzgebirge, Harz
- Höchster Berg: Zugspitze, 2.962 m, in den Alpen (Bayern)
- Hauptstadt Berlin · ca. 84 Mio. Einwohner · Flagge schwarz–rot–gold (von oben)

## Technik

- Reines HTML/CSS/JS in einer Datei, kein Build-Schritt
- Funktioniert in Chrome (Android) auch über `file://` inklusive `localStorage`
- WebAudio-Sounds werden beim ersten Antippen freigeschaltet (Browser-Regel)
