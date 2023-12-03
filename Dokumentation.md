# Projekt-Dokumentation

Cedric Tuma, Luca Jeanneret, Fabian Meyer und Elias Spycher

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|   15.09.2023    | 0.0.1   |    Wir haben das Projekt geplant    |
|   22.09.2023    | 0.0.2   |    Wir haben realisiert                                                          |
|   29.09.2023    | 0.1.1   |    Wir haben realisiert                                                           |
|   27.10.2023    | 0.1.2   |    Wir haben realisiert                                                           |
|   03.11.2023    | 1.0.0   |    Wir haben realisiert                                                          |

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
| 11.12|        Game geöffnet      |    -    |      AEastereggs auf der Map versteckt             |


✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

![Screenshot besserLA1301 2023-09-15 093958](https://github.com/Biberkatze/1301/assets/110892742/c88d2d72-9406-4ad3-b4da-676031a69759)



## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       |           |              |               |
| ...  |       |           |              |               |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

Wir haben uns entschieden auf die Implementation der Ameisenbären zu verzichten und stattdessen ein kleines Minigame zu implementieren, dies besteht aus einem Suchspiel, bei dem man 10 Objekte finden muss. 
Die neuen Anforderungen und Testfälle sind hier neu aufgeführt

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Testprotokoll

| TC-№ | Testfall Nr.  | Datum | Resultat | Tester | Bemerkung | Unterschrift |
| 1.2  |          |   0.3.12.2023    |          |        |           |              |
| ---- | -----         |   0.3.12.2023    |          |        |           |              |
| ---- | -----         |   0.3.12.2023    |          |        |           |              |
| ---- | -----         |   0.3.12.2023    |          |        |           |              |
| ---- | -----         |   0.3.12.2023    |          |        |           |              |
| ---- | -----         |   0.3.12.2023    |          |        |           |              |
| ---- | -----         |   0.3.12.2023    |          |        |           |              |
| ---- | -----         |   0.3.12.2023    |          |        |           |              |
| ---- | -----         |   0.3.12.2023    |          |        |           |              |
| ---- | -----         |   0.3.12.2023    |          |        |           |              |
| ---- | -----         |   0.3.12.2023    |          |        |           |              |
| ---- | -----         |   0.3.12.2023    |          |        |           |              |



## 6 Auswerten


