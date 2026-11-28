# Fel-Hexenmeister für Baldur's Gate 3

Eine neue Klasse nach dem Vorbild des Hexenmeisters aus World of Warcraft, gebaut für den Mod
**DnD 5.5e All-in-One BEYOND**. Im Spiel heißt sie **Fel-Hexenmeister** (englisch *Fel Warlock*).

- Drei Spezialisierungen: Gebrechen, Zerstörung, Dämonologie
- Seelensplitter, Flüche, Wichtel, Teufelsjäger, Leerwandler und Sukkubus
- Komplett bis Stufe 20 (für Stufe 13–20 braucht ihr *UnlockLevelCurve*)
- 49 eigene Items, eine kleine Questreihe und zwei Rätsel
- Talentreihen wie in WoW: auf vielen Stufen eins aus drei Talenten

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
5. In den Mod-Details sollte die Version stehen, die Tim dir genannt hat (zum Beispiel `0.7.1`).

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

## Neu in 0.7.1

Beide brauchen wieder genau diese Version. Niemand muss umskillen.

- **Neues Set „Schwarzes Banner“ für Gebrechen im Nahkampf:**
  - **Nachtklinge** (Katana, sehr selten): Deine Waffentreffer legen Qual (falls das Ziel sie noch nicht hat) und frischen
    die Verderbnis auf. Dazu +1W6 nekrotisch für jeden deiner Effekte auf dem Ziel (Qual, Verderbnis, Instabiles
    Gebrechen). Gibt den Fernangriff **Nachtschnitt**: eine Sichel aus Dunkelheit bis 18 m, Zaubertrick-Würfel W8, legt bei
    Treffer Verderbnis.
  - **Mantel des Schwarzen Banners** (Robe, RK 12): Einmal pro Zug ein Seelensplitter, wenn deine Waffe ein Ziel mit
    deiner Qual trifft. Zusammen mit der Nachtklinge gibt es **Nachtschnitt (Schwarzes Banner)** einmal pro Zug als
    Bonusaktion.
  - **So kommst du dran:** Jeder Fel-Hexenmeister hat den Zauber **Schwarzes Banner rufen** (Leiste, Reiter Fel Warlock).
    Einmal wirken, dann liegen beide Teile im Inventar. Geht nur ein einziges Mal. Zusätzlich gibt es beides bei Arron
    (Akt 1), Talli (Akt 2) und Helsik (Akt 3).
  - Nachtschnitt steht in der Leiste unter **Common**. Die Bonusaktions-Fassung landet nicht immer von selbst in der
    Leiste: Zauberbuch (K), Reiter Common, nach „Night“ suchen und in die Leiste ziehen.
- Im Spiel geprüft: Rufen legt beide Teile ins Inventar, Katana-Modell, Treffer +5, Nahkampftreffer mit Zusatzschaden und
  Verderbnis, Nachtschnitt 12 Schaden mit Verderbnis, die Bonusaktions-Fassung lässt sich wirken. Außerdem jetzt geprüft:
  Qual und Verderbnis treffen mit echter Stufenbedingung 4 Ziele.

## Neu in 0.7

Beide brauchen wieder genau diese Version. Niemand muss umskillen, laufende Spielstände bekommen alles beim Laden.

- **Gebrechen räumt Gruppen ab, wie in WoW:**
  - Qual und Verderbnis treffen ab Stufe 5 drei Ziele, ab Stufe 9 vier. Talente geben eins mehr obendrauf.
  - Neu ab Stufe 5: **Qual und Verderbnis** als ein Zauber. Eine Bonusaktion legt beide auf alle Ziele.
  - Die Explosion der Saat verteilt ab Stufe 5 auch Verderbnis.
  - **Verderbter Makel** macht jetzt sofort 2W6 nekrotisch an allen Gegnern im Umkreis (Konstitution halbiert), ab Stufe 9 3W6.
  - **Seuchenträger** (Talent auf Stufe 7) neu: Stirbt ein Gegner mit deiner Qual, springen Qual und Verderbnis auf alle
    Gegner in 4 m.
- **Mehr Schaden ab Stufe 9:** Instabiles Gebrechen und Bösartige Verzückung 2W8, Dunkle Ernte 1W8 (bisher erst ab 11).
- **Instabiles Gebrechen** macht auf Stufe 3 und 4 1W6 statt 2W6. Früh war es zu stark.
- **Einbruch der Nacht** löst mit 25 % statt 15 % aus.
- **Fehler behoben, wichtig für euren Lauf:** Gequälte Seelen und Einbruch der Nacht haben seit 0.5 nie ausgelöst, weil
  das Spiel DoT-Ticks anders kennzeichnet als gedacht. Jetzt bringen die Ticks deiner Dauerschäden auf Zielen mit Qual
  wirklich Seelensplitter, und Einbruch der Nacht kommt. Im Spiel geprüft.
