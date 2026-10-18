ARCHIV 016 — VARKHON / REVISION 13

Starten
- ZIP vollständig entpacken.
- archiv-016/index.html öffnen.
- Die Startanimation läuft 10 Sekunden: Eine schwere Papierakte kommt auf den Tisch, der Einband klappt langsam auf, Seiten werden sichtbar und ein Stempel setzt den Abschluss.
- Die Musiksteuerung auf der Hauptseite enthält nur Musik AN/AUS und Lautstärke.
- Wenn der Browser Autoplay mit Ton blockiert, während des Einstiegs auf „TON AKTIVIEREN“ klicken.

Änderungen in Revision 11
- Der Stil wurde in Richtung physische Papierakte, abgegriffener Einband, Papierkanten und Stempel überarbeitet. Der Startscreen verwendet kein hochgeladenes Tischfoto als Hintergrund.
- Die Öffnungsanimation ist langsamer und weicher abgestimmt; der Loader bleibt insgesamt zehn Sekunden sichtbar.
- Mehrere zusätzliche Startgeräusche sind enthalten: dumpfer Aktenkontakt mit dem Tisch, Metallclip, Papierrascheln und zusätzliches Umblättern. Sämtliche neuen WAV-Effekte wurden synthetisch erzeugt und nicht aus fremden Samples übernommen.
- Das Porträt von Kael Veyron verwendet eine vom Nutzer bereitgestellte Originaldatei, unverändert kopiert. Das Aussehen des Charakters wurde nicht neu generiert oder retuschiert.
- Die dritte Website-Karte UC2-Mix wurde entfernt. Das Original-Skin-Template bleibt im Ordner mc-vorlage/ zur Verfügung.
- Das vorhandene Schattenzeugen-Dossierbild bleibt in der Übersicht. Es liefert Hinweise zu Varkhon; die Verbindung zu Kael Veyron wird weiterhin als ungeklärt bezeichnet.
- Übersicht und Rekonstruktion sowie das Control-Deck bleiben erhalten. Die Rekonstruktion gleicht die 16 Fundstückwörter nach dem Eintragen automatisch ab; ein manueller Prüfen-Knopf entfällt.

Assets
- assets/kael-veyron-portrait.png: unverändertes, vom Nutzer bereitgestelltes Charakterrender.
- assets/shadow-witness-dossier.png: vorhandenes Schattenzeugen-Dossierbild.
- assets/opening-*.wav: lokal erzeugte synthetische Öffnungs- und Papiergeräusche.
- assets/Beatific.mp3: vom Nutzer bereitgestellte Hintergrundmusik. Der frühere Loading-Ton hvjkjh.mp3 wurde aus dem Startup-Ablauf und Paket entfernt; stattdessen leitet intro-dark-mystery.mp3 den Einstieg.
- mc-vorlage/: Minecraft-Skin-Dateien zur weiteren Nutzung.


REVISION 11: Die drei Fundstück-Ansichten aus der älteren Archivfassung sind wieder enthalten: Die Gestalt, der abgerissene Zettel, Symbolanalyse, Zeugenaussage und letzte Sichtung. Glitch-/Layout-Korruptions-Effekte und die zugehörigen Sounds wurden entfernt. Der Start zeigt eine Akte, die auf dem Tisch landet, der Einband öffnet sich, danach klappt ein Beweisblatt sichtbar nach links und bleibt flach auf der linken Seite liegen. Das Fundstück-Bild assets/varkhon-evidence.png bleibt unverändert eingebunden.


REVISION 12 — PHYSICAL BOOK OPENING
- The book cover is a double-sided 3D object: the front cover swings from the right-hand half around the spine, exposing its paper-lined inside. The book settles toward the center, then a separate page flips from right to left and remains flat. The scene keeps a solid contact shadow against the desk.
- The main dossier and original character portraits can be clicked or keyboard-activated to open a full-size viewer. The image is shown with object-fit: contain; it is not cropped. The “Die Gestalt” figure/artifact image remains unchanged in the paper layout.
- The startup sound sequence uses the uploaded “Dark Mystery Intro” as quiet ambience, “Edge of Panic” as a low transition layer, the uploaded book-opening and page-turn sounds, and a short radio-static sample. The uploaded Dark Mystery Intro leads the startup audio; the previous loading sound is removed. Beatific.mp3 starts after the 10-second intro as before.
- The very long uploaded radio-static recording is trimmed to six seconds for the existing radio-preview button, with a shorter excerpt used in the intro.
- CSS/JavaScript glitch and layout-tearing effects remain removed. The rest of the site layout, evidence tabs and reconstruction are preserved.

Audio provenance note: the new MP3s were supplied by the site owner in this conversation. The filenames indicate third-party/community sources for some effects; check the original source license and add attribution where required before public redistribution.


REVISION 13
- Removed the old loading sound; the uploaded dark-mystery intro now leads the startup audio.
- The 16 reconstruction words are auto-evaluated when all fields are filled; no manual check button remains.
- Redesigned word slots as numbered paper slips.
- Aligned the book spread and rotating leaf to an exact 50/50 spine; the page flip no longer tilts off the center.
