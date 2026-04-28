## 1. Laborübung

Bearbeite die Aufgaben in den **alphabetisch sortierten Notebooks** im Ordner `05_01_LABOR-6`.

### Ziel der Übung
- SCPI-Kommunikation mit dem R&S FPC1500 praktisch verstehen.
- Messdaten aus `TRACE1` auslesen, interpretieren und visualisieren.
- S11-Messungen auswerten sowie Spektrum-, Leistungs- und Rauschkennwerte bestimmen.
- Ergebnisse mit Replay-Daten und mit realen Messungen vergleichen.

### Aufgaben nach Notebook
- `0-fpc1500-eval.ipynb`  
  SCPI-Grundtest: Verbindung prüfen (`*IDN?`), `TRACE1` lesen, Frequenzachse aus Geräteeinstellungen bestimmen und Screenshot-Transfer testen.

- `1-fpc1500-NA-S11.ipynb`  
  S11-Auswertung mit offenem Kabel: Phase und Betrag aus `TRACE1` sind bereits vorgegeben, zu komplexem Reflexionsfaktor kombinieren, in linear/dB und Smith-Chart darstellen. Messaufgabe im Notebook bearbeiten.

- `2-fpc1500-NA-S11.ipynb`  
  S11-Messung für eine zweite Messanordnung analog zu Notebook 1 analysieren. Unterschiede der S11-Kurve begründen und physikalisch interpretieren.

- `3-fpc1500-NA-S11.ipynb`  
  S11-Messung einer SDR-Antenne selbst in einem gewählten Frequenzbereich durchführen. Smith-Diagramm und frequenzabhängiges Verhalten der Antenne analysieren.

- `4-fpc1500-SA.ipynb`  
  Spektrumanalyse eines Oszillators: Messung ist vorgegeben, und die Aufgabe zu Gesamtleistung, Klirrfaktor und SNR/CN0 (gegen Noise-Floor) umsetzen.

- `5-fpc1500-SA.ipynb`  
  Spektrumanalyse eines weiteren Oszillators mit denselben Kennwerten wie in Notebook 4 selbst durchführen. Ergebnisse beider Oszillatoren vergleichen und diskutieren.

-

### Hinweise zur Durchführung
- Nutze zunächst den Replay-Modus, um die Auswertung stabil nachzuvollziehen; führe danach reale Messungen mit `REPLAY=False` durch.
- Dokumentiere pro Notebook die wichtigsten Messergebnisse und deine Interpretation (inkl. Screenshot/Plot).
- Achte darauf, dass die Geräteanzeige (Format/Trace) zur jeweils abgefragten SCPI-Messung passt.

### Abgabe-Checkliste
- Pro bearbeitetem Notebook mindestens **ein Screenshot oder Plot** mit kurzer Interpretation.
- Für `1`, `2`, `3` (S11): zentrale Aussagen zu Betrag/Phase/Smith-Darstellung und Messverhalten.
- Für `4`, `5` (SA): berechnete Kennwerte (z. B. Gesamtleistung, Klirrfaktor, SNR/CN0) inkl. kurzer Bewertung.
- Ergebnisse nachvollziehbar im Antwortdokument zusammenfassen (inkl. verwendeter Einstellungen/Annahmen).