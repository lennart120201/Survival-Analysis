# Survival-Analysis

## Struktur

Das auszuführende Notebook befindet sich mitsamt den Daten, sowie einer PDF des Notebooks im Source-Ordner.
Da es sich nur um eine Datei handelt, ist bei der Ausführung lediglich zu beachten, dass Jupyter-Notebook oder Jupyter-Lab, sowie sämtliche Requirements installiert sind.
Im Order Dokumentation befindet sich der auch im Code referenzierte Projektbericht, sowie die Präsentation des Projekts.

## Zielsetzung

Das menschliche Leben wird häufig durch Krankheiten beeinflusst oder gar beendet. In
diesem Projekt geht es um die Zusammenhänge zwischen einer Krankheit und bestimmten
Attributen, sodass Vorsorgemaßnahmen angepasst werden können. Dadurch wird sich eine
Steigerung der Lebensqualität sowie ein optimierter Umgang mit Krankheiten und weiteren
unumgänglichen Ereignissen erhofft. Es soll eine Prognose über den möglichen Zeitraum
des Todes einer Person mit einer bestimmten Krankheit getroffen werden, sodass diese
Person ihre restliche Lebenszeit mit mehr Gewissheit verbringen kann. Die hauptsächliche Motivation liegt darin, durch die erkannten Zusammenhänge zwischen Attributen und
bestimmten Krankheiten rechtzeitig Maßnahmen einleiten zu können, sodass ein schwerwiegender oder gar tödlicher Verlauf einer Krankheit verhindert werden kann. Um diese
Motivation zu verkörpern, nannte sich das Projektteam "Lifesaver", denn dieses Projekt
soll Leben retten.

##Anmerkungen zur Umsetzung

Zunächst wurden angemessene Daten gesucht. Es stellte sich heraus, dass medizinische "Time-to-Event"-Daten, welche für dieses Projekt benötigt wurden, sehr schwer zu beschaffen sind und meistens nur auf Anfrage oder ähnliche Umwege erhalten werden können. Nach einigen Recherchen sind wir auf eine Studie über Herzkrankheiten gestoßen.

Daraufhin wurde die Struktur der Daten geprüft. Es stellte sich heraus, dass der Datensatz vollständig bereinigt war. Außerdem wurden sämtliche Bedeutungen der Attribute und Abkürzungen recherchiert. (siehe Projektbericht Anhang A.1)

Danach folgte ein erster Test mittels univariaten Modellen, sowie eine deskriptive Analyse der Daten. Anhand von späteren Tests mittels des finalen Cox-Modells wurden statistisch signifikante Attribute ausgewählt und eine finale Analyse mit besagten Modell, sowie eine Validierung des Modells durchgeführt und grafische Auswirkungen der einzelnen Attribute und Faktoren ausgegeben.

## Autoren

Laura-Marie Struss

Lennart Schulz

Marcel Winter
