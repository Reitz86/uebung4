# Übung 4
Bitte forken Sie sich das Repository. In ihren Fork checken Sie bitte den Quellcode ihrer Lösung ein. Die Fragen können Sie in einer einfachen Textdatei beantworten oder auch gerne direkt in der readme.md einfügen (aber bitte kenntlich machen. Also markieren!). Die Lösungen zu den Diagrammen checken Sie bitte als separate Bilder ein. Der Link zu ihrem Repository mit der Angabe ihres letzten Commits (der Hash) ist bis zur Abgabe per Mail einzureichen.

Viel Erfolg!


## Aufgabe 1
Entwerfen Sie ein Anwendungsfalldiagramm zu der folgenden Beschreibung:
In einem Kino kann ein Gast Kinokarten an der Kasse kaufen, die vorbestellt sein könnten. Außerdem
ist es möglich Popcorn und Getränke zu bestellen. Danach bezahlt der Kunde beim Kassierer die
Rechnung. Es ist auch möglich mit Kreditkarte zu bezahlen, welche bei Bedarf einer automatischen
Prüfung unterzogen werden kann.

## Aufgabe 2
Entwerfen Sie ein Zustandsdiagramm, das folgenden Sachverhalt über die Bestellung eines Blumenstraußes
über das Internet beschreibt:
Die über das Internet aufgegebenen Bestellungen werden zuerst vom Kundencenter überprüft. Sind
die Bestelldaten nicht korrekt oder ist die Bestellung nicht plausibel, so nimmt das Kundencenter mit
dem entsprechenden Kunden Kontakt auf, um die offenen Fragen zu klären. Ist mit der Bestellung alles
in Ordnung, bzw. sind die offenen Fragen geklärt, dann stellt die Floristin mit Hilfe der Bestelldaten
den Strauß zusammen. Sobald der Strauÿ fertig ist, wird er vom Lieferdienst an die auf der Bestellung
vermerkte Adresse geliefert.

### Entwerfen Sie zu diesem Beispiel auch ein Aktivitätsdiagramm. Erkennen Sie die Unterschiede?

## Aufgabe 3
Welche der folgenden Aussagen über ein Interface ist korrekt?
1. Ein Interface kann private Attribute besitzen
2. Ein Interface kann andere Interfaces redefinieren
3. Alle Merkmale eines Interface müssen die Sichtbarkeit "private" haben
4. Ein Interface kann keine Attribute haben

## Aufgabe 4
Welche Aussagen sind korrekt?
1. An Interface may be implemented by multiple classifiers, but one classifier may only implement one interface.
2. An Interface may be implemented by multiple classifiers, and one classifier may implement multiple interfaces.
3. An interface may be implemented by at most one classifier, and one classifier may implement at most one interface.
4. An interface may be implemented by at most one classifier, but one classifier may implement multiple interfaces.