- **Qual und Verderbnis** lässt eine laufende Qual auf ihrer Stufe, sie wächst also weiter, wenn du nur die Verderbnis
  auffrischst. Wer die Qual neu starten will, nimmt den einzelnen Zauber Qual.
- Im Spiel geprüft: alles oben, dazu Dunkle Ernte, Verzückung, Furcht, Schreckensgeheul, Schattenfuror, Gesundheitsstein,
  Unendliche Entschlossenheit, Sukkubus, Lebenstrichter, Teleport und Dämonenhaut. **Noch nicht geprüft:** die Talente auf
  Stufe 7 und 10 außer Seuchenträger.

## Neu in 0.6.1

- Zufallseffekte würfeln jetzt wirklich: **Seelenleitung** gab bisher jeden ausgegebenen Seelensplitter zurück, jetzt mit 20 %.
  Dasselbe gilt für Gequälte Seelen, Seelenflut, Einbruch der Nacht, Splitterinstabilität, Ausmerzen der Schwachen, Glut,
  Feuersbrunst, Dämonischer Ruf und die Splitter-Chancen von Laterne und Grimoire.
- Spielstände laufen ohne Umskillen weiter. Beide brauchen wieder genau diese Version.

## Neu in 0.6

**Wichtig vor dem Spielen:** Beide brauchen genau diese Version. Wer schon über Stufe 2 ist, bekommt die Talente der
erreichten Stufen erst nach einmal Umskillen bei **Withers** (100 Gold). Ohne Umskillen geht alles weiter, die Talente kommen
dann ab dem nächsten Aufstieg.

- **Talentreihen wie in WoW:** Beim Aufstieg wählst du eins aus drei Talenten (nicht zu verwechseln mit den D&D-Talenten
  auf 4, 8, 12).
  - Für alle Hexenmeister auf Stufe 2, 6 und 10: zum Beispiel mehr Trefferpunkte, Übung in leichter Rüstung, ein
    stärkerer Gesundheitsstein, stärkere Dämonen oder Schattenfuror mit 5 m.
  - Gebrechen auf 3, 5, 7 und 11: mehr Ziele für Qual und Verderbnis, eine größere Saat, mehr Splitter, Lebensentzug,
    Qual startet höher, eine Gratis-Saat zum Kampfbeginn.
  - Zerstörung und Dämonologie haben je eigene Reihen auf 3, 5, 7 und 11.
- **Saat der Verderbnis als Kombo:** Die Saat macht beim Setzen keinen Schaden mehr. Leg danach **Qual** auf das Ziel,
  dann platzt die Saat: 2W6 nekrotisch an jedem Gegner im Umkreis von 4 m (Konstitution halbiert), und alle bekommen Qual.
  Liegen weitere Saaten in Reichweite, platzen sie mit. Stirbt der Träger, platzt sie ebenfalls.
- **Leiste aufgeräumt:** Die Dämonen stecken in einem Zauber **Dämon beschwören**, die Flüche in **Flüche**. Klick
  darauf und wähl aus der Liste. Fehlen sie in deiner Leiste, zieh sie aus dem Zauberbuch (Taste K) hinein.
- **Gesundheitsstein** herstellen geht jetzt einmal pro **Short Rest**.
- **Schattenfuror** ab Stufe 5, **Schreckensgeheul** ab Stufe 9, jetzt auf Entfernung: Furcht im Umkreis von 6 m mit
  Weisheitsrettungswurf.
- **Beschwörungsritual neu, wie in WoW:** Du rufst einen Verbündeten, auch über sein Porträt. Er wählt „Dem Ruf folgen“
  (er tritt zu dir) oder „Ruf ablehnen“. Du kannst „Ritual abbrechen“. Nur außerhalb des Kampfes.
- **22 neue Gegenstände** in allen drei Akten, darunter Dolche, Stäbe, Roben und Ringe. Neu sind auch Gegenstände für
  die Nebenhand statt der Fackel: zwei Laternen und ein Grimoire. Sie entzünden kein Fett (im Spiel geprüft). Die erste
  Laterne gibt es schon bei **Arron** im Druidenhain. Eine Kapuze in Akt 1 und ein Ring in Akt 2 geben
  Übung in leichter Rüstung. Ein Teil liegt bei Händlern (Grymforge, Weg nach Rosymorn, Mondaufgangstürme, Unterstadt),
  der Rest ist versteckt. Truhen füllen sich nur beim ersten Öffnen.
- **Noch nicht im Spiel getestet:** das neue Ritual, die neuen Gegenstände und die Talente ab Stufe 7.

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
