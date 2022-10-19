### Vorlage für Aufgabenblätter (Stand: 19.10.2022)

#### Struktur 

* `AGFA-Abl-Master` Msterfile, in dem via. `\input{name}` das Aufgabenblatt `name` umgewandelt wird.

* Alle Aufgabenblätter sind in `./content` gespeichert. Bitte sich das Muster ansehen und beachten!

* Name: `ablatt-nr.tex`, wobei `nr` die Nummer des Aufgabenblattes ist. 

* In `./preamble` ist die datei `Abl-layout.tex` und `Abl-defn.tex` gespeichert. 

In der ersten Datei sind die notwendigen Pakete und Angaben für das Layout gemacht. Falls weitere Pakete erforderlich sein sollten, dann bitte hier einbauen. 

In der zweiten Datei befinden sich einige Definitionen für mathematischen Text, den man entsprechend des Bedarfs ergänzen muss. 

* Querverweise mit dem üblichen `\ref{key}`; sollte momentan ausreichend sein. 

* Nicht eingebaut: Literaturverweise. Ich denke, darauf kann man verzichten bzw. mit der `LaTeX` Umgebung `thebibliography` bei Bedarf selbst anlegen. Auf Wunsch baue ich es aber noch ein.

* Bitte für Aufzählungen römische Zahlen (i) und für Äquivalenzen (a) nehmen, d.h. 
```
\begin{enumerate}[(i)]
\item
\end{enumerate}
```
bzw.
```
\begin{enumerate}[(a)]
\item
\end{enumerate}
```

