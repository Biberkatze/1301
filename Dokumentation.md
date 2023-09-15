# Projekt-Dokumentation

Alai, Cedric Tuma, Luca Jeanneret, Fabian Meyer und Elias Spycher

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|   15.09.2023    | 0.0.1   |    Wir haben das Projekt geplant    |
|   22.09.2023    | ...     |                                                              |
|   29.09.2023    | 1.0.0   |                                                              |
|   27.10.2023    | 1.0.0   |                                                              |
|   03.11.2023    | 1.0.0   |                                                              |

## 1 Informieren

Wir haben uns überlegt, was mir machen wollen un sind in der Aufgabenstellung auf den Verweiss auf Roblux gekommen. Für dies haben wir uns auch entschieden. Für das genauere Game haben wir uns einen Ameisenbär [Tycoon](https://de.wikipedia.org/wiki/Tycoon) vorgestellt, dies wäre gut umsetzbar und wäre auch auf einem guten Schwierigkeitsgrad. Für das müssen wir uns in die Umgebung von Roblox Studio einarbeiten und Ameisenbär Modelle mit [Blender](https://www.blender.org/) erstellen

### 1.1 Ihr Projekt

Ein Ameisenbär Tycoongame, in dem man immer mächtiger wird und das grösste Ameisenbärmonopol aufbauen kann.

In diesem Projekt lernen wir mehrere neue Technologien kennen, darunter Blender, eine professionelle grafikdesign Plattform, Roblox Studios und mehr. In dem Tycoon soll man verschiedene Ameisenbären kaufen und verwalten. Es sollte Möglichkeiten geben diesen Futter zu geben und neue Technologien freischalten zu können um mehr Geld zu verdienen um noch mehr Tiere zu kaufen. Es sollte Käufe mit Echtgeld geben um In-App-Käufe zu tätigen und somit auch ein wenig Geld zu verdienen.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ | Beschreibung |
| ---- | --------------- | --- | -------------- |
| 1    | muss | Funktional | Als Nutzer möchte ich, dass ich das Game starten kann, um es zu spielen. |
| 2    | muss | Funktional | Als Nutzer möchte ich, dass man ein kleines Tutorial bekommt, was man machen muss und was das Ziel ist, um zu wissen, wie man spielt. |
| 3    | muss | Funktional | Als Nutzer will ich, dass es eine Währung gibt, damit ich Sachen kaufen kann. |
| 4    | muss | Qualität | Als Nutzer will ich, dass die Ameisenbären gut modelliert wurden und cool aussehen, damit das Spiel gut aussieht. |
| 5    | muss | Funktional | Als Nutzer will ich, dass ich am Anfang einen ersten Ressourcengenerator habe, um erstes Einkommen zu generieren und direkt beginnen zu können. |
| 6    | muss | Funktional | Als Nutzer möchte ich, dass viele verschiedene Upgrades zur Verfügung stehen, damit ich eine Progression im Spiel habe. |
| 7    | muss | Qualität | Als Nutzer möchte ich, dass das Spiel mehrere Stufen im Tycoon-Modus hat, damit der Spielspaß länger anhält. |
| 8    | muss | Funktional | Als Nutzer möchte ich, dass es mehrere Standorte für mein Tycoon gibt, damit ich mein Geschäft an verschiedenen Orten aufbauen kann. |
| 9    | muss | Funktional | Als Nutzer möchte ich, dass das Spiel einen Mehrspielermodus hat, damit ich mit meinen Freunden spielen kann. |
| 10   | kann | Qualität | Als Nutzer möchte ich, dass es Achievements gibt, um zusätzlichen Spaß und Herausforderungen im Spiel zu haben. |
| 11   | muss | Qualität | Als Nutzer möchte ich, dass das Spiel erkundbare Karten enthält, damit ich die Welt des Ameisenbär-Tycoons entdecken kann. |
| 12   | kann | Randbedingung | Als Nutzer möchte ich, dass es Geheimnisse (Eastereggs) auf der Karte gibt, die ich entdecken kann, um die Erforschung spannender zu gestalten. |
| 13   | kann | Randbedingung | Als Nutzer möchte ich die Möglichkeit haben, Gamepasses mit Robux zu kaufen, um meine Spielfortschritte zu beschleunigen. ||
| 14   | muss | Qualität | Als Nutzer möchte ich regelmäßige Updates im Spiel sehen, um die Spielerfahrung kontinuierlich zu verbessern. |
| 15   | kann | Qualität | Als Nutzer möchte ich, dass das Spiel eine ansprechende Hintergrundmusik und Soundeffekte bietet, um die Atmosphäre zu verbessern. |
| 16   | muss | Funktional | Als Nutzer möchte ich, dass es regelmäßige Sicherungsoptionen gibt, um meinen Spielfortschritt nicht zu verlieren. |
| 17   | kann | Qualität | Als Nutzer möchte ich, dass ich einen Gamepass kaufen kann, damit ich den Namen der Ameisenbären verändern kann. |



✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |        Roblox offen      |    Game starten     |        Game bereit zum spielen           |
| 2.1  |        Game zum ersten mal geöffnet      |    Keine     |        Kleines tuturial           |
| 3.1  |        Game geöffnet      |    Keine     |         Es gibt eine währung          |
| 4.1  |        Game geöffnet      |    Spiel gestartet     |      Die Ameisenbären sollen gut aussehen             |
| 5.1  |        Game geöffnet      |    Spiel gestartet     |      Man bekommt einen Ressourcengenerator             |


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

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