## Aufgabe 5
Geben Sie in der folgenden Abbildung die Bezeichnungen der dargestellten Elemente an.
![Aufgabe 5](https://github.com/Reitz86/uebung4/raw/master/aufgabe5.JPG)


## Aufgabe 6
Welche der folgenden Aussagen ist korrekt?
![Aufgabe 6](https://github.com/Reitz86/uebung4/raw/master/aufgabe6.JPG)

1. Sobald w zerstört wird, dann wird auch z zerstört.
2. Sobald z zerstört wird, dann wird auch w zerstört.
3. Zu einem bestimmten Zeitpunkt kann eine Instanz von z in genau einer Instanz von w enthalten sein.
4. Zu einem bestimmten Zeitpunkt kann eine Instanz von z in mehreren Instanzen von w enthalten sein.

## Aufgabe 7
Schauen Sie sich die Java Dateien im Ordner RobotAdapter an: Die Spielfiguren in einem Computerspiel müssen alle das Interface Spieler implementieren. Die Klasse Human tut dies. Nun hat eine Zulieferfirma den Code für einen Roboter geschrieben (Robot.java). Leider haben Sie auf diesen keinen Einfluss und müssen den Roboter so in ihr Spiel integrieren. Welches Pattern eignet sich dafür? Implementieren Sie den entsprechenden Code.

# Zusätzliche Materialien (wird nach und nach erweitert, bis alle Inhalte die keine Folien haben hier vorhanden sind. Daher immer wieder reinschauen)
##Literatur zur Programmierung
Knappe Angabe, welche Bereiche des Buchs "Java ist auch eine Insel" von Christian Ullenboom zur Recherche geeignet sind. Es kann vorkommen, dass einzelne Spezialitäten nicht in der Vorlesung behandelt worden sind. Die Zusammenfassung unten versucht den Inhalt so gut es geht auf die in "Einführung in die Programmierung" und "Information Systems Engineering" behandelten Themen zu reduzieren.

###1.5 Das erste Programm compilieren und testen
http://openbook.rheinwerk-verlag.de/javainsel/javainsel_01_005.html#dodtp86b7140e-a27a-4d07-8007-372cf0a9fc88

###2 Imperative Sprachkonzepte (bis 2.7.12)
http://openbook.rheinwerk-verlag.de/javainsel/javainsel_02_001.html#dodtp332f236b-44e2-4fc6-a101-14774985570c

###3 Klassen und Objekte
http://openbook.rheinwerk-verlag.de/javainsel/javainsel_03_001.html#dodtp394ff2f8-9134-4eb3-a6b4-469ed4572a74

###4.5 Konvertieren zwischen Primitiven und StringsZur nächsten Überschrift
http://openbook.rheinwerk-verlag.de/javainsel/javainsel_04_005.html#dodtpa464e970-fb6f-47bd-bf9c-d6cb1f0b5349

###6 Exceptions
http://openbook.rheinwerk-verlag.de/javainsel/javainsel_06_001.html#dodtp97490f9b-54f8-4fd3-a4d6-482f5243e8ee
###-6.1.7 throws im Methodenkopf angeben
http://openbook.rheinwerk-verlag.de/javainsel/javainsel_06_001.html#dodtp4dc6c4dc-085f-4ebb-ac61-1af419ac8372

###5 Eigene Klassen schreiben
http://openbook.rheinwerk-verlag.de/javainsel/javainsel_05_001.html#dodtp44e7828f-b21f-41d3-9c25-d36ace6e35b4

###7.3.2 Die this-Referenz
http://openbook.rheinwerk-verlag.de/javainsel/javainsel_07_003.html#dodtp746f8034-cbf4-4f52-ac3f-64a3c9d5f61b

###8.3 Object ist die Mutter aller Klassen (generell, speziell nur toString())
http://openbook.rheinwerk-verlag.de/javainsel/javainsel_08_003.html#dodtpe2738381-3e34-44c9-9fea-fadba7f7b82d

###10.2 Design-Pattern (Entwurfsmuster)
http://openbook.rheinwerk-verlag.de/javainsel/javainsel_10_002.html#dodtpa1401ab7-6470-4217-bc05-d2973590bbe8

##UML
Hier bitte die Literaturangaben aus dem Skript beachten. Zusätzlich zu den Videos im CLM  sind die folgenden Bücher zum Studium geeignet:
UML @ Classroom: Eine Einführung in die objektorientierte Modellierung (https://www.amazon.de/UML-Classroom-Einf%C3%BChrung-objektorientierte-Modellierung/dp/3898647765)
UML 2 glasklar: Praxiswissen für die UML-Modellierung (https://www.amazon.de/UML-glasklar-Praxiswissen-f%C3%BCr-UML-Modellierung/dp/3446430571/ref=pd_lpo_sbs_14_img_1?_encoding=UTF8&psc=1&refRID=NWWSJCZAZBCMKDWB24Z0)


##Patterns
### Adapter Pattern
1. Einfache Einführung als Video: https://www.video2brain.com/de/tutorial/passt-schon-adapter
2. Technische Beschreibung mit Beispielen (Folie 47-50): https://homepages.fhv.at/hv/Semester4/OOAD/Patterns.pdf

### Observer Pattern
1. Technische Beschreibung mit Beispielen (Folie 35-46): https://homepages.fhv.at/hv/Semester4/OOAD/Patterns.pdf

### Factory Pattern
1. Technische Beschreibung mit Beispielen (Folie 75-83): https://homepages.fhv.at/hv/Semester4/OOAD/Patterns.pdf

### Zusätzliche Literatur
### Zusätzliche Literatur
Entwurfsmuster: Das umfassende Handbuch (https://www.amazon.de/Entwurfsmuster-umfassende-Handbuch-Matthias-Geirhos/dp/3836227622/ref=pd_lpo_sbs_14_img_2?_encoding=UTF8&psc=1&refRID=NWWSJCZAZBCMKDWB24Z0)



