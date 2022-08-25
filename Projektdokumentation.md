# Projekt-Dokumentation


Haldimann Joel

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|       | 0.0.1   | ✍️ Jedes Mal, wenn Sie an dem Projekt arbeiten, fügen Sie hier eine neue Zeile ein und beschreiben in *einem* Satz, was Sie erreicht haben. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt

Ich programmiere ein Zahlenratespiel.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    | Funktional | muss | Als ein Computer möchte ich eine zufällige Zahl zwischen 1 und 100 generieren, damit der Speieler diese erraten kann |
| 2    | Funktional | muss | Als ein Spieler möchte ich eine Zahl raten können, damit ich die gesuchte zahl finden kann. |
| 3.a  | Qualität | kann | Als Speieler möchte ich wissen ob meine Zahl kleiner als die gesuchte Zahl ist, um sie einfacher zu finden. |
| 3.b  | Qualität | kann | Als Speieler möchte ich wissen ob meine Zahl grösser als die gesuchte Zahl ist, um sie einfacher zu finden. |
| 3.c  | Funktional| muss | Als Spieler möchte ich wissen ob ich die Zahl erraten habe, damit ich weiss ob das Spiel vorbei ist. |
| 4    | Qualität | kann | Als Spieler möchte ich wissen wie viele Versuche ich hatte, damit ich weiss wie gut ich war.|
| 5    | Funktionl | muss | Als Computer möchte ich mit Fehleingaben ungehen können, damit das Spiel weitergehen kann. |
| 6    | Qualität  | kann | Als Spielr möchte ich einen schönen Hintergrund haben. |

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1. |Ich habe den Code für die Zahlengeneation geschreiebn| Console.Write(Z)| Eine zufällig generierte Zahl.|
| 2. | Ich habe den Code für das Erraten der Zahlen| Eine Zahl in das Feld eingeben. | Man kann die Zahl in das Feld schreiben. |
| 3.a| Ich habe den Code für das Erkennen ob die geratene Zahl kleiner als die gesuchte Zahl ist. | Ich gebe eine Zahl unter 0 ein| Das Programm sagt mir das meine  Zahl zu tief war. |
| 3.b| Ich habe den Code für das Erkennen ob die geratene Zahl grösser als die gesuchte Zahl ist. | Ich gebe eine Zahl die grösser als 100 ist ein| Das Programm sagt mir, dass meine Zahl zu gross ist. |
| 3.c|Ich habe den Code um herauszufinden ob meine Zahl die gesuchte Zahl ist.| Ich gebe eine Zahl ein. | Die Antowrt wird als Richtig angezeigt oder die Zahl wird gelöscht. |
| 4. | Ich habe den Code um zu wissen wie viel Versuch ich hatte. | Ich gebe eine Antwort. | Der Coutner erhöt sich um 1.|
| 5. | Ich habe den Code damit der Computer mit fehleingaben umgehen kann| Ich gebe ein Wort ein. | Die Eingabe wird gelöscht und nicht als Versuch gespeichert. |
| 6. | Ich habe den Code für einen blauen Hintergrund. | Ich schaue das Spiel an. | Der Hintergrund ist blau. |



### 1.4 Diagramme

<img width="437" alt="Pap" src="https://user-images.githubusercontent.com/111045600/186599808-eaae3af1-f4f7-4ebe-a90a-7b48aac18cbf.png">

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.   | 2.09.22 | Joel | Zahlen generieren können | 1 Lektionen|
| 2.   | 9.09.22 | Joel | Zahlen raten können| 3 Lektionen|
| 3.a  | 9.09.22 | Joel | Wissen ob Zahl zu klein ist | 1 Lektionen |
| 3.b  | 16.09.22 | Joel | Wissen ob Zahl zu gross ist| 1 Lektionen |
| 3.c  | 16.09.22 | Joel | Wissen ob Zahl richtig ist | 1 Lektion |
| 4.   | 16.09.22 | Joel | Wissen wie viele Versuche man hatte | 2 Lektionen |
| 5.   | 23.09.22 | Joel | Mit Fehlanzeigen umgehen können | 3 Lektionen |
| 6.   | 30.09.22 | Joel | Hintergrund blau machen| 1 Lektion

Total: 13 Lektionen

## 3 Entscheiden

Ich habe mich dazu entschieden den Hintergrund blau zu machen, weil blau eine schöne Farbe ist.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.