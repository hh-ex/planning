# Anleitung, um Coding Kata durchzuführen



### Grundsätzliches

**Intention:** Wende Deine Fertigkeit einzig dazu an, um Deine Fähigkeit in X zu verbessern.



**Sonst:** Hauptsache: Es insgesamt schaffen. Nebensache: Die Fertigkeit zu verbessern.

**Jetzt:** Hauptsache: Die (Teil-)Fertigkeit verbessern. Nebensache: Es insgesamt schaffen.



*Durchführung als Meetup, statt Vortrag; Vorteil: Jeder wirkt aktiv mit, kein "Blockvortrag".*



### Rollen

- Organisatoren
  - Aufgabe, Code-Repo, Einladung
  - Durchführung, Moderation vor Ort:
    - offene Atmosphäre herstellen über: *TBD*
    - klare Anweisungen geben
    - Hilfestellung leisten: Probleme erkennen, ohne darum gebeten zu werden
- Teilnehmer: Teams kommen nicht weiter, wenn sie aus gleich guten sind (daher losen)



### Aufgabe TBD: Beispiel

- alle Skilllevels sollten es in 1 h lösen können (ist interessantes Problem in der richtigen Komplexität)
- ist einfach aufzufassen
- ist klar, verständlich geschrieben; was nicht gewollt ist, eindeutig bezeichnet
- mit konkreten, eindeutigen Beispielen versehen
- setzt wenig *Domänenwissen* voraus
- Umfang
  - füge eine Funktionalität hinzu 
  - nehme etwas weg
  - lasse die Tests grün und reduziere Code um 50 % (refactoring) bei gleicher oder besserer Verständlichkeit des Codes
  - code golfing
  - …



### Ablauf

- Vorbereitung Organisatoren: pico-bello git repo mit fertig aufgesetztem Projekt, Tests, alles benannt, du weißt, was wo ist, bestenfalls mit CI
  `git pull, cd, mix get, mix test # und los geht's`
- Vorbereitung Teilnehmer: notwendige Tools installieren, ggf. mit vagrant?
- Teams auslosen (2-3 pro Team): Ziel: unterschiedliche Skill-Levels
- Schleife
  - Coden
    - Intention: Code auf ein Kriterium hin optimieren / Teilziel erfüllen
    - Driver (tippt): mit wenig Kenntnissen in Sprache; Navigator (hat Erfahrung): führt; ggf. wechseln
    - pull request
  - Präsentation der Ergebnisse der Teams



### Ausführungsvarianten

- nach 1. Runde: zurück auf Los, wdh. unter Verwendung neu gewonnener Erkenntnisse
- mit/ohne Zeitlimit
- eine/mehrere Runden
- nach jeder Runde neue Teams bilden
