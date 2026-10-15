ARCHIV 016 — Autostart-Fix

- Beim Öffnen wird versucht, den Loading-Sound hvjkjh.mp3 direkt zu starten.
- Der Loading-Screen ist für 10 Sekunden vorgesehen.
- Nach 10 Sekunden wird Beatific.mp3 automatisch als Hintergrundmusik gestartet.
- Die Musiksteuerung bleibt als Ein/Aus-Schalter vorhanden.

Browser-Hinweis:
Chrome, Safari und andere Browser blockieren häufig Audio mit Ton, wenn eine Website geöffnet wird, bevor der Nutzer irgendwo geklickt oder getippt hat. Deshalb versucht die Seite den Ton direkt beim Laden; falls der Browser das blockiert, startet die Sequenz beim ersten Klick/Tippen oder Tastendruck. Das lässt sich nicht zuverlässig durch Website-Code umgehen.
Beim Deployment müssen index.html und assets/ gemeinsam hochgeladen werden.
