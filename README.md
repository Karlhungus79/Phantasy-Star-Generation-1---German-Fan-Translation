# Phantasy Star Generation:1 – German Fan Translation

Unofficial German translation of **SEGA AGES 2500 Series Vol. 1 – Phantasy Star Generation:1**
(PlayStation 2, NTSC-J, SLPM-62362). Version **1.0**.

The translation is based on FlamePurge's English script (PSCave patch v3.03). It was rendered into German,
adapted linguistically and technically re-inserted into the game. It is not a new translation from Japanese.

## What is in German?

- Dialogue, menus, status screen, help texts and battle commands
- Name tags in battle and enemy names (with umlauts and ß)
- A brand-new German ending credits sequence
- The main characters use the names from the Master System series: **Alis, Odin, Noah** and so on

## Extra options in the Options menu

The Options menu has four additional rows. The default values match the original game, and the settings
are stored in your save data.

| Row | Values |
|---|---|
| Experience / Meseta | x1 / x2 / x4 |
| Random battles | On / Off (also applies in dungeons; bosses and story battles still happen) |
| Running | Hold button / Always |
| Music | **PSG1** (PS2 music), **PSOG** (Master System music, normal sound), **PSFM** (Master System music with FM sound) |

With PSOG and PSFM the game behaves like on the Master System: after a battle the music of the area resumes
exactly where it was interrupted, the town music keeps playing in the clinic, and entering locations
produces no transition sound. Switching takes effect immediately.

Also fixed: the numbers in the results window after a battle are now displayed without gaps.

## Highlights of the new Options menu

The Options menu is not just "slightly extended" – it is a small command console for **your** Phantasy Star
adventure. Each of the four new rows makes the game more comfortable, more flexible or simply more beautiful
in its own way, and everything can be changed **at any time during play**, with no restart.

### ⚔️ Experience / Meseta (x1 / x2 / x4) – set the pace of your hero's journey

- **No more endless grinding:** With x2 or x4 your experience bar *and* your purse fill up in no time. Level-ups
  come flying at you, and the Meseta for the next suit of armor is saved up faster than a Palman antlion can
  say "ouch".
- **One dial, two effects:** Experience and Meseta are scaled together. No juggling, one value is enough.
- **Just right for every kind of player:** x1 is the unspoiled original experience for purists, x2 the
  golden middle for casual players, and x4 the turbo mode for everyone who finally wants to see the story or
  is playing for the second or third time.
- **Changeable at any time:** If a boss gets too tough, turn it up. If things become too easy, turn it back
  down. Your game, your rules.

### 🎲 Random battles (On / Off) – explore without constant interruptions

- **Undisturbed exploring:** With "Off" you can wander calmly across Palma, Motavia and Dezoris, admire the
  landscapes and listen to the music without being pulled out of the game every few steps.
- **Even works in dungeons:** Caves and labyrinths stay peaceful too. Mapping, hunting for chests and trying
  out routes is wonderfully relaxed.
- **Story stays story:** Bosses and story battles still take place. You skip nothing important, only the
  small fry in between.
- **Perfect for replays and videos:** If you already know the game or simply want to travel through the
  story, you save a lot of time. And since you can switch it back to "On" at any moment, you can still go
  monster hunting whenever you like.

### 👟 Running (Hold button / Always) – move faster, with less thumb cramp

- **"Hold button"** gives you the classic behavior of the original.
- **"Always"** turns you into a permanent sprinter: Alis and her companions dash through the world without a
  button held down. This spares your thumb on long stretches and noticeably speeds up the whole adventure.
- **Short trips, big plus:** Especially on the many marches between towns, spaceports and dungeons the game
  suddenly feels much smoother and more modern.

### 🎵 Music (PSG1 / PSOG / PSFM) – three soundtracks, one game, zero restarts

- **PSG1 – the PS2 soundtrack:** The familiar, rearranged SEGA AGES music. If you know and love the game
  this way, simply stay with it.
- **PSOG – Master System music with classic sound:** The original melodies by Tokuhiko Uwabo in the
  authentic sound of the Master System. Pure 8-bit nostalgia, straight from 1987.
- **PSFM – Master System music with FM sound:** The same pieces, but with the warm, full FM instruments of
  the Japanese Master System. The insider tip for connoisseurs, because this is how Phantasy Star sounded
  in Japan with the FM expansion.
