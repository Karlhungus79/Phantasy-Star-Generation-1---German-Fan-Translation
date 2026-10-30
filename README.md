# Phantasy Star Generation:1 – German Fan Translation

Unofficial German translation of **SEGA AGES 2500 Series Vol. 1 – Phantasy Star Generation:1**
(PlayStation 2, NTSC-J, SLPM-62362). Version **1.1**.

The translation is based on FlamePurge's English script (PSCave patch v3.03). It was rendered into German,
adapted linguistically and technically re-inserted into the game. It is not a new translation from Japanese.

*Deutsche Version: siehe weiter unten (ab „Phantasy Star Generation:1 – Deutsche Fan-Übersetzung“).*

## Two games in one

This patch contains two games that are played differently. To avoid confusion, this readme always says which one
it means:

- **PSG1** = the PS2 remake *Phantasy Star Generation:1* itself.
- **Original game** = the Master System classic *Phantasy Star* (1987), built into the title menu as a third entry.

| | PSG1 | Original game |
|---|---|---|
| What it is | PS2 remake | Master System game, German translation by Karlhungus with quality-of-life updates, runs in a built-in emulator |
| Title menu entry | Start / Continue | **Originalspiel** |
| Extra options (experience / Meseta, random battles, running) | yes, rows in the PSG1 Options menu | yes, in the Original game's own **OPTIONEN** menu |
| Music selection (PSG1 / PSOG / PSFM) | yes | **no** (Master System sound only) |
| Macros | yes, in the PSG1 main menu and battle menu | yes, the Original game's own macros (4 macros) |
| Double battle speed (Square) | yes | **no** |
| Enemy names on/off (R1) | yes | **no** |
| Save data | PS2 save on Memory Card | separate file `PS1SRAM` on Memory Card 1, written about 2 seconds after saving |
| Save slots | PS2 save slots | the 5 save slots of the Master System game |
| Back to the title screen of PSG1 | – | SELECT + START (hold for about 1 second); **PSG1 restarts, unsaved PSG1 progress is lost** |

## What's new in 1.1

**PSG1**

- **Macros:** a new main menu entry **MAKRO** (below SYSTEM) and a fourth button in the battle menu. Set up to
  four battle macros once, then run a whole round with a single button press. See "Macros" below.
- **Battle speed:** hold **Square** during a battle in PSG1 for double speed.
- **Enemy names in battle:** the on/off switch is now **R1** (it was Square). Square is now only used for the
  battle speed.
- **Items renamed:** *PelorieMate* is now **Cola**, *Roginine* is now **Burger**. Dialogue was adjusted
  accordingly.
- **Fixed:** the MAKRO entry in the main menu no longer disappears after leaving the ITEM menu.
- **Fixed:** the macro editor only offers characters that are already in your party, also when choosing a target.

**Original game**

- **New:** the Master System classic *Phantasy Star* in a German translation by Karlhungus as a third entry in
  the title menu, **Originalspiel**. It comes with quality-of-life updates: an **OPTIONEN** menu with experience /
  Meseta x1/x2/x4, faster running and random battles on/off, plus battle macros. See "Original game" below.
- **Notice screen** before the start (idea by FlamePurge): save in PSG1 first, otherwise the Original game cannot
  save.
- **Message when saving fails:** if the save data cannot be written to the Memory Card, a message appears.
- **Controls** match PSG1: Circle confirms, Cross cancels.
- **Fixed:** the title menu entry "Originalspiel" no longer disappears after you choose "Continue" and leave the
  save list again, and no leftover save-game text remains on screen.

Everything from version 1.0 is still included.

## What is in German?

- Dialogue, menus, status screen, help texts and battle commands
- Name tags in battle and enemy names (with umlauts and ß)
- A brand-new German ending credits sequence
- The main characters use the names from the Master System series: **Alis, Odin, Noah** and so on
- The Original game is in German too (German translation with quality-of-life updates by Karlhungus)

### About the names

The English v3.03 patch uses the names **Alisa, Tyrone, Lutz, La Shiec and Dark Falz**. FlamePurge kept them
because the original project author, Kyence, wanted the retranslated names, and he wanted to respect her wishes.
He has kindly agreed that this German version uses the names known from the Master System series and the
Western releases instead: **Alis, Odin, Noah, Lassic and Dark Force**. This is a matter of taste for German
players who know the series under these names, not a criticism of the English version.

