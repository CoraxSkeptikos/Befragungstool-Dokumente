[Inhaltsverzeichnis](https://github.com/FI17/Befragungstool-Dokumente/blob/master/README.md)
# Testszenarien - Beantwortung
## visuelle Tests
* Ist das Aussehen der Seiten in den folgenden Browsern gleich? Gibt es irgendwelche grafischen Fehler?

| Seite/Browser | Google Chrome | Mozilla Firefox | Microsoft Internet Explorer | Microsoft Edge |
| --- | :---: | :---: |  :---: | :---: |
| Beantwortungsseite - Weiter | :white_check_mark: | Progressbar sieht in jedem Browser anders aus, führt aber nicht zu unerwünschtem Verhalten. |:white_check_mark:|:white_check_mark:|
| Beantwortungsseite - Fertigstellen | :white_check_mark: | :white_check_mark:|:white_check_mark:|:white_check_mark:|

## funktionale Tests
* Ist die Funktionsweise der folgenden Elemente wie gewünscht?

### Beantwortung - Weiter
![Bild der Beantwortungsseite mit dem Button "Weiter"](https://github.com/FI17/Befragungstool-Dokumente/blob/master/Tests/Content/Beantwortung/1-Beantwortung-Weiter.png)

| Nr. | Elementtyp | gewollte Funktion | funktionsfähig? |
| :---: | :---: | :--- | :---: |
| 1 | Textfeld | Eingabefeld für die Antwort zur Frage - Texteingabe | :white_check_mark: |
| 2 | Button | Antwort abspeichern und nächste Frage aufrufen | :white_check_mark: |

### Beantwortung - Fertigstellen
![Bild der Beantwortungsseite mit dem Button "Fertigstellen"](https://github.com/FI17/Befragungstool-Dokumente/blob/master/Tests/Content/Beantwortung/2-Beantwortung-Fertigstellen.png)

| Nr. | Elementtyp | gewollte Funktion | funktionsfähig? |
| :---: | :---: | :--- | :---: |
| 3 | Textfeld | Eingabefeld für die Antwort zur Frage - Texteingabe | :white_check_mark: |
| 4 | Button | Antwort in der Datenbank abspeichern und Weiterleitung auf Dankesseite | :white_check_mark: |

---

# Testfälle - Beantwortung
## Element 1

| Testszenario | Eingabefeld für die Antwort zur Frage - Texteingabe | funktionsfähig? | Anmerkungen |
| :---: | :--- | :---: | :--- |
| Testfall 1 | keine Eingabe von Zeichen | :white_check_mark: | möglich, Abfangen gegenwärtig noch nicht gewollt |
| Testfall 2 | Eingabe von Antworttext ohne Umlaute | :white_check_mark: |
| Testfall 3 | Eingabe von Antworttext mit Umlauten | :white_check_mark: |
| Testfall 4 | Eingabe von Antworttext mit Sonderzeichen | :red_circle: | einziges Problem bei der Eingabe von < gefolgt von Buchstaben |
| Testfall 5 | Eingabe von Antworttext mit Hiragana | :white_check_mark: |
| Testfall 6 | Eingabe von Antworttext mit Han-Schrift | :white_check_mark: |
| Testfall 7 | Eingabe von Antworttext mit arabischer Schrift | :white_check_mark: |
| Testfall 8 | Eingabe von Antworttext mit einer Länge von 10.000 Zeichen (lat. Buchstaben) | :white_check_mark: | möglich, Abfangen gegenwärtig noch nicht gewollt |
| Testfall 9 (1-8)| Website läuft auf PC | :white_check_mark: |
| Testfall 10 (1-8)| Website läuft auf Server | :white_check_mark: |

## Element 2

| Testszenario | Antwort abspeichern und nächste Frage aufrufen | funktionsfähig? | Anmerkungen |
| :---: | :--- | :---: | :--- |
| Testfall 1 | keine Eingabe von Zeichen im Textfeld | :white_check_mark: | möglich, Abfangen gegenwärtig noch nicht gewollt |
| Testfall 2 | Antworttext ohne Umlaute | :white_check_mark: |
| Testfall 3 | Antworttext mit Umlauten im Textfeld | :white_check_mark: |
| Testfall 4 | Antworttext mit Sonderzeichen | :red_circle: | einziges Problem bei der Eingabe von < gefolgt von Buchstaben |
| Testfall 5 | Antworttext mit Hiragana im Textfeld | :white_check_mark: |
| Testfall 6 | Antworttext mit Han-Schrift im Textfeld | :white_check_mark: |
| Testfall 7 | Antworttext mit arabischer Schrift im Textfeld | :white_check_mark: |
| Testfall 8 | Antworttext mit einer Länge von 10.000 Zeichen oder mehr (lat. Buchstaben) im Textfeld | :white_check_mark: | möglich, Abfangen gegenwärtig noch nicht gewollt |
| Testfall 9 (1-8)| Website läuft auf PC | :white_check_mark: |
| Testfall 10 (1-8)| Website läuft auf Server | :white_check_mark: |

---

## Element 3

| Testszenario | Eingabefeld für die Antwort zur Frage - Texteingabe | funktionsfähig? | Anmerkungen |
| :---: | :--- | :---: | :--- |
| Testfall 1 | keine Eingabe von Zeichen | :white_check_mark: | möglich, Abfangen gegenwärtig noch nicht gewollt |
| Testfall 2 | Eingabe von Antworttext ohne Umlaute | :white_check_mark: |
| Testfall 3 | Eingabe von Antworttext mit Umlauten | :white_check_mark: |
| Testfall 4 | Eingabe von Antworttext mit Sonderzeichen | :red_circle: | einziges Problem bei der Eingabe von < gefolgt von Buchstaben |
| Testfall 5 | Eingabe von Antworttext mit Hiragana | :white_check_mark: |
| Testfall 6 | Eingabe von Antworttext mit Han-Schrift | :white_check_mark: |
| Testfall 7 | Eingabe von Antworttext mit arabischer Schrift | :white_check_mark: |
| Testfall 8 | Eingabe von Antworttext mit einer Länge von 10.000 Zeichen (lat. Buchstaben) | :white_check_mark: | möglich, Abfangen gegenwärtig noch nicht gewollt |
| Testfall 9 (1-8)| Website läuft auf PC | :white_check_mark: |
| Testfall 10 (1-8)| Website läuft auf Server | :white_check_mark: |

## Element 4

| Testszenario | Antwort abspeichern und nächste Frage aufrufen | funktionsfähig? | Anmerkungen |
| :---: | :--- | :---: | :--- |
| Testfall 1 | keine Eingabe von Zeichen im Textfeld | :white_check_mark: | möglich, Abfangen gegenwärtig noch nicht gewollt |
| Testfall 2 | Antworttext ohne Umlaute | :white_check_mark: |
| Testfall 3 | Antworttext mit Umlauten im Textfeld | :white_check_mark: |
| Testfall 4 | Antworttext mit Sonderzeichen | :red_circle: | einziges Problem bei der Eingabe von < gefolgt von Buchstaben |
| Testfall 5 | Antworttext mit Hiragana im Textfeld | :white_check_mark: |
| Testfall 6 | Antworttext mit Han-Schrift im Textfeld | :white_check_mark: |
| Testfall 7 | Antworttext mit arabischer Schrift im Textfeld | :white_check_mark: |
| Testfall 8 | Antworttext mit einer Länge von 10.000 Zeichen oder mehr (lat. Buchstaben) im Textfeld | :white_check_mark: | möglich, Abfangen gegenwärtig noch nicht gewollt |
| Testfall 9 (1-8)| Website läuft auf PC | :white_check_mark: |
| Testfall 10 (1-8)| Website läuft auf Server | :white_check_mark: |