- **Switch instantly:** The music changes the moment you change the option. So you can compare right in the
  middle of Camineet which sound you like better.
- **Authentic Master System feel:** After a battle the music of the area resumes exactly at the interrupted
  spot (with a soft fade-in) instead of starting over. In the clinic the town music keeps playing
  undisturbed, and entering places has no transition sound, just like in the original.
- **Built with care:** The ending credits have their own fitting music in PSOG and PSFM, the volume was
  balanced against the PS2 soundtrack, and the loops run cleanly.

### 💾 And this applies to all four rows

- **Saved in your save data:** Your settings are kept, even after quitting the game.
- **Faithful defaults:** If you change nothing, you play exactly the original. Everything else is an offer,
  not an obligation.
- **Neatly fitted into the menu:** Window and cursor are sized so that even the longest choice sits properly
  inside the brackets, in German and without cut-off text.

## Requirement: the Japanese original image

The patch fits exactly this dump only (BIN/CUE, **not** ISO):

```
Sega Ages 2500 Series Vol. 1 - Phantasy Star Generation 1 (Limited Edition) [NTSC-J] [SLPM-62362].bin
Size:   69,932,016 bytes
CRC32:  3A9B5922
MD5:    BBA63DA6BD64489DA663A856B1D49C8F
SHA-1:  3FAE75234774D8DB3D73228AAF8A33BEC9844D73
```

No game data is distributed, only an xdelta patch. You must own the game yourself.

## Applying the patch

**With Delta Patcher (Windows)**

