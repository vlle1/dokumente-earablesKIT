# wenn man im Laufmodus startet und stoppt und den Modus NICHT wechselt, stürzt die App 10 Sekunden später ab (Erwin)
 - Schritte zur rekonstruktion
  - 1. App starten
  - 2. Kopfhörer verbinden
  - 3. Laufmodus starten
  - 4. 30 Schritte machen
  - 5. Laufmodus beendet und PopUp noch nicht weggecklickt
  - 6. Warten
  - 7. App stürtzt ab wegen Null Pointer exception
# edit entry in listenandperform (jan):
dialog wegklicken führt zu löschung, sollte aber da bleiben,
Dialog überarbeiten (edit führt zu "add acitivity") (drüber reden)


# ignore everything down here it is just small things I will change them later..
### Resources (valle)
Ausrufezeichen weg usw.
### Frequenz (valle)
-- statt 0, falls stehend
Berechnung anpassen (regression über letzte 5 Schritte).

### Püp-üp (valle)
beim Verbinden: anzeigen, dass Verbindung gerade hergestellt wird, damit Nutzer nicht weg klickt.

### Impressum (benni)
Impressum fehlt noch... (benni)

### Sampling Rate (valle)
Einstellen funkitoniert noch nicht zuverlässig (hinkt immer eine Einstellung hinterher oder so?)

### Muic Mode ( unassigned - nicht soo wichtig)
Gif seems to take some time loading!
Message when going out of music mode should be removed! (was a debug message)

### Stepmode done / sachen formatieren:
"you have taken 123 seps done".
 Data Overview (valle)
Shouldn't say "welcome to", strings besser formatieren


### Listenandperform (valle - lowes prio)
Darstellungsform der Buttons ändern: add sollte in der Tabelle angezeigt werden, damit klar ist, dass man was am ende anfügt.
Should default workout be empty or like it is right now?

