# LA_1300
# Projekt-Dokumentation

Angel Angelov 

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
| 18.08.2023 | 0.1  | Im ersten Lernatelier morgen musste ich meine C# Kenntnisse auffrischen, da ich die Sprache schon lange nicht mehr benutzt habe. |
| 25.08.2023 | 0.2  | Die ersten zwei Stunden habe ich an einem C#-Kurs gearbeitet und dann habe ich mit dem Zufallszahlenspiel begonnen.              |
| 01.09.2023 | 0.3  | Heute habe ich mein Zufallszahlenspiel fertiggestellt.                                                                          |
| 08.09.2023 | 1.0  | Ich habe noch einige Änderungen an meinem Spiel vorgenommen und dann habe ich mit der Dokumentation begonnen.
## 1 Informieren

### 1.1 Ihr Projekt

In diesem Projekt möchte ich ein Spiel erstellen, bei dem ich eine zufällige Zahl erraten muss.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |  Muss           |   Funktional   |Als User möchte ich, dass das Programm eine Zufallszahl zwischen 1 und 100 generieren kann und diese speichert.|
| 2    |  Muss           |   Funktional   |Als User möchte ich die Möglichkeit haben, Zahlen einzugeben. |
| 3    |  Muss           |   Funktional   |Als User möchte ich, dass das Programm mir mitteilt, ob die von mir eingegebene Zahl kleiner oder größer ist als die gewünschte Zahl.|
| 4    |  Muss           |   Funktional   |Als User möchte ich, dass der Computer mir mitteilt, wenn ich die Zahl richtig geraten habe.|
| 5    |  Muss           |   Funktional   |Als User möchte ich, dass mir die Anzahl der Versuche angezeigt wird, wenn ich die Zahl erraten habe.|
| 6    |  Muss           |   Funktional   |Als User möchte ich, dass das Programm auch mit fehlerhaften Eingaben umgehen kann.|
| 7    |  Kann           |   Funktional   |Als User möchte ich die Möglichkeit haben, das Spiel mehrmals zu spielen, ohne das Programm erneut starten zu müssen.|


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Programm gestartet |    -     | Ein Zufallszahl wird generiert und gespeichert|
| 1.2  | Please guess the Random Nummber |   Zahlen    | The Nummber is bigger/smaller|
| 1.3  | Give another Nummber | Zahelen |  The Nummber is bigger/smaller  |
| 1.7  | Give another Nummber| Buchstaben | You can't only enter numbers|
| 1.4  | Give another Nummber | Zahelen     |  You got the number right    |
| 1.5  | You needed 8 gueses | -Enter- | Woud you like to play again?|
| 1.6  |  Woud you like to play again? | No | Programm beendet|

### 1.4 Diagramme

![image](https://github.com/doomdude32a/LA1300/assets/112430127/d975b1e8-5c1c-4951-bd4e-857a9ee98e21)


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 18.08.2023 |   Angel Angelov    | C#-Kenntnisse auffrischen | 180 min |
| 2.A  | 25.08.2023 |   Angel Angelov   |  Ein Zahl zwischen 1-100 generieren und speichern    |   30 min   |
| 3.A  | 25.08.2023 |   Angel Angelov  | Die eingegebene Zahl mit der zufällig generierten Zahl vergleichen und ausgeben, ob die Zahl größer, kleiner oder eraten wurde |  60min  |
| 4.A  | 25.08.2023 |   Angel Angelov  | Das Programm so einrichten, dass es mit fehlerhaften Eingaben umgehen kann.           |      30min         |
| 5.A  | 01.09.2023 |   Angel Angelov  |  Programm mehrmals wiederholen zu können  | 30 min              |
| 6.A |  01.09.2023 |   Angel Angelov  |  Das Programm verschönern und verbessern            |      60min             |


## 3 Entscheiden

Ich habe mich entschieden ein MainMenu zu implemintieren.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 18.08.2023      |   Angel Angelov        |      180min         |    300min               |
| 2.A  | 25.08.2023      |   Angel Angelov          |     30 min          |      15min             |
| 3.A  | 25.08.2023      |   Angel Angelov          |      60min        |        60min           |
| 4.A  | 25.08.2023      |   Angel Angelov          |    30min            |       40min             |
| 5.A  | 01.09.2023      |   Angel Angelov          |    30 min            |     40 min               |
| 6.A  | 01.09.2023      |   Angel Angelov          |       60min        |    120min               |

## 5 Kontrollieren

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 10.09.2023      |   erfüllt       |  Angel Angelov      |
| 1.2  |  10.09.2023     |   erfüllt       |   Angel Angelov     |
| 1.3  |  10.09.2023     |   erfüllt       |   Angel Angelov     |
| 1.4  | 10.09.2023      |   erfüllt       |   Angel Angelov     |
| 1.5  |  10.09.2023     |    erfüllt      |   Angel Angelov     |
| 1.6  |  10.09.2023     |    erfüllt      |   Angel Angelov     |

## 6 Auswerten

-> Mahara 
