# Vorlagen für studentische Arbeiten

In diesem Repo finden Sie Vorlagen zur Erstellung von Dokumenten in LaTeX. Folgende Vorlagen stehen zur Auswahl:

- `Article.tex`: Vorlage für kleinere Dokumente wie bspw. ein Proposal (Vorschlag) für eine Praxis- oder Abschlussarbeit
- `Report.tex`: Vorlage für ein größeres Dokument wie bspw. eine Projektdokumentation
- `Thesis.tex`: Vorlage für eine Abschlussarbeit (Bachelor- oder Masterarbeit)

In der Datei `htwk.sty` sind alle Zusatzpakete enthalten sowie die entpsrechenden Einstellungen zu finden. Somit bleibt die Hauptdatei übersichtlich.

### Minted und Pygments
Zur Formatierung von Quellcode wurde die `minted`-Umgebung (https://ctan.org/pkg/minted) eingebunden. Zur Formatierung von Quellcode benötigt `minted` das Programm Pygments (https://pygments.org), welches sich mit `pip` installieren lässt:
```shell
pip3 install pygments
```
Für die Konvertierung von LaTeX in ein PDF ist bei der Verwendung von `minted` zusätzlich noch die Option `-shell-escape` notwendig:
```shell
pdflatex -shell-escape Report.tex
```

### Weiterentwicklung und Fehler
Diese Vorlagen dienen als Basis, die Sie selbstverständlich gerne erweitern oder ändern können.

Finden Sie Fehler oder haben Sie nützliche Ergänzungen, von denen alle profitieren, können Sie mir gerne die überarbeitete Vorlage als neues Template zur Verfügung stellen. Ich würde mich freuen.