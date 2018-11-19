make: pflichtenheft.tex pflichtenheft.gls uml/export/Architektur.png uml/export/Organisation.png uml/export/Spiel.png uml/export/FeatureSelect.png uml/export/Administration.png uml/export/Spieler_Ubersicht.png
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
uml/export/Administration.png: uml/Administration.uxf
	umlet -action=convert -format=png -filename=uml/Administration.uxf -output=uml/export/Administration.png
uml/export/Spieler_Ubersicht.png: uml/Spieler_Ubersicht.uxf
	umlet -action=convert -format=png -filename=uml/Spieler_Ubersicht.uxf -output=uml/export/Spieler_Ubersicht.png
