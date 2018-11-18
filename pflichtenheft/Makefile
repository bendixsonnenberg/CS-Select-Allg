make: pflichtenheft.tex pflichtenheft.gls uml/export/Architektur.png uml/export/Organisation.png uml/export/Spiel.png uml/export/FeatureSelect.png
	pdflatex pflichtenheft.tex

pflichtenheft.gls: pflichtenheft.glo
	makeglossaries pflichtenheft.glo

pflichtenheft.glo: pflichtenheft.tex
	pdflatex pflichtenheft.tex

uml/export/Architektur.png: uml/Architektur.uxf
	umlet -action=convert -format=png -filename=uml/Architektur.uxf -output=uml/export/Architektur.png

uml/export/Organisation.png: uml/Organisation.uxf 
	umlet -action=convert -format=png -filename=uml/Organisation.uxf -output=uml/export/Organisation.png
uml/export/Spiel.png: uml/Spiel.uxf
	umlet -action=convert -format=png -filename=uml/Spiel.uxf -output=uml/export/Spiel.png
uml/export/FeatureSelect.png: uml/FeatureSelect.uxf
	umlet -action=convert -format=png -filename=uml/FeatureSelect.uxf -output=uml/export/FeatureSelect.png
