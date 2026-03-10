# Fragebogen: Huffman-Codierung (huffman.py)

Nach dem Ausführen des Skripts und **Einfügen der Konsolenausgabe** (Merge-Symbol in der Task-Card):

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

---
 Char | Huffman code
----------------------
 'd'  |        0111
 'a'  |        0100
 'b'  |       01011
 'c'  |       01010
 'e'  |        0001
 'f'  |        0000
 'g'  |        0011
 'h'  |        0010
 'i'  |       10101
 'j'  |       10100
 'k'  |       10111
 'l'  |       10110
 'm'  |       10001
 'n'  |       10000
 'o'  |       10011
 'p'  |       10010
 'q'  |       11101
 'r'  |       11100
 's'  |       11111
 't'  |       11110
 'u'  |       11001
 'v'  |       11000
 'w'  |       11011
 'x'  |       11010
 'y'  |       01101
 'z'  |       01100

**2. Deine Kommentierung**

- Was zeigen die ausgegebenen Huffman-Codes?  
  *[kurz beschreiben]*
Jedem Zeichen wird ein Codewort aus 0 und 1 zugeordnet.
Die Codes haben unterschiedliche Längen (z. B. 4 oder 5 Bit).
Der Code ist präfixfrei:
Kein Code ist der Anfang eines anderen Codes.
Dadurch kann der Bitstrom eindeutig wieder dekodiert werden.
Bedeutung der Tabelle:
Sie beschreibt die optimale Binärcodierung der Zeichen für genau diesen Text.
Diese Codierung minimiert die durchschnittliche Anzahl an Bits pro Zeichen.

- Warum haben häufigere Zeichen kürzere Codewörter?  
  *[kurz begründen]*
Wenn ein Zeichen häufig vorkommt:
wird es sehr oft im Bitstrom auftreten
deshalb lohnt es sich, ihm ein kurzes Codewort zu geben
Seltene Zeichen bekommen dagegen längere Codes, weil sie nur selten vorkommen und den Durchschnitt kaum erhöhen.