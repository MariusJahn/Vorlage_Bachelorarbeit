# Vorlage_Bachelorarbeit

Dies ist eine Vorlage für eine Bachelorarbeit an der Westfälischen Hochschule in Gelsenkirchen. Die Vorlage basiert auf der KOMA-Script-Klasse `scrreprt` und ist für die Verwendung von `biblatex` zur Literaturverwaltung konfiguriert. Die Vorlage enthält Beispiele für die Verwendung von Bildern, Tabellen, Quellcode und Literaturverweisen. Die Vorlage ist so konfiguriert, dass sie mit `Texmaker` und `Miktex` verwendet werden kann.

Die Vorlage ist an dem Beispiel von [Nico Hülscher](https://de.overleaf.com/latex/templates/vorlage-bachelorarbeit-informatik-westfalische-hochschule/ympzbtzjqhdd) und wurde von mir nach meinen Bedürfnissen geändert.

## Voraussetzungen

- Miktex als Tex-Distribution (https://miktex.org/)
- Texmaker als Editor (https://www.xm1math.net/texmaker/)
- Perl als Skriptsprache (https://www.perl.org/get.html)

## Wichtige Pakete

- `inputenc` und `fontenc` für die Kodierung
- `babel` für die Sprache
- `csquotes` für Anführungszeichen
- `graphicx` für Bilder
- `hyperref` für Links
- `longtable` für Tabellen über mehrere Seiten
- `biblatex` für die Literaturverwaltung

## Befehle zum kompilieren

`lualatex -synctex=1 -interaction=nonstopmode %.tex|makeglossaries %|biber %|lualatex -synctex=1 -interaction=nonstopmode %.tex|lualatex -synctex=1 -interaction=nonstopmode %.tex|"C:/Program Files/Adobe/Acrobat DC/Acrobat/Acrobat.exe" %.pdf`
