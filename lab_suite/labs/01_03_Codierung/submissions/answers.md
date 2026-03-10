# Fragebogen: Huffman-Codierung (huffman.py)

Nach dem Ausführen des Skripts und **Einfügen der Konsolenausgabe** (Merge-Symbol in der Task-Card):

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

---

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

---

## Konsolenausgabe

```
Enter the string to compute Huffman Code Tree: ---------------------------------------------------------
Dictionary of Characters with char frequency:       {'a': 7, 'n': 2, 'h': 1, 'd': 2, 's': 1, 'f': 2, 'k': 3, 'j': 3}
Dictionary converted into a list:                   dict_items([('a', 7), ('n', 2), ('h', 1), ('d', 2), ('s', 1), ('f', 2), ('k', 3), ('j', 3)])
List of characters sorted to descending frequency:  [('a', 7), ('k', 3), ('j', 3), ('n', 2), ('d', 2), ('f', 2), ('h', 1), ('s', 1)]
Huffman Code Dictionary:                            {'d': '000', 'n': '001', 's': '0100', 'h': '0101', 'f': '011', 'j': '100', 'k': '101', 'a': '11'}

 Char | Huffman code 
----------------------
 'a'  |          11
 'k'  |         101
 'j'  |         100
 'n'  |         001
 'd'  |         000
 'f'  |         011
 'h'  |        0101
 's'  |        0100
```
