# AbnehmCoach Peter V1.1.2

Diese Version korrigiert die lokale Speicherung und die Darstellung der Kalorien-/Gewichtsdaten.

## Wichtigste Änderungen

- Das Schnellimport-Feld bleibt direkt ganz oben.
- Die Kalorienvisualisierung verwendet jetzt keine Canvas-Grafik mehr, sondern normale HTML-Balken. Dadurch ist die Anzeige in Safari, Chrome und auf dem iPhone robuster.
- Es gibt eine neue Datenspeicher-Prüfung direkt unter den Tageskacheln:
  - Mahlzeiten gesamt
  - Kalorien gesamt
  - Eiweiß gesamt
  - Tage mit Essen
- Die Kaloriengrafik zeigt alle gespeicherten Essenstage, nicht nur ein festes Datumsfenster.
- Wenn 280 kcal lokal gespeichert sind, müssen sie in der Datenspeicher-Prüfung und in der Balkengrafik sichtbar sein.
- Die Gewichtsgrafik zeigt schon bei einem einzelnen Gewichtswert einen Hinweis mit dem gespeicherten Wert; eine Linie erscheint weiterhin erst ab zwei Gewichtswerten.

## Sehr wichtig beim Umstieg

Die App speichert lokal im Browser. Damit bestehende Daten erhalten bleiben, am besten die bestehende `index.html` in deinem bisherigen Abnehmcoach-Ordner durch diese neue `index.html` ersetzen. Wenn du die Datei in einem komplett neuen Ordner öffnest, kann der Browser lokale Daten eventuell als neuen Speicherort behandeln.

## Bedienung

1. ChatGPT-Auswertung oben einfügen.
2. „Schätzung übernehmen“ klicken.
3. Datum und Mahlzeitenart prüfen.
4. Optional Foto ergänzen.
5. „Mahlzeit speichern“ klicken.
6. In der Datenspeicher-Prüfung kontrollieren, ob Mahlzeiten und Kalorien gezählt werden.

## Importformat

Kalorien: ca. 280 kcal
Eiweiß: ca. 37 g
Bewertung: passt gut
Tipp: Sehr guter Start. Eiweißreiches Frühstück, passt gut in den Tagesplan.

## Hinweis

Die App analysiert Bilder noch nicht automatisch. Die Schätzung kommt weiterhin aus dem ChatGPT-Chat; die App speichert und visualisiert die Werte lokal.