## PSG1: Extra options in the Options menu

*Applies to PSG1 only, not to the Original game.*

The Options menu has four additional rows. The default values match the original game, and the settings
are stored in your save data. Everything can be changed at any time during play, no restart needed.

| Row | Values |
|---|---|
| Experience / Meseta | x1 / x2 / x4 |
| Random battles | On / Off (also applies in dungeons; bosses and story battles still happen) |
| Running | Hold button / Always |
| Music | **PSG1** (PS2 music), **PSOG** (Master System music, normal sound), **PSFM** (Master System music with FM sound) |

- **Experience / Meseta:** both are scaled together. x1 is the original, x2 and x4 shorten the grinding.
- **Random battles:** with "Off" you can explore Palma, Motavia and Dezoris, including all dungeons, without
  being interrupted. Bosses and story battles still take place.
- **Running:** "Hold button" is the classic behavior, "Always" makes the party run without a button held down.
- **Music:** PSOG plays the original melodies by Tokuhiko Uwabo with the classic Master System sound, PSFM
  with the warmer FM instruments of the Japanese Master System. With both, the game behaves like on the Master
  System: after a battle the music of the area resumes exactly where it was interrupted, the town music keeps
  playing in the clinic, and entering locations produces no transition sound. The ending credits have their own
  fitting music. Switching takes effect immediately.

Also: the numbers in the results window after a battle are displayed without gaps.

## PSG1: Macros

*Applies to PSG1 only, not to the Original game.* Macros work like in the sister project for Phantasy Star
Generation:2.

- **Editor:** main menu, entry **MAKRO** (below SYSTEM). There are **4 macros**. For every party member you
  choose a command (attack, technique, combo or item). The editor only offers characters that are already in
  your party, also when choosing a target.
- **In battle:** the battle menu has a fourth button, **MAKRO**. Pick a macro and the party carries out its
  commands for the round.
- **Targets:** enemy targets are chosen automatically (the first enemy still alive). Combos are allowed.
- **Impossible commands** (for example not enough MP, or an item that is no longer there) turn into a normal
  attack.
- Macros are stored in your save data.

## Controls

**In PSG1**

| Button | Function |
|---|---|
| Square (hold, in battle) | Double battle speed |
| R1 (in battle) | Enemy names on / off |
| Triangle (technique and item lists) | Help text on / off |

**In the Original game**

| Button | Function |
|---|---|
| D-pad | Move |
| Circle | Confirm (Master System button 2) |
| Cross | Cancel (Master System button 1) |
| Triangle | Open the command window (Master System button 1) |
| START | Pause (Master System pause button) |
| SELECT + START (hold for about 1 second) | Back to PSG1 (PSG1 restarts) |
| Square | no function – there is no speed-up in the Original game |

## Original game

The title menu has a third entry, **Originalspiel**. It starts the Master System version of *Phantasy Star*
(1987) in a German translation by Karlhungus (Marcel), including quality-of-life updates. It runs inside the
game through a built-in Master System emulator, with picture and sound. It is the Master System game, not the
PSG1 remake: the PSG1 extras (PSG1 Options rows, PSG1 macros, battle speed, enemy-name switch, music selection)
do not work there. The Original game has its own extras instead:

**Quality-of-life updates in the Original game** (all by Karlhungus)

- **OPTIONEN menu** with
  - **Experience and Meseta:** x1 / x2 / x4
  - **Faster running:** yes / no
  - **Random battles:** on / off
- **Macros:** up to 4 battle macros (attack and so on) to run a round with fewer button presses.
- These settings belong to the Original game and are independent of the PSG1 options.

**Saving the Original game.** In the game you save the Master System way: open the command window with
Cross or Triangle, choose SAVE and one of the 5 save slots (not possible during a battle). The save data of the
Original game is written to **Memory Card 1** as `PS1SRAM`, inside the folder of the PS2 game (`BISLPM-62362`),
next to your PSG1 save games. It does not touch your PSG1 saves. That folder only exists after you have saved
Phantasy Star Generation:1 at least once on Memory Card 1.

- Therefore a **notice screen** appears before the Original game starts: save in PSG1 first. Continue with
  Circle.
