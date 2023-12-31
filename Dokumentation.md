# Projekt-Dokumentation

Cedric Tuma, Luca Jeanneret, Fabian Meyer und Elias Spycher

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|   15.09.2023    | 0.0.1   |    Wir haben das Projekt geplant    |
|   22.09.2023    | 0.0.2   |    Wir haben realisiert             |
|   29.09.2023    | 0.1.1   |    Wir haben realisiert             |
|   27.10.2023    | 0.1.2   |    Wir haben realisiert             |
|   03.11.2023    | 1.0.0   |    Wir haben realisiert             |

## 1 Informieren

Wir haben uns überlegt, was mir machen wollen un sind in der Aufgabenstellung auf den Verweiss auf Roblox gekommen. Für dies haben wir uns auch entschieden. Für das genauere Game haben wir uns einen Ameisenbär [Tycoon](https://de.wikipedia.org/wiki/Tycoon) vorgestellt, dies wäre gut umsetzbar und wäre auch auf einem guten Schwierigkeitsgrad. Für das müssen wir uns in die Umgebung von Roblox Studio einarbeiten und Ameisenbär Modelle mit [Blender](https://www.blender.org/) erstellen

### 1.1 Ihr Projekt

Ein Ameisenbär Tycoongame, in dem man immer mächtiger wird und das grösste Ameisenbärmonopol aufbauen kann.

In diesem Projekt lernen wir mehrere neue Technologien kennen, darunter Blender, eine professionelle grafikdesign Plattform, Roblox Studios und mehr. In dem Tycoon soll man verschiedene Ameisenbären kaufen und verwalten. Es sollte Möglichkeiten geben diesen Futter zu geben und neue Technologien freischalten zu können um mehr Geld zu verdienen um noch mehr Tiere zu kaufen. Es sollte Käufe mit Echtgeld geben um In-App-Käufe zu tätigen und somit auch ein wenig Geld zu verdienen.

### 1.2 Anforderungsanalyse

| A-№ | Verbindlichkeit | Typ | Beschreibung |
| ---- | --------------- | --- | -------------- |
| 1    | muss | Funktional | Als Nutzer möchte ich, dass ich das Game starten kann, um es zu spielen. |
| 2    | muss | Funktional | Als Nutzer möchte ich, dass man ein kleines Tutorial bekommt, was man machen muss und was das Ziel ist, um zu wissen, wie man spielt. |
| 3    | muss | Funktional | Als Nutzer will ich, dass es einen Moneyproducer und Collector gibgt, dass man Geld verdienen kann. |
| 4    | muss | Funktional | Als Nutzer will ich, dass es eine Währung gibt, damit ich Sachen kaufen kann. |
| 5    | muss | Qualität | Als Nutzer will ich, dass die Ameisenbären gut modelliert wurden und cool aussehen, damit das Spiel gut aussieht. |
| 6    | muss | Funktional | Als Nutzer will ich, dass ich am Anfang einen ersten Ressourcengenerator habe, um erstes Einkommen zu generieren und direkt beginnen zu können. |
| 7    | muss | Funktional | Als Nutzer möchte ich, dass viele verschiedene Upgrades zur Verfügung stehen, damit ich eine Progression im Spiel habe. |
| 8    | muss | Funktional | Als Nutzer möchte ich, dass das Spiel einen Mehrspielermodus hat, damit ich mit meinen Freunden spielen kann. |
| 9    | kann | Qualität | Als Nutzer möchte ich, dass es Achievements gibt, um zusätzlichen Spaß und Herausforderungen im Spiel zu haben. |
| 10   | muss | Qualität | Als Nutzer möchte ich, dass das Spiel eine erkundbare Map enthält, damit ich mich bewegen kann auf der Karte. |
| 11   | kann | Randbedingung | Als Nutzer möchte ich, dass es Geheimnisse (Eastereggs) auf der Karte gibt, die ich entdecken kann, um die Erforschung spannender zu gestalten. |

### 1.3 Testfallspezifikationen

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |        Roblox offen      |    Game starten     |        Game bereit zum spielen           |
| 2.2  |        Game zum ersten mal geöffnet      |    -     |        Kleines tuturial           |
| 3.3  |        Game gestartet    |    -     |         Money Producer produziert Objekt        |
| 3.4  |        Money Producer hat Objekt erstellt       |    -    |      Collector nimmt löscht Objekt          |
| 4.5  |        Objekt wurde gelöscht      |    Spiel gestartet     |      Money +1             |
| 5.6  |        Game geöffnet      |    -    |      Der Ameisenbär sieht Cool aus          |
| 6.7  |        Game geöffnet      |    -    |      Der Money Producer steht schon und produziert Ressourcen            |
| 7.8  |        Game geöffnet      |    Auf Druckplatte stehen    |      Es wird ein Upgrade gemacht           |
| 8.9  |        Game geöffnet      |    -    |      Fruende können Joinen           |
| 9.10 |        Etwas spezielles gemacht      |    -    |      Achievemt claimed             |
| 10.11|        Game geöffnet      |    -    |      geladene Map mit Umgebung             |
| 11.12|        Game geöffnet      |    -    |      Eastereggs auf der Map versteckt             |


### 1.4 Diagramme

![Screenshot besserLA1301 2023-09-15 093958](https://github.com/Biberkatze/1301/assets/110892742/c88d2d72-9406-4ad3-b4da-676031a69759)



## 2 Planen

| AP-№ | Frist    | Zuständig      | Beschreibung                                    | Geplante Zeit |
| ---- | -------- | -------------- | ----------------------------------------------- | ------------- |
| 1.A  | 15.09.23 | Luca J.W.      | User Stories schreiben                          | 45 min        |
| 2.A  | 15.09.23 | Luca J.W.      | Testfälle schreiben                             | 30 min        |
| 3.A  | 15.09.23 | Cedic Tuma     | Use-Case-Diagramm erstellen                     | 30 min        |
| 4.A  | 15.09.23 | Luca J.W.      | Planung erstellen                               | 45 min        |
| 5.A  | 15.09.23 | Alle           | Roblox Studio installieren/starten und alle im Spiel haben | 30 min        |
| 6.A  | 22.09.23 | Luca J.W.      | Wege für verschiedene Orte im Spiel erstellen   | 30 min        |
| 7.A  | 22.09.23 | Fabian Meyer    | Förderbandsystem erstellen                      | 100 min       |
| 8.A  | 22.09.23 | Cedic Tuma/ Fabian Meyer | Geldcounter und Geld erstellen           | 180 min       |
| 9.A  | 27.10.23 | Fabian Meyer/ Elias Spycher | Upgrader und Geldspawner erstellen   | 240 min       |
| 10.A | 27.10.23 | Luca J.W.      | Gebäude für den Kauf von Alais plaziert       | 60 min        |
| 10.B | 27.10.23 | Luca J.W.      | Gebäude für die Futterbeschaffung für Alais platziert | 60 min        |
| 10.C | 29.09.23 | Luca J.W.      | Gebäude für die Abholzung platziert             | 60 min        |
| 11.A | 29.09.23 | Cedic Tuma     | GUI erstellen                                   | 180 min       |
| 12.A | 29.09.23 | Elias Spycher  | Einen Wald platzieren                           | 150 min       |
| 13.A | 27.10.23 | Luca J.W.      | Den Wald verschönern                            | 120 min       |
| 14.A | 27.10.23 | Elias Spycher  | Micao erstellen                                 | 180 min       |
| 14.B | 27.10.23 | Cedic Tuma     | Micao Hunt erstellen                            | 90 min        |
| 14.C | 27.10.23 | Luca J.W.      | Micaos verstecken                               | 30 min        |
| 15.A | 27.10.23 | Cedic Tuma     | Gnome Hunt erstellen                            | 90 min        |
| 15.B | 27.10.23 | Luca J.W.      | Gnomes verstecken                               | 30 min        |
| 16.A | 27.10.23 | Fabian Meyer    | Tutorial programmieren                           | 180 min       |
| 17.A | 03.11.23 | Luca J.W.      | Gebäude für den Tycoon erstellen                | 180 min       |
| 18.A | 03.11.23 | Cedric Tuma     | Achievements erstellen                          | 180 min       |
| 19.A | 03.11.23 | Fabian Meyer    | Gamepass erstellen                              | 180 min       |
| 20.A | 03.11.23 | Elias Spycher   | Easter Eggs hinzufügen                          | 180 min       |


Total: 2680 min


## 3 Entscheiden

Wir haben uns entschieden auf die Implementation der Ameisenbären zu verzichten und stattdessen ein kleines Minigame zu implementieren, dies besteht aus einem Suchspiel, bei dem man 10 Objekte finden muss. 
Die neuen Anforderungen und Testfälle sind hier neu aufgeführt

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |15.09.23 | Luca J.W. |   45 min            |        45 min           |
| 2.A  |15.09.23| Luca J.W. |    30 min           |        30 min           |
| 3.A  |15.09.23| Cedic Tuma |    30 min           |       30 min            |
| 4.A  |15.09.23| Luca J.W. |     45 min          |         45 min          |
| 5.A  |15.09.23| Alle  |    30 min           |             30 min      |
| 6.A  |22.09.23| Luca J.W. |   30 min            |        30 min           |
| 7.A  |22.09.23| Fabian Meyer|    100 min           |     100 mi              |
| 8.A  |22.09.23|Cedic Tuma/ Fabian Meyer|   180 min            |    360 min               |
| 9.A  |27.10.23|Fabian Meyer/ Elias Spycher|     240 min          |     480 min              |
| 10.A  |27.10.23|Luca J.W. |   60 min            |         60 min          |
| 10.B  |27.10.23|Luca J.W. |   60 min            |         60 min          |
| 10.C  |27.10.23|Luca J.W. |    60 min           |        60 min           |
| 11.C  |28.10.23|Cedic Tuma |    180 min           |        180 min           |
| 12.A  |28.10.23|Elias Spycher|  150 min             |      150 min             |
| 13.A  |04.11.23|Luca J.W./ Elias Spycher|   120 min      |       120 min            |
| 14.A  |04.11.23|Elias Spycher |  180 min       |      180 min             |
| 14.B  |04.11.23|Elias Spycher |    90 min    |       90 min            |
| 14.c  |03.11.2023|Luca J.W. |      30 min         |    30 min               |
| 15.A  |03.11.2023|Cedic Tuma |    90 min   |     90 min              |
| 15.B  |03.11.2023|Luca J.W. |     30 min     |      30 min             |

## 5 Testprotokoll

| TC-№ | Datum | Tester | Resultat | Bemerkung | Unterschrift |
| ---- | ----- | -------- | -------| --------- | ------------ |
| 1.1  |            0.3.12.2023      |   Elias Spycher   |   OK       |          -         |     ALA     |        
| 2.1  |            0.3.12.2023      |   Elias Spycher   |   NOK      |         Spiel selbsterklärend          |     ALA    |           
| 3.1  |            0.3.12.2023      |   Elias Spycher   |   OK        |         -          |     ALA     |           
| 4.1  |            0.3.12.2023      |   Elias Spycher   |   OK         |                   |     ALA     |           
| 5.1  |            0.3.12.2023      |   Elias Spycher   |   NOK         |      es wird nicht angezeigt            |     ALA     |          
| 6.1  |            0.3.12.2023      |   Elias Spycher   |   NOK         |      Keine Ameisenbären implementiert, Micao Game erstellt             |     ALA     |         
| 7.1  |            0.3.12.2023      |   Elias Spycher   |   OK         |       -            |     ALA     |          
| 8.1  |            0.3.12.2023      |   Elias Spycher   |   NOK         |      Upgrade wird nicht gemacht             |     ALA     |        
| 9.1  |           0.3.12.2023       |   Elias Spycher   |   OK        |        -           |     ALA     |          
| 10.1  |           0.3.12.2023      |   Elias Spycher   |   NOK         |        Achievements nicht implementiert           |     ALA     |        
| 11.1  |           0.3.12.2023      |   Elias Spycher   |   OK        |          -         |     ALA     |        
| 11.1  |           0.3.12.2023      |   Elias Spycher   |   OK        |          -         |     ALA     |   

## 6 Testbericht

Viele Teile des geplanten konnten nicht umgsetzt werden. 
Testfälle 2, 5, 6, 8 und 10 funktionieren allesamt nicht.
Der Tycoon ist somit nicht wirklich spielbar und braucht noch viel Überarbeitung und Fehlerbehebungen.
