Protokoll vom 3.2., sollte weiterverwendet werden.

# Übersicht
- Dateien für Ergebnisse usw. in #Ressourcen im Slack
- MannuelleViewTests https://studentkit-my.sharepoint.com/:x:/g/personal/utzfk_student_kit_edu/EZHEOxC2IIlKgxoD2Yn0LuUBEm9PCVOnaLMjEzlAmGFbNQ?e=AvamrL
- am wichtigsten ist Nutzerfreundlichkeit und Korrektheit (!).

# Aufgaben
## Vorbereitung
- Mock für die Bibliothek (Benni) - schafft er nicht
- Tests aus Pflichtenheft in ManuelleViewTests eintragen (David) - done
- Testaufgaben einteilen (alle) - !
- Fakedaten für Algorithmen (Aufzeichnungsmöglichkeit in App schreiben) - über Äpp (unterpunkt Valle)
- Mappe / Dokument für Praxistest entwerfen (Umgebung, was sagen wir den Testpersonen, wo lang laufen (bitte eher Strecke entlang, draußen, geradeaus) (david!)
  - Tests z.B.: 2\*10 liegestütze, 2\*10 Tisups, 2\*50 Schritte geradeaus (wo platz ist)
  - Trainingsablauf
  - 10 Schritte mit pausen und anderen Bewegungen, eine Minute lang -> Dokumentieren, was für Bewegungen gemacht wurden.
  - Bei Situps: 1 situp sauber vormachen ("ganz hoch")
  - Anweisung: "mach, was die App sagt". Bei 2. Durchlauf Hinweise geben und dokumentieren. 
  - Fakedaten aufnehmen für 2 Situps, 2 Liegestütze, 2 Schritte
- in testfiles (RealLiveTests) soll übersichts-statistik automatisch berechnet werden. (David)
## Testaufgaben
- Bib testen (Erwin) (eigenes Ding um Bib zu testen. Steuerungsparameter, Rohtaden.)
- Unit-Tests schreiben (siehe Einteilung)
  - model:
    - Bib 
      - ??(Was, wenn Kopfhöhrer falsche sachen zurückgeben  - keine Priorität, sollte laut tobi gemacht werden)
      - IMUDataExtractor (klein, Bytefolge auf Werte) (unassigned)
    - Erweiterungsmodul 
      - Algorithmen (mit Fakedaten prüfen) (valle)
      - ActivityManager (klein)
    - DBService
    - SettingsService nicht (noch schlimmer als Bibliothek)
    - Servicemanager (klein)(benni)
  - viewmodel: 
    - StepModeViewModel (Pionier-Mock)(abgucken von DatabaseConnectionTest)
    - dann Aufwandschätzung, andere viewmodels testen...
  - view: keine (nur manuelle view tests.)
- Szenarien testen und Wunsch/Mussanforderungen daraufhin abhaken. (manuell) (David, Jan, Benni)
- Praxis: Testpersonen (jeder mit einer Testperson)
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