- If the Original game cannot save, because there is no PSG1 save game on Memory Card 1, a message appears
  for 5 seconds: "Nicht gespeichert! Zuerst PSG1 auf Memory Card 1 speichern." (Not saved! Save PSG1 to Memory
  Card 1 first.)
- The save data is written to the card about 2 seconds after you save inside the game. Do not remove the
  Memory Card or switch off the console in that moment.

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

**Always patch the original Japanese image**, never an already patched version 1.0.

## Applying the patch

**With Delta Patcher (Windows)**

1. Start Delta Patcher: https://github.com/marco-calautti/DeltaPatcher/releases
2. *Original file*: your Japanese `.bin`.
3. *XDelta patch*: `PSG1_Deutsch_v1.1.xdelta`.
4. Click *Apply patch*.

> **Important:** Delta Patcher overwrites the original file. Make a copy first or enable
> *Backup original file* in the settings. An original that has been overwritten once will not work
> for further patches.

**With xdelta3 (command line)**

```
xdelta3 -d -s "Original.bin" PSG1_Deutsch_v1.1.xdelta "PSG1_Deutsch_v1.1.bin"
```

**Verify the result** – the patched file must look like this:

```
Size:   71,133,888 bytes
CRC32:  7322991B
MD5:    43B56032E4CF4A70E5B4EDF59452E828
SHA-1:  F523016A98F0333EEBD286A693200204D0751B69
```

If the patcher reports a checksum error, your image is a different dump. Check CRC32 and SHA-1 first.

**Starting the game:** Keep the original's `.cue` file and enter the file name of the new `.bin` in it:

```
FILE "PSG1_Deutsch_v1.1.bin" BINARY
  TRACK 01 MODE2/2352
    INDEX 01 00:00:00
```

PCSX2 can load the `.bin` or the `.cue`. Restart the game and **do not load a savestate** from another
version. A savestate keeps old graphics in memory.

## Credits

**German version**

| | |
|---|---|
| Karlhungus (Marcel) | Project lead, translation, extra options, macros, music conversion, integration of the Original game; German translation of the Original game (Master System) including its quality-of-life updates |
| Zacke | Testing and proofreading of the dialogue |
| FlamePurge | Support and tools; author of the English script this version is based on; testing of version 1.1 and the idea of the notice screen before the Original game |
| CUE | LZR compression algorithm, PSG-LZR / PSG-PACK |
| Nicolas Allemand | Z80 emulation core (MIT license) used for the Original game |
| Claude (Anthropic) | Technical support, see below |

**English version (patch v3.03)**

tryphon (reprogramming, inventor of Algoring, menu graphics) · Blaw- · mziab (Algoring, Double-EXP addition) ·
Kyence (original project author) · FlamePurge (translation organization, retranslation, lore consistency) ·
Nobunaga (ending credits) · Kini · Orakio_Rob · Ignitz · Rodolfo RG · CUE · Missagh Alami · BenoitRen ·
Polly Glot · Wolfgang Landgraf · bokokun · Ace_Aileron · KahnerC · Sega for the original.

