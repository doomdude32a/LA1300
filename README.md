# LA_1300
# Projekt-Dokumentation

☝️ Alle Text-Stellen, welche mit einem ✍️ beginnen, können Sie löschen, sobald Sie die entsprechende Stellen ausgefüllt haben.

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


✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

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



✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

![image](https://github.com/doomdude32a/LA1300/assets/112430127/d975b1e8-5c1c-4951-bd4e-857a9ee98e21)


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 18.08.2023 |   Angel Angelov    | C#-Kenntnisse auffrischen | 180 min |
| 2.A  | 25.08.2023 |   Angel Angelov   |  Ein Zahl zwischen 1-100 generieren und speichern    |   30 min   |
| 3.A  | 25.08.2023 |   Angel Angelov  | Die eingegebene Zahl mit der zufällig generierten Zahl vergleichen und ausgeben, ob die Zahl größer, kleiner oder eraten wurde |  60min  |
| 4.A  | 25.08.2023 |   Angel Angelov  | Das Programm so einrichten, dass es mit fehlerhaften Eingaben umgehen kann.           |      30min         |
| 5.A  | 25.08.2023 |   Angel Angelov  |  Programm mehrmals wiederholen zu können  | 30 min              |


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
