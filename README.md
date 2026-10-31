# Fel-Hexenmeister für Baldur's Gate 3

Eine neue Klasse nach dem Vorbild des Hexenmeisters aus World of Warcraft, gebaut für den Mod
**DnD 5.5e All-in-One BEYOND**. Im Spiel heißt sie **Fel-Hexenmeister** (englisch *Fel Warlock*).

- Drei Spezialisierungen: Gebrechen, Zerstörung, Dämonologie
- Seelensplitter, Flüche, Wichtel, Teufelsjäger, Leerwandler und Sukkubus
- Komplett bis Stufe 20 (für Stufe 13–20 braucht ihr *UnlockLevelCurve*)
- 27 eigene Items, eine kleine Questreihe und zwei Rätsel

**Download:** [Neueste Version unter Releases](https://github.com/Frostmagier/bg3-fel-hexenmeister/releases/latest), dort die Datei `FelWarlock.pak`.

---

## Installieren (Windows)

### 1. Was schon da sein muss

- Baldur's Gate 3 auf dem aktuellen Stand
- **DnD 5.5e All-in-One BEYOND** aus dem Mod-Manager im Spiel, aktiviert

### 2. Datei herunterladen

Unter [Releases](https://github.com/Frostmagier/bg3-fel-hexenmeister/releases/latest) auf `FelWarlock.pak` klicken. Fragt der Browser, ob du die
Datei behalten willst, sag ja. Die Datei ist kein ZIP und muss nicht entpackt werden.

### 3. In den Mods-Ordner legen

1. **Windows-Taste + R** drücken.
2. Das hier einfügen und Enter drücken:
   ```
   %LOCALAPPDATA%\Larian Studios\Baldur's Gate 3\Mods
   ```
   Es öffnet sich der Ordner, in dem auch deine anderen Mods liegen.
3. `FelWarlock.pak` dort hineinkopieren.

Im Ordner darf nur **eine** Fel-Warlock-Datei liegen. Heißt sie zum Beispiel `FelWarlock (1).pak`,
weil eine ältere schon da war: die alte löschen und die neue in `FelWarlock.pak` umbenennen.

### 4. Im Spiel aktivieren

1. Baldur's Gate 3 starten. Lief das Spiel schon, einmal komplett beenden und neu starten.
2. Im Hauptmenü **Mods** öffnen.
3. Bei den installierten Mods **Fel Warlock** suchen und aktivieren. Er wird als Drittanbieter-Mod
   angezeigt, weil er nicht von mod.io kommt. Das ist richtig so.
4. Fel Warlock muss **nach** DnD 5.5e All-in-One BEYOND laden, also in der Liste darunter stehen.
5. In den Mod-Details sollte die Version stehen, die Tim dir genannt hat (zum Beispiel `0.4.0`).

---

## Zusammen spielen

- **Beide** brauchen genau dieselbe Datei in derselben Version, und beide haben Fel Warlock aktiviert.
  Ladet sie beide hier aus demselben Release herunter.
- Wer hostet, aktiviert den Mod, **bevor** der Spielstand geladen wird. Danach tritt der andere bei.
- Erscheint beim Beitreten ein Fenster, dass Mods nicht passen, und Fel Warlock steht darin: Die
  Versionen sind verschieden. Das Spiel kann diesen Mod nicht selbst herunterladen. Beide laden die
  neueste Datei von hier und ersetzen ihre alte.
- Die Klasse bekommt ein neuer Charakter in der Charaktererstellung, oder ein Begleiter beim Umskillen
  bei **Withers**.

### Wichtig für euren Spielstand

Sobald ihr einen Spielstand mit dem Mod gespielt habt, braucht dieser Spielstand den Mod. Ihn später
zu deaktivieren kann den Spielstand kaputtmachen. Der Mod ist neu und ab Stufe 3 noch wenig im Spiel
getestet. Probiert ihn deshalb erst in einem neuen gemeinsamen Spielstand aus, bevor ihr ihn in eure
Honour-Runde holt.

---

## Neu in 0.5

- **Gebrechen wie in WoW Midnight:** Qual erzeugt Splitter, Instabiles Gebrechen (stapelt bis drei) und Saat der Verderbnis
  geben sie aus. Neu sind Dunkle Ernte, Verderbter Makel, Einbruch der Nacht, Splitterinstabilität und ab Stufe 9 ein
  Heldentalent zur Wahl (Höllenrufer oder Seelenernter), das auf 13 und 17 wächst.
- **Alle Stufen bis 20 bringen etwas:** Leerwandler, Sukkubus, drei Flüche, Lebenstrichter, Teufelsrausch, Dämon
  unterwerfen, Grimoire der Opferung und weitere.
- **Fehler behoben:** Die Splitter füllten sich über „Gequälte Seelen“ ständig wieder auf. Der Wichtel lässt seine
  Armbrust nicht mehr fallen.
- **Neue Items** in Akt 1 bis 3, darunter eine Robe und Hörner, die man über zwei Rätsel findet.
- **Mehr Fläche und Kontrolle früh** (nach dem ersten Abend im Honour-Run):
  - Verderbnis und Qual treffen pro Bonusaktion **zwei Ziele**. Für nur ein Ziel nach dem ersten Klick den grünen
    Haken neben der Zielanzeige („1 Target(s)“) drücken.
  - **Saat der Verderbnis ab Stufe 3**, Verderbter Makel ab 5.
  - **Leerwandler ab Stufe 2.**
  - Neu: **Schreckensgeheul** (Stufe 3, Gegner in 6 m fliehen) und **Schattenfuror** (Stufe 5, Gegner in 3 m betäubt),
    je einmal pro Short Rest.
  - **Bösartige Verzückung** zählt jedes Instabile Gebrechen einzeln, macht ab Stufe 5 2W6 pro Effekt (vorher 1W8) und
    trifft auch neutrale Kreaturen, die du belegt hast.
  - **Seelendieb** trifft immer (kein Rettungswurf mehr) und würfelt W10 statt W8.
- **Niemand muss umskillen:** Was auf Stufe 2 bis 5 neu ist, schaltet ein Passiv frei, das jeder Hexenmeister schon hat.
  Ein Charakter auf Stufe 5 hat nach dem Laden sofort alles.

---

## Updates

Wenn Tim eine neue Version hochlädt:

1. Spiel beenden.
2. Neue `FelWarlock.pak` aus [Releases](https://github.com/Frostmagier/bg3-fel-hexenmeister/releases/latest) laden.
3. Die alte Datei im Mods-Ordner damit ersetzen (gleicher Name `FelWarlock.pak`).
4. Spiel starten. Im Mod-Manager steht jetzt die neue Version.

Beide müssen immer auf derselben Version sein.

### Neu in 0.4.2

- **Schriftrollen:** Der Fel-Hexenmeister kann jetzt alle Zauberschriftrollen lesen, die DnD 5.5e einem
  Hexenmeister erlaubt, zum Beispiel Nebelschritt, Hex oder Hypnotisches Muster. Wie beim Hexenmeister
  gilt: Der Grad der Rolle darf höchstens eins über deinem höchsten Zauberplatz liegen. Rollen anderer
  Klassen, etwa Feuerball, bleiben gesperrt.
- Sonst ist alles wie in 0.4.1. Niemand muss umskillen.

---

## Wenn etwas nicht klappt

| Problem | Lösung |
| --- | --- |
| Fel Warlock taucht im Mod-Manager nicht auf | Liegt die Datei im richtigen Ordner (Schritt 3), nicht im Steam-Spielordner? Endet der Name auf `.pak`? Spiel ganz neu starten. |
| Fel Warlock lässt sich nicht aktivieren | Ist DnD 5.5e All-in-One BEYOND installiert und aktiv? |
| Beitreten klappt nicht, Mods passen nicht | Unterschiedliche Versionen. Beide die neueste Datei aus Releases nehmen. |
| Klasse fehlt in der Auswahl | Ist Fel Warlock aktiv? Im Spiel heißt die Klasse **Fel-Hexenmeister**, der normale Warlock heißt nur **Hexenmeister**. |

---

Fanprojekt von Frostmagier, nicht verbunden mit Larian Studios oder Blizzard Entertainment.