1. Start [Delta Patcher](https://github.com/marco-calautti/DeltaPatcher/releases).
2. *Original file*: your Japanese `.bin`.
3. *XDelta patch*: `PSG1_Deutsch_v1.0.xdelta`.
4. Click *Apply patch*.

> **Important:** Delta Patcher overwrites the original file. Make a copy first or enable
> *Backup original file* in the settings. An original that has been overwritten once will not work
> for further patches.

**With xdelta3 (command line)**

```
xdelta3 -d -s "Original.bin" PSG1_Deutsch_v1.0.xdelta "PSG1_Deutsch_v1.0.bin"
```

**Verify the result** – the patched file must look like this:

```
Size:   70,345,968 bytes
CRC32:  1BD19B79
MD5:    FA47D1015FE0F35A3876D7756BB67B1F
SHA-1:  605C45279A741E775D10C74A37D0DA1FFF903811
```

If the patcher reports a checksum error, your image is a different dump. Check CRC32 and SHA-1 first.

**Starting the game:** Keep the original's `.cue` file and enter the file name of the new `.bin` in it:

```
FILE "PSG1_Deutsch_v1.0.bin" BINARY
  TRACK 01 MODE2/2352
    INDEX 01 00:00:00
```

PCSX2 can load the `.bin` or the `.cue`. Restart the game and **do not load a savestate** from another
version. A savestate keeps old graphics in memory.

## Credits

**German version**

| | |
|---|---|
| Karlhungus (Marcel) | Project lead, translation, extra options, music conversion |
| Zacke | Testing |
| FlamePurge | Support and tools; author of the English script this version is based on |
| CUE | LZR compression algorithm, PSG-LZR / PSG-PACK |
| Claude (Anthropic) | Technical support, see below |

**English version (patch v3.03)**

tryphon (reprogramming, inventor of Algoring, menu graphics) · Blaw- · mziab (Algoring, Double-EXP addition) ·
Kyence (original project author) · FlamePurge (translation organization, retranslation, lore consistency) ·
Nobunaga (ending credits) · Kini · Orakio_Rob · Ignitz · Rodolfo RG · CUE · Missagh Alami · BenoitRen ·
Polly Glot · Wolfgang Landgraf · bokokun · Ace_Aileron · KahnerC · Sega for the original.

Special thanks to the [PhantasyStarCave](https://www.pscave.com) community, who made this work possible in the first place.

The SMS music comes from the Master System original *Phantasy Star* (Sega, Tokuhiko Uwabo). For the FM instruments
(PSFM), emu2413 by Mitsutaka Okazaki (MIT license) was used.

## Note on AI assistance

Claude, an AI assistant by Anthropic, was used for the technical work (analysis of file formats, tools,
check scripts, insertion and verification of texts and graphics). Decisions about translation, terminology
and tone were made by the project lead himself.

## Legal

SEGA AGES 2500 Series Vol. 1 – Phantasy Star Generation:1 and the Phantasy Star universe are © SEGA.
This is an unofficial, non-commercial fan project and is distributed free of charge. Any commercial use is
prohibited. Use at your own risk; please back up your original image first.

Please report bugs and feedback in the PSCave forum or as a GitHub issue.

---

# Phantasy Star Generation:1 – Deutsche Fan-Übersetzung

Inoffizielle deutsche Übersetzung von **SEGA AGES 2500 Series Vol. 1 – Phantasy Star Generation:1**
(PlayStation 2, NTSC-J, SLPM-62362). Version **1.0**.

Die Übersetzung beruht auf dem englischen Skript von FlamePurge (PSCave-Patch v3.03) und wurde
ins Deutsche übertragen, sprachlich angepasst und technisch neu eingebaut. Sie ist keine eigene
Übersetzung aus dem Japanischen.

## Was ist deutsch?

- Dialoge, Menüs, Statusschirm, Hilfetexte und Kampfbefehle
- Namensschilder im Kampf und Gegnernamen (mit Umlauten und ß)
- Neuer deutscher Abspann
- Die Hauptfiguren tragen die Namen aus der Master-System-Reihe: **Alis, Odin, Noah** usw.

## Zusatzoptionen im Optionsmenü

Das Optionsmenü hat vier zusätzliche Zeilen. Die Standardwerte entsprechen dem Originalspiel,
die Einstellungen werden im Spielstand gespeichert.

| Zeile | Werte |
|---|---|
| Erfahrung / Meseta | x1 / x2 / x4 |
| Zufallskämpfe | An / Aus (gilt auch im Dungeon; Bosse und Story-Kämpfe bleiben) |
| Rennen | Taste halten / Immer |
| Musik | **PSG1** (PS2-Musik), **PSOG** (Master-System-Musik, normaler Sound), **PSFM** (Master-System-Musik mit FM-Sound) |

Bei PSOG und PSFM verhält sich das Spiel wie auf dem Master System: Nach dem Kampf setzt die Musik
des Gebiets an der unterbrochenen Stelle wieder ein, in der Klinik läuft die Stadtmusik weiter,
und beim Betreten von Orten gibt es kein Übergangsgeräusch. Die Umschaltung wirkt sofort.

Außerdem behoben: Die Zahlen im Ergebnisfenster nach dem Kampf werden ohne Lücken dargestellt.

## Die Highlights des neuen Optionsmenüs

Das Optionsmenü ist nicht einfach „ein bisschen erweitert“, es ist ein kleines Kommandopult für **dein**
Phantasy-Star-Abenteuer. Jede der vier neuen Zeilen macht das Spiel auf ihre Weise bequemer, flexibler
oder schlicht schöner – und alles lässt sich **jederzeit mitten im Spiel** umstellen, ganz ohne Neustart.

### ⚔️ Erfahrung / Meseta (x1 / x2 / x4) – Du bestimmst das Tempo deiner Heldenreise

- **Schluss mit endlosem Grinden:** Mit x2 oder x4 füllen sich Erfahrungsleiste *und* Geldbeutel in
  Windeseile. Level-Ups fliegen dir nur so zu, und die Meseta für die nächste Rüstung ist schneller
  beisammen, als ein Palma-Ameisenlöwe „Autsch“ sagen kann.
- **Ein Regler, zwei Wirkungen:** Erfahrung und Meseta werden gemeinsam skaliert. Du musst nicht jonglieren,
  ein Wert genügt.
- **Für jeden Spielertyp das Passende:** x1 ist das ungeschönte Originalerlebnis für Puristen, x2 der
  goldene Mittelweg für Gelegenheitsspieler, x4 die Turbo-Stufe für alle, die endlich die Story sehen
  wollen oder das Spiel zum zweiten und dritten Mal erleben.
- **Jederzeit änderbar:** Wird ein Boss zu zäh, drehst du hoch. Wird es dir zu leicht, drehst du wieder
  zurück. Dein Spiel, deine Regeln.

### 🎲 Zufallskämpfe (An / Aus) – Entdecken, ohne ständig gestört zu werden

- **Ungestörtes Erkunden:** Mit „Aus“ wanderst du in aller Ruhe über Palma, Motavia und Dezoris, bewunderst
  die Landschaften und hörst die Musik, ohne alle paar Schritte aus dem Spiel gerissen zu werden.
- **Gilt sogar im Dungeon:** Auch in den Höhlen und Labyrinthen bleibt es friedlich. Karten zeichnen,
  Truhen suchen und Wege ausprobieren geht damit herrlich entspannt.
- **Story bleibt Story:** Bosse und Story-Kämpfe finden weiterhin statt. Du überspringst nichts Wichtiges,
  nur den Kleinkram dazwischen.
- **Perfekt für Wiederholungsrunden und Videos:** Wer das Spiel schon kennt oder einfach durch die Geschichte
  reisen möchte, spart sich eine Menge Zeit. Und weil du es jederzeit wieder auf „An“ stellen kannst,
  gehst du gezielt auf Gegnerjagd, wenn du es willst.

### 👟 Rennen (Taste halten / Immer) – Flotter unterwegs, mit weniger Daumenkrampf

- **„Taste halten“** bietet dir das klassische Verhalten des Originals.
- **„Immer“** macht dich zum Dauersprinter: Alis und ihre Gefährten flitzen ohne gedrückte Taste durch
  die Welt. Das schont den Daumen bei langen Strecken und beschleunigt das ganze Abenteuer spürbar.
- **Kurze Wege, großes Plus:** Gerade bei den vielen Märschen zwischen Städten, Raumhäfen und Dungeons
  fühlt sich das Spiel plötzlich viel flüssiger und moderner an.

### 🎵 Musik (PSG1 / PSOG / PSFM) – Drei Soundtracks, ein Spiel, null Neustarts

- **PSG1 – der PS2-Soundtrack:** Die gewohnte, neu arrangierte Musik von SEGA AGES. Wer das Spiel so
  kennt und liebt, bleibt einfach dabei.
- **PSOG – Master-System-Musik mit klassischem Sound:** Die originalen Melodien von Tokuhiko Uwabo im
  authentischen Klang des Master Systems. Pure 8-Bit-Nostalgie, direkt aus dem Jahr 1987.
- **PSFM – Master-System-Musik mit FM-Sound:** Dieselben Stücke, aber mit den warmen, vollen FM-Instrumenten
  des japanischen Master Systems. Der „Geheimtipp“ für alle Kenner, denn so klang Phantasy Star damals
  in Japan mit FM-Erweiterung.
- **Sofort umschaltbar:** Die Musik wechselt in dem Moment, in dem du die Option änderst. Du kannst
  also mitten in Camineet direkt vergleichen, welcher Klang dir besser gefällt.
- **Authentisches Master-System-Gefühl:** Nach einem Kampf setzt die Musik des Gebiets genau an der
  unterbrochenen Stelle wieder ein (mit weichem Einblenden), statt wieder von vorn zu beginnen. In der
  Klinik läuft die Stadtmusik ungestört weiter, und beim Betreten von Orten bleibt das Übergangsgeräusch
  weg, genau wie im Original.
- **Bedacht und mit Liebe eingebaut:** Der Abspann hat bei PSOG und PSFM seine eigene passende Musik, die
  Lautstärke wurde gegen den PS2-Soundtrack abgeglichen, und die Schleifen laufen sauber durch.

### 💾 Und das gilt für alle vier Zeilen

- **Im Spielstand gespeichert:** Deine Einstellungen bleiben erhalten, auch nach dem Beenden des Spiels.
- **Originalgetreue Standardwerte:** Wer nichts ändert, spielt exakt das Original. Alles Weitere ist
  ein Angebot, kein Zwang.
- **Sauber ins Menü eingepasst:** Fenster und Cursor sind so bemessen, dass auch die längste Auswahl
  ordentlich in der Klammer sitzt, auf Deutsch und ohne abgeschnittene Texte.

## Voraussetzung: das japanische Original-Image

Der Patch passt nur auf genau diesen Dump (BIN/CUE, **nicht** ISO):

```
Sega Ages 2500 Series Vol. 1 - Phantasy Star Generation 1 (Limited Edition) [NTSC-J] [SLPM-62362].bin
Größe:  69.932.016 Bytes
CRC32:  3A9B5922
MD5:    BBA63DA6BD64489DA663A856B1D49C8F
SHA-1:  3FAE75234774D8DB3D73228AAF8A33BEC9844D73
```

Es werden keine Spieldaten weitergegeben, sondern nur ein xdelta-Patch. Das Spiel musst du selbst besitzen.

## Patch anwenden

**Mit Delta Patcher (Windows)**

1. [Delta Patcher](https://github.com/marco-calautti/DeltaPatcher/releases) starten.
2. *Original file*: dein japanisches `.bin`.
3. *XDelta patch*: `PSG1_Deutsch_v1.0.xdelta`.
4. *Apply patch* klicken.

> **Wichtig:** Delta Patcher überschreibt die Originaldatei. Vorher eine Kopie anlegen oder in den
> Einstellungen *Backup original file* aktivieren. Ein einmal überschriebenes Original funktioniert
> für weitere Patches nicht mehr.

**Mit xdelta3 (Kommandozeile)**

```
xdelta3 -d -s "Original.bin" PSG1_Deutsch_v1.0.xdelta "PSG1_Deutsch_v1.0.bin"
```

**Ergebnis prüfen** – die gepatchte Datei muss so aussehen:

```
Größe:  70.345.968 Bytes
CRC32:  1BD19B79
MD5:    FA47D1015FE0F35A3876D7756BB67B1F
SHA-1:  605C45279A741E775D10C74A37D0DA1FFF903811
```

Meldet der Patcher einen Prüfsummenfehler, ist dein Image ein anderer Dump. Prüfe zuerst CRC32 und SHA-1.

**Starten:** Die `.cue`-Datei des Originals behalten und darin den Dateinamen der neuen `.bin` eintragen:

```
FILE "PSG1_Deutsch_v1.0.bin" BINARY
  TRACK 01 MODE2/2352
    INDEX 01 00:00:00
```

PCSX2 kann die `.bin` oder die `.cue` laden. Das Spiel neu starten und **keinen Savestate** einer
anderen Version laden. Ein Savestate hält alte Grafiken im Speicher.

## Credits

**Deutsche Fassung**

| | |
|---|---|
| Karlhungus (Marcel) | Projektleitung, Übersetzung, Zusatzoptionen, Musikumsetzung |
| Zacke | Tests |
| FlamePurge | Unterstützung und Werkzeuge; Autor des englischen Skripts, auf dem diese Fassung beruht |
| CUE | LZR-Kompressionsalgorithmus, PSG-LZR / PSG-PACK |
| Claude (Anthropic) | Technische Unterstützung, siehe unten |

**Englische Fassung (Patch v3.03)**

tryphon (Neuprogrammierung, Erfinder von Algoring, Menügrafiken) · Blaw- · mziab (Algoring, Double-EXP-Zusatz) ·
Kyence (ursprüngliche Projektautorin) · FlamePurge (Übersetzungsorganisation, Neuübersetzung, Lore-Konsistenz) ·
Nobunaga (Abspann) · Kini · Orakio_Rob · Ignitz · Rodolfo RG · CUE · Missagh Alami · BenoitRen ·
Polly Glot · Wolfgang Landgraf · bokokun · Ace_Aileron · KahnerC · Sega für das Original.

Besonderer Dank an die Community von [PhantasyStarCave](https://www.pscave.com), die diese Arbeit überhaupt möglich gemacht hat.

Die SMS-Musik stammt aus dem Master-System-Original *Phantasy Star* (Sega, Tokuhiko Uwabo). Für die FM-Instrumente
(PSFM) wurde emu2413 von Mitsutaka Okazaki (MIT-Lizenz) verwendet.

## Hinweis zur KI-Unterstützung

Bei der technischen Arbeit (Auswertung der Dateiformate, Werkzeuge, Prüfskripte, Einbau und Prüfung von Texten
und Grafiken) wurde Claude, ein KI-Assistent von Anthropic, eingesetzt. Entscheidungen zu Übersetzung, Begriffen
und Ton traf der Projektleiter selbst.

## Rechtliches

SEGA AGES 2500 Series Vol. 1 – Phantasy Star Generation:1 und das Phantasy-Star-Universum sind © SEGA.
Dies ist ein inoffizielles, nicht-kommerzielles Fan-Projekt und wird kostenlos weitergegeben. Jede kommerzielle
Nutzung ist untersagt. Die Nutzung erfolgt auf eigene Gefahr, bitte sichere vorher dein Original-Image.

Fehler und Rückmeldungen bitte im PSCave-Forum oder als GitHub-Issue melden.
