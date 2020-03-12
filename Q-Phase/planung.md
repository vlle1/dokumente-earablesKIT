Protokoll vom 3.2., sollte weiterverwendet werden.

# Übersicht
- Dateien für Ergebnisse usw. in #Ressourcen im Slack
- MannuelleViewTests https://studentkit-my.sharepoint.com/:x:/g/personal/utzfk_student_kit_edu/EZHEOxC2IIlKgxoD2Yn0LuUBEm9PCVOnaLMjEzlAmGFbNQ?e=AvamrL
- am wichtigsten ist Nutzerfreundlichkeit und Korrektheit (!).

# Aufgaben
## Vorbereitung
%% H Häkchen, X weggelassen, A in Arbeit

- X Mock für unsere Bibliothek (Benni) - NOPE
- H Tests aus Pflichtenheft in ManuelleViewTests eintragen (David) - done
- H Testaufgaben einteilen (alle) - !
- H Fakedaten für Algorithmen (Aufzeichnungsmöglichkeit in App schreiben) - über App (Valle) 
- H Mappe / Dokument für Praxistest entwerfen (Umgebung, was sagen wir den Testpersonen, wo lang laufen (bitte eher Strecke entlang, draußen, geradeaus) (david!)
  - Tests z.B.: 2\*10 liegestütze, 2\*10 Tisups, 2\*50 Schritte geradeaus (wo platz ist)
  - Trainingsablauf
  - 10 Schritte mit pausen und anderen Bewegungen, eine Minute lang -> Dokumentieren, was für Bewegungen gemacht wurden.
  - Bei Situps: 1 situp sauber vormachen ("ganz hoch")
  - Anweisung: "mach, was die App sagt". Bei 2. Durchlauf Hinweise geben und dokumentieren. 
  - Fakedaten aufnehmen für 2 Situps, 2 Liegestütze, 2 Schritte
- in testfiles (RealLiveTests) soll übersichts-statistik automatisch berechnet werden. (David)
## Testaufgaben
- A Bib testen (Erwin) (eigenes Ding um Bib zu testen. Steuerungsparameter, Rohtaden.)
- A Unit-Tests schreiben (siehe Einteilung)
  - model:
    - A Bib 
      - ??(Was, wenn Kopfhöhrer falsche sachen zurückgeben  - keine Priorität, sollte laut tobi gemacht werden) (Test für checksum schreiben)
      - H IMUDataExtractor (klein, Bytefolge auf Werte) (done)
    - Erweiterungsmodul 
      - A Algorithmen (mit Fakedaten prüfen) (Valle)
      - ende: ActivityManager (klein)
    - nochmal überarbeiten: DBService
    - X SettingsService nicht (noch schlimmer als Bibliothek)
    - Servicemanager (klein)(benni)
  - viewmodel: 
    - StepModeViewModel (Pionier-Mock)(abgucken von DatabaseConnectionTest)
    - dann Aufwandschätzung, andere viewmodels testen...
- A Szenarien testen und Wunsch/Mussanforderungen daraufhin abhaken. (manuell) (David, Jan, Benni)
- A Praxis: Testpersonen (jeder mit einer Testperson)
## Abschlussaufgaben
- Testabdeckung ermitteln (für "testbare" Bestandteile)

# Fragen (Tobi, Anja)
- Rekursionstests haben wir nicht so wirklich gemacht. Wie sollen wir mit dem Teil jetzt weitermachen (Ignorieren / im Nachhinein schreiben)? Nacharbeiten
- Was sollen wir mocken? Vollständige Schnittstelle der Bibliothek
- Wie auf iOS testen? mock / live / lassen? do it.


# 5.3. Tobi, Anja

- Auch Integrationstest sollten gemacht werden!
- veränderungen an Testszenarien dokumentieren
- Tests möglichst umfassend dokumentieren
- Implementiernungsprotokoll überarbeiten (mittlere Priorität)

# 12.3. Tobi, Anja

- nix neues :D