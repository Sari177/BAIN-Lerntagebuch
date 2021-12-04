# Hier sind alle Übungen

## Aufgabe vom 05.11.2021
Import/Export in ArchivesSpace

Am 05. November bekamen wir die erste Übung, die Dokumentiert werden darf. In dieser Übung geht es darum, dass in ArchivesSpace die Accession und Resource erstellt werden. 
Dies wurde eigentlich bereits im Unterricht durchgeführt, da es bei mir aber zu langen Wartezeiten und zu einem Time-out der VDI führte, holte ich dies noch nach.
Es könnte sein, dass ich die Einträge auch schon während dem Unterricht hätte durchführen können. 
Ich konnte auch dieses Mal die Dropdowns nicht öffnen, was mich wieder stutzig machte. Durch herausprobieren, ging es dann mit den Pfeiltasten 
und mit Eingabe der ersten Buchstaben in das Dropdown Feld. 
Dies hatte ich nicht erwartet. Nach diesem aha Erlebnis, konnte ich mühelos die Accession und Resourcen anlegen und durch das jeweilige publishen, auch auf dem Port 8081 sehen.
Danach gab es zwei weitere Übungen. Einmal zum Import von EAD-Beispieldaten ins ArchivesSpace und anschliessend werden diese importierten Daten in MARCXML exportiert.
Ich konnte nicht feststellen, wo die Dateien auf der angegebenen Seite ( https://eadiva.com/sample-ead-files/) heruntergeladen werden konnten. 
Deshalb habe ich sie einfach in eine Text Datei gepackt und eine «.ead» Datei daraus gemacht. Danach habe ich diese auf ArchivesSpace hochgeladen, also importiert. 
Da dies einige Minuten ging, fing ich bereits an hier zu dokumentieren. Die Anzeige in ArchivesSpace habe ich mit der HTML Ansicht kurz verglichen. 
Die EAD Datei enthält nur eine “Resource”, aber keine “Digital Objects” und die Zeitspanne ist unterschiedlich.
Diese Importierte Datei exportierte ich in einem zweiten Schritt. Dies war zu finden unter Resources > der Datei > Edit > Export > Download MARCXML.

![Export ArchivesSpace](Uebung1.png?raw=true)

 
Als ich die MARCXML Datei verglich mit dem Eintrag in ArchivesSpace fiel mir auf, dass bei den Extends der Begriff in Portion nicht im XML vorhanden ist und auch 
die Finding Aid Data sah ich nicht in der MARCXML Datei. In diesem Falle muss festgestellt werden, dass der Export Informationsverlust mit sich zieht.



## Aufgabe vom 19.11.2021
Bei dieser Übung ging es darum, die erstellte Publikation in DSpace  über die OAI-PMH Schnittstelle  zu exportieren. 
Das würde normalerweise nicht händisch gemacht, sondern per Algorithmus automatisch in ein anderes System übertragen. 
Ich entschied mich, gleich am nächsten Tag den Download durchzuführen, sodass ich nicht nochmals eine neue Community, sowie Collection mit einer Publikation anlegen muss. 
Leider war aber der ganze Tag der Service unavailable. Als ich am nächsten Tag nochmals auf die Seite zugriff, waren wie angekündigt alle Communitys und Collections gelöscht. 
So entschied ich mich einfach eine Beispieldatei, welche in OAI-PMH zu finden war, herunterzuladen. 
Mehr gibt es zu dieser Übung eigentlich nicht zu sagen 😊 kurz und knackig



## Aufgabe vom 03.12.2021
Konfiguration Suche und Facetten
Für diese Übung durften wir uns zuerst dieses Video anschauen: https://www.youtube.com/watch?v=qFbW8u9UQyM&list=PL5_8_wT3JpgE5rv38PwE2ulKlgzBY389y&index=5

Ich fand es sehr spannend wie einfach es gemacht wurde, dass die Suche durch das «searches.ini» file mit vorgegebenen Parametern einfach modifiziert werden kann. 
Hierzu wurden im Video ein paar Details aufgezeigt. 
Wie zum Beispiel wieviel Records auf der Seite angezeigt werden, welche Metadaten in den Records angezeigt werden sollen oder auch wie man die Sortierung der Suche einstellen will. 
Sehr spannend fand ich auch die Kontrolle darüber, wie die Suchresultate angezeigt werden sollen wenn man sich für die Freitextsuche entscheidet. 
Diese kann auch individuell modifiziert werden, welche Vorschläge z.B. angezeigt werden sollen, wenn keine Treffer gefunden worden. 
Nachher wurde auch im Video eine kopie von der Datei «facets» angelegt. Diese Facetten ist die Tabelle auf der rechten Seite in VuFind. 
All diese Konfiguration kann auch individuell modifiziert werden, neu angeordnet oder die Labels nach belieben gewechselt werden. 
Es können auch eigene Checkboxen für die Suche erstellt werden. Zum Beispiel «no Author». So können auch Records angezeigt werden, welchen keinen Author hinterlegt haben. 
Oder auch Checkboxen welche das Format auswählbar macht in der Suche (z.B. Ebook, Book, Book Chapter etc.)