Special thanks to the PhantasyStarCave community (https://www.pscave.com), who made this work possible in the
first place.

The SMS music comes from the Master System original *Phantasy Star* (Sega, Tokuhiko Uwabo). For the FM instruments
(PSFM), emu2413 by Mitsutaka Okazaki (MIT license) was used.

## Note on AI assistance

Claude, an AI assistant by Anthropic, was used for the technical work (analysis of file formats, tools,
check scripts, insertion and verification of texts and graphics, programming of the extra functions). Decisions
about translation, terminology and tone were made by the project lead himself.

## Legal

SEGA AGES 2500 Series Vol. 1 – Phantasy Star Generation:1, *Phantasy Star* and the Phantasy Star universe are
© SEGA. This is an unofficial, non-commercial fan project and is distributed free of charge. Any commercial use
is prohibited. Use at your own risk; please back up your original image first.

Please report bugs and feedback in the PSCave forum (https://www.pscave.com).

---

# Phantasy Star Generation:1 – Deutsche Fan-Übersetzung

Inoffizielle deutsche Übersetzung von **SEGA AGES 2500 Series Vol. 1 – Phantasy Star Generation:1**
(PlayStation 2, NTSC-J, SLPM-62362). Version **1.1**.

Die Übersetzung beruht auf dem englischen Skript von FlamePurge (PSCave-Patch v3.03) und wurde
ins Deutsche übertragen, sprachlich angepasst und technisch neu eingebaut. Sie ist keine eigene
Übersetzung aus dem Japanischen.

## Zwei Spiele in einem

Dieser Patch enthält zwei Spiele, die sich unterschiedlich bedienen. Damit nichts durcheinandergerät, steht in
dieser Anleitung immer dabei, welches gemeint ist:

- **PSG1** = das PS2-Remake *Phantasy Star Generation:1* selbst.
- **Originalspiel** = der Master-System-Klassiker *Phantasy Star* (1987), als dritter Eintrag im Titelmenü
  eingebaut.

| | PSG1 | Originalspiel |
|---|---|---|
| Was es ist | PS2-Remake | Master-System-Spiel, deutsche Übersetzung von Karlhungus mit Komfort-Verbesserungen, läuft in einem eingebauten Emulator |
| Eintrag im Titelmenü | Start / Fortsetzen | **Originalspiel** |
| Zusatzoptionen (Erfahrung / Meseta, Zufallskämpfe, Rennen) | ja, Zeilen im PSG1-Optionsmenü | ja, im eigenen Menü **OPTIONEN** des Originalspiels |
| Musikauswahl (PSG1 / PSOG / PSFM) | ja | **nein** (nur Master-System-Klang) |
| Makros | ja, im PSG1-Hauptmenü und Kampfmenü | ja, eigene Makros des Originalspiels (4 Makros) |
| Doppeltes Kampftempo (Viereck) | ja | **nein** |
| Gegnernamen an/aus (R1) | ja | **nein** |
| Spielstand | PS2-Spielstand auf der Memory Card | eigene Datei `PS1SRAM` auf Memory Card 1, wird etwa 2 Sekunden nach dem Speichern geschrieben |
| Speicherplätze | PS2-Speicherplätze | die 5 Speicherplätze des Master-System-Spiels |
| Zurück zu PSG1 | – | SELECT + START (ca. 1 Sekunde halten); **PSG1 startet neu, nicht gespeicherter PSG1-Fortschritt geht verloren** |

## Neu in 1.1

**PSG1**

- **Makros:** ein neuer Hauptmenüpunkt **MAKRO** (unter SYSTEM) und ein vierter Knopf im Kampfmenü. Bis zu
  vier Kampf-Makros einmal einrichten, dann eine ganze Runde mit einem Tastendruck ausführen. Siehe „Makros“.
- **Kampftempo:** **Viereck** im Kampf von PSG1 gehalten = doppeltes Tempo.
- **Gegnernamen im Kampf:** Der An/Aus-Schalter liegt jetzt auf **R1** (vorher Viereck). Viereck dient nur
  noch dem Kampftempo.
- **Waren umbenannt:** *PelorieMate* heißt jetzt **Cola**, *Roginine* heißt jetzt **Burger**. Die Dialoge
  wurden angepasst.
- **Behoben:** Der Eintrag MAKRO im Hauptmenü verschwindet nicht mehr, nachdem man das ITEM-Menü verlassen hat.
- **Behoben:** Der Makro-Editor bietet nur Figuren an, die schon in deiner Gruppe sind, auch bei der
  Zielauswahl.

**Originalspiel**

- **Neu:** der Master-System-Klassiker *Phantasy Star* in einer deutschen Übersetzung von Karlhungus als dritter
  Eintrag im Titelmenü, **Originalspiel**. Er bringt Komfort-Verbesserungen mit: ein Menü **OPTIONEN** mit
  Erfahrung / Meseta x1/x2/x4, schnellerem Laufen und Zufallskämpfen an/aus sowie Kampf-Makros. Siehe „Originalspiel“.
- **Hinweisbild** vor dem Start (Idee von FlamePurge): erst in PSG1 speichern, sonst kann das Originalspiel nicht
  speichern.
- **Meldung bei fehlgeschlagenem Speichern:** Lässt sich der Spielstand nicht auf die Memory Card schreiben,
  erscheint eine Meldung.
- **Steuerung** wie in PSG1: Kreis bestätigt, Kreuz bricht ab.
- **Behoben:** Der Titelmenüeintrag „Originalspiel“ verschwindet nicht mehr, nachdem man „Fortsetzen“ gewählt
  und die Spielstandliste wieder verlassen hat, und es bleibt kein Text eines Spielstands auf dem Bildschirm
  stehen.

Alles aus Version 1.0 ist weiterhin enthalten.

## Was ist deutsch?

- Dialoge, Menüs, Statusschirm, Hilfetexte und Kampfbefehle
- Namensschilder im Kampf und Gegnernamen (mit Umlauten und ß)
- Neuer deutscher Abspann
- Die Hauptfiguren tragen die Namen aus der Master-System-Reihe: **Alis, Odin, Noah** usw.
- Auch das Originalspiel ist deutsch (deutsche Übersetzung von Karlhungus mit Komfort-Verbesserungen)

### Zu den Namen

Der englische Patch v3.03 verwendet die Namen **Alisa, Tyrone, Lutz, La Shiec und Dark Falz**. FlamePurge hat
sie beibehalten, weil die ursprüngliche Projektautorin Kyence die neu übersetzten Namen wollte und er ihre
Wünsche respektieren wollte. Er war freundlicherweise damit einverstanden, dass diese deutsche Fassung
stattdessen die aus der Master-System-Reihe und den westlichen Veröffentlichungen bekannten Namen nutzt:
**Alis, Odin, Noah, Lassic und Dark Force**. Das ist eine Geschmacksfrage für deutsche Spieler, die die Reihe
unter diesen Namen kennen, keine Kritik an der englischen Fassung.

## PSG1: Zusatzoptionen im Optionsmenü

*Gilt nur für PSG1, nicht für das Originalspiel.*

Das Optionsmenü hat vier zusätzliche Zeilen. Die Standardwerte entsprechen dem Originalspiel,
die Einstellungen werden im Spielstand gespeichert. Alles lässt sich jederzeit mitten im Spiel umstellen,
ohne Neustart.

| Zeile | Werte |
|---|---|
| Erfahrung / Meseta | x1 / x2 / x4 |
| Zufallskämpfe | An / Aus (gilt auch im Dungeon; Bosse und Story-Kämpfe bleiben) |
| Rennen | Taste halten / Immer |
| Musik | **PSG1** (PS2-Musik), **PSOG** (Master-System-Musik, normaler Sound), **PSFM** (Master-System-Musik mit FM-Sound) |

- **Erfahrung / Meseta:** beides wird gemeinsam skaliert. x1 ist das Original, x2 und x4 verkürzen das Grinden.
- **Zufallskämpfe:** Mit „Aus“ erkundest du Palma, Motavia und Dezoris samt aller Dungeons ohne Unterbrechung.
  Bosse und Story-Kämpfe finden weiterhin statt.
- **Rennen:** „Taste halten“ ist das klassische Verhalten, „Immer“ lässt die Gruppe ohne gedrückte Taste rennen.
- **Musik:** PSOG spielt die originalen Melodien von Tokuhiko Uwabo im klassischen Klang des Master Systems,
  PSFM mit den wärmeren FM-Instrumenten des japanischen Master Systems. Bei beiden verhält sich das Spiel wie
  auf dem Master System: Nach dem Kampf setzt die Musik des Gebiets an der unterbrochenen Stelle wieder ein,
  in der Klinik läuft die Stadtmusik weiter, und beim Betreten von Orten gibt es kein Übergangsgeräusch. Der
  Abspann hat seine eigene passende Musik. Die Umschaltung wirkt sofort.

Außerdem: Die Zahlen im Ergebnisfenster nach dem Kampf werden ohne Lücken dargestellt.

## PSG1: Makros

*Gilt nur für PSG1, nicht für das Originalspiel.* Die Makros funktionieren wie im Schwesterprojekt für
Phantasy Star Generation:2.

- **Editor:** Hauptmenü, Eintrag **MAKRO** (unter SYSTEM). Es gibt **4 Makros**. Für jede Figur der Gruppe
  wählst du einen Befehl (Angriff, Technik, Kombo oder Ware). Der Editor bietet nur Figuren an, die schon in
  deiner Gruppe sind, auch bei der Zielauswahl.
- **Im Kampf:** Das Kampfmenü hat einen vierten Knopf, **MAKRO**. Wähle ein Makro, und die Gruppe führt dessen
  Befehle für die Runde aus.
- **Ziele:** Gegnerziele werden automatisch gewählt (der erste noch lebende Gegner). Kombos sind erlaubt.
- **Unmögliche Befehle** (zum Beispiel zu wenig MP oder eine Ware, die nicht mehr da ist) werden zu einem
  normalen Angriff.
- Die Makros werden im Spielstand gespeichert.

## Steuerung

**In PSG1**

| Taste | Funktion |
|---|---|
| Viereck (halten, im Kampf) | Doppeltes Kampftempo |
| R1 (im Kampf) | Gegnernamen an / aus |
| Dreieck (Listen für Techniken und Waren) | Hilfetext an / aus |

**Im Originalspiel**

| Taste | Funktion |
|---|---|
| Steuerkreuz | Bewegen |
| Kreis | Bestätigen (Master-System-Taste 2) |
| Kreuz | Abbrechen (Master-System-Taste 1) |
| Dreieck | Befehlsfenster öffnen (Master-System-Taste 1) |
| START | Pause (Pause-Taste des Master Systems) |
| SELECT + START (ca. 1 Sekunde halten) | Zurück zu PSG1 (PSG1 startet neu) |
| Viereck | keine Funktion – im Originalspiel gibt es keine Beschleunigung |

## Originalspiel

Das Titelmenü hat einen dritten Eintrag, **Originalspiel**. Er startet die Master-System-Fassung von
*Phantasy Star* (1987) in einer deutschen Übersetzung von Karlhungus (Marcel) samt Komfort-Verbesserungen. Sie
läuft über einen eingebauten Master-System-Emulator im Spiel, mit Bild und Ton. Es ist das Master-System-Spiel,
nicht das PSG1-Remake: Die PSG1-Extras (PSG1-Optionszeilen, PSG1-Makros, Kampftempo, Gegnernamen-Schalter,
Musikauswahl) wirken dort nicht. Das Originalspiel hat stattdessen eigene Extras:

**Komfort-Verbesserungen im Originalspiel** (alle von Karlhungus)

- **Menü OPTIONEN** mit
  - **Erfahrung und Meseta:** x1 / x2 / x4
  - **Schneller laufen:** Ja / Nein
  - **Zufallskämpfe:** An / Aus
- **Makros:** bis zu 4 Kampf-Makros (Angriff usw.), um eine Runde mit weniger Tastendrücken auszuführen.
- Diese Einstellungen gehören zum Originalspiel und sind unabhängig von den PSG1-Optionen.

**Speichern im Originalspiel.** Im Spiel speicherst du wie am Master System: Mit Kreuz oder Dreieck das
Befehlsfenster öffnen, SPEICHERN und einen der 5 Speicherplätze wählen (nicht während eines Kampfes). Der
Spielstand des Originalspiels wird auf **Speicherkarte 1** als `PS1SRAM` in den Ordner des PS2-Spiels
(`BISLPM-62362`) geschrieben, neben deine PSG1-Spielstände. Deine PSG1-Spielstände bleiben unberührt. Diesen
Ordner gibt es erst, nachdem du Phantasy Star Generation:1 mindestens einmal auf Speicherkarte 1 gespeichert hast.

- Deshalb erscheint vor dem Start des Originalspiels ein **Hinweisbild**: erst in PSG1 speichern. Weiter geht es
  mit Kreis.
- Kann das Originalspiel nicht speichern, weil auf Speicherkarte 1 kein PSG1-Spielstand liegt, erscheint
  5 Sekunden lang die Meldung „Nicht gespeichert! Zuerst PSG1 auf Memory Card 1 speichern.“
- Der Spielstand wird etwa 2 Sekunden nach dem Speichern im Spiel auf die Karte geschrieben. Die Speicherkarte
  in diesem Moment nicht entfernen und die Konsole nicht ausschalten.

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

**Immer das japanische Original-Image patchen**, nie eine bereits gepatchte Version 1.0.

## Patch anwenden

**Mit Delta Patcher (Windows)**

1. Delta Patcher starten: https://github.com/marco-calautti/DeltaPatcher/releases
2. *Original file*: dein japanisches `.bin`.
3. *XDelta patch*: `PSG1_Deutsch_v1.1.xdelta`.
4. *Apply patch* klicken.

> **Wichtig:** Delta Patcher überschreibt die Originaldatei. Vorher eine Kopie anlegen oder in den
> Einstellungen *Backup original file* aktivieren. Ein einmal überschriebenes Original funktioniert
> für weitere Patches nicht mehr.

**Mit xdelta3 (Kommandozeile)**

```
xdelta3 -d -s "Original.bin" PSG1_Deutsch_v1.1.xdelta "PSG1_Deutsch_v1.1.bin"
```

**Ergebnis prüfen** – die gepatchte Datei muss so aussehen:

```
Größe:  71.133.888 Bytes
CRC32:  7322991B
MD5:    43B56032E4CF4A70E5B4EDF59452E828
SHA-1:  F523016A98F0333EEBD286A693200204D0751B69
```

Meldet der Patcher einen Prüfsummenfehler, ist dein Image ein anderer Dump. Prüfe zuerst CRC32 und SHA-1.

**Starten:** Die `.cue`-Datei des Originals behalten und darin den Dateinamen der neuen `.bin` eintragen:

```
FILE "PSG1_Deutsch_v1.1.bin" BINARY
  TRACK 01 MODE2/2352
    INDEX 01 00:00:00
```

PCSX2 kann die `.bin` oder die `.cue` laden. Das Spiel neu starten und **keinen Savestate** einer
anderen Version laden. Ein Savestate hält alte Grafiken im Speicher.

## Credits

**Deutsche Fassung**

| | |
|---|---|
| Karlhungus (Marcel) | Projektleitung, Übersetzung, Zusatzoptionen, Makros, Musikumsetzung, Einbau des Originalspiels; deutsche Übersetzung des Originalspiels (Master System) samt dessen Komfort-Verbesserungen |
| Zacke | Tests und Gegenlesen der Dialoge |
| FlamePurge | Unterstützung und Werkzeuge; Autor des englischen Skripts, auf dem diese Fassung beruht; Tests von Version 1.1 und Idee des Hinweisbilds vor dem Originalspiel |
| CUE | LZR-Kompressionsalgorithmus, PSG-LZR / PSG-PACK |
| Nicolas Allemand | Z80-Emulationskern (MIT-Lizenz) für das Originalspiel |
| Claude (Anthropic) | Technische Unterstützung, siehe unten |

**Englische Fassung (Patch v3.03)**

tryphon (Neuprogrammierung, Erfinder von Algoring, Menügrafiken) · Blaw- · mziab (Algoring, Double-EXP-Zusatz) ·
Kyence (ursprüngliche Projektautorin) · FlamePurge (Übersetzungsorganisation, Neuübersetzung, Lore-Konsistenz) ·
Nobunaga (Abspann) · Kini · Orakio_Rob · Ignitz · Rodolfo RG · CUE · Missagh Alami · BenoitRen ·
Polly Glot · Wolfgang Landgraf · bokokun · Ace_Aileron · KahnerC · Sega für das Original.

Besonderer Dank an die Community von PhantasyStarCave (https://www.pscave.com), die diese Arbeit überhaupt
möglich gemacht hat.

Die SMS-Musik stammt aus dem Master-System-Original *Phantasy Star* (Sega, Tokuhiko Uwabo). Für die FM-Instrumente
(PSFM) wurde emu2413 von Mitsutaka Okazaki (MIT-Lizenz) verwendet.

## Hinweis zur KI-Unterstützung

Bei der technischen Arbeit (Auswertung der Dateiformate, Werkzeuge, Prüfskripte, Einbau und Prüfung von Texten
und Grafiken, Programmierung der Zusatzfunktionen) wurde Claude, ein KI-Assistent von Anthropic, eingesetzt.
Entscheidungen zu Übersetzung, Begriffen und Ton traf der Projektleiter selbst.

## Rechtliches

SEGA AGES 2500 Series Vol. 1 – Phantasy Star Generation:1, *Phantasy Star* und das Phantasy-Star-Universum sind
© SEGA. Dies ist ein inoffizielles, nicht-kommerzielles Fan-Projekt und wird kostenlos weitergegeben. Jede
kommerzielle Nutzung ist untersagt. Die Nutzung erfolgt auf eigene Gefahr, bitte sichere vorher dein
Original-Image.

Fehler und Rückmeldungen bitte im PSCave-Forum melden (https://www.pscave.com).
