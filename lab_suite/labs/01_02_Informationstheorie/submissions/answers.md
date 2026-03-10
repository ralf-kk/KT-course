# Fragebogen: Entropie-Analyse (entropy1.py)

Nach dem Ausführen von `entropy1.py` mit eigenem Text in `sampletext.txt`:

**Konsolenausgabe einfügen:** Nutze das Merge-Symbol in der Task-Card, um die Ausgabe aus `console_log.txt` hier einzufügen. Anschließend die Ausgabe **kommentieren**.

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

---

**2. Deine Kommentierung:**

- Was fällt dir bei der Entropie deines Textes auf?  
  *[z. B. Vergleich mit anderen Texten, Zeichenverteilung, Redundanz]*

Hohe Entropie
→ viele verschiedene Zeichen, relativ gleichmäßig verteilt
→ der nächste Buchstabe ist schwer vorherzusagen

Niedrige Entropie
→ wenige Zeichen oder stark ungleiche Verteilung
→ der nächste Buchstabe ist leichter vorherzusagen

---

## Konsolenausgabe

```
Analyze the file:  c:\Users\ralfk\GIT_KT\lab_suite\labs\01_02_Informationstheorie\sidedata/sampletext.txt

-----File Contents:---------------------------------------------------
#das ist mein modifizierter Text --lol --. hahahah rofl lmao

#ich mag das so sehr, dass ich es in einem Textfile speichern muss. Es ist so lustig, dass ich es mit der ganzen Welt teilen mÃ¶chte. Vielleicht wird es ja viral und jeder wird darÃ¼ber lachen. Wer weiÃŸ, vielleicht wird es sogar ein Meme!

#Ich hoffe, dass du genauso viel SpaÃŸ beim Lesen dieses Textes hast wie ich beim Schreiben hatte. Es ist einfach zu lustig, um es fÃ¼r mich zu behalten. Also teile es mit deinen Freunden und lass uns gemeinsam lachen!

#Und denk daran, immer SpaÃŸ zu haben und das Leben nicht zu ernst zu nehmen. Manchmal ist es wichtig, einfach nur zu lachen und das Leben zu genieÃŸen. Also lass uns gemeinsam lachen und das Leben feiern!

#In diesem Sinne, viel SpaÃŸ beim Lesen und Teilen dieses Textes! Lachen ist die beste Medizin, also lass uns gemeinsam lachen und das Leben genieÃŸen!
Number of characters: 877
Character Dictionary: {'#': 5, 'd': 34, 'a': 46, 's': 63, ' ': 150, 'i': 62, 't': 28, 'm': 26, 'e': 112, 'n': 62, 'o': 12, 'f': 9, 'z': 10, 'r': 23, 'T': 5, 'x': 4, '-': 4, 'l': 31, '.': 8, 'h': 33, '\n': 4, 'c': 22, 'g': 12, ',': 9, 'p': 4, 'u': 25, 'E': 2, 'W': 2, 'Ã': 9, '¶': 1, 'V': 1, 'w': 6, 'j': 2, 'v': 4, '¼': 2, 'b': 12, 'Ÿ': 6, 'M': 3, '!': 5, 'I': 2, 'S': 5, 'L': 7, 'A': 2, 'F': 1, 'U': 1, 'k': 1}

-------Table of characters:----------------
       | cnt=150    p=0.171   H=2.548 bit/char  H_av=0.436 bit/char
 e     | cnt=112    p=0.128   H=2.969 bit/char  H_av=0.379 bit/char
 s     | cnt= 63    p=0.072   H=3.799 bit/char  H_av=0.273 bit/char
 i     | cnt= 62    p=0.071   H=3.822 bit/char  H_av=0.270 bit/char
 n     | cnt= 62    p=0.071   H=3.822 bit/char  H_av=0.270 bit/char
 a     | cnt= 46    p=0.052   H=4.253 bit/char  H_av=0.223 bit/char
 d     | cnt= 34    p=0.039   H=4.689 bit/char  H_av=0.182 bit/char
 h     | cnt= 33    p=0.038   H=4.732 bit/char  H_av=0.178 bit/char
 l     | cnt= 31    p=0.035   H=4.822 bit/char  H_av=0.170 bit/char
 t     | cnt= 28    p=0.032   H=4.969 bit/char  H_av=0.159 bit/char
 m     | cnt= 26    p=0.030   H=5.076 bit/char  H_av=0.150 bit/char
 u     | cnt= 25    p=0.029   H=5.133 bit/char  H_av=0.146 bit/char
 r     | cnt= 23    p=0.026   H=5.253 bit/char  H_av=0.138 bit/char
 c     | cnt= 22    p=0.025   H=5.317 bit/char  H_av=0.133 bit/char
 o     | cnt= 12    p=0.014   H=6.191 bit/char  H_av=0.085 bit/char
 g     | cnt= 12    p=0.014   H=6.191 bit/char  H_av=0.085 bit/char
 b     | cnt= 12    p=0.014   H=6.191 bit/char  H_av=0.085 bit/char
 z     | cnt= 10    p=0.011   H=6.455 bit/char  H_av=0.074 bit/char
 f     | cnt=  9    p=0.010   H=6.607 bit/char  H_av=0.068 bit/char
 ,     | cnt=  9    p=0.010   H=6.607 bit/char  H_av=0.068 bit/char
 Ã     | cnt=  9    p=0.010   H=6.607 bit/char  H_av=0.068 bit/char
 .     | cnt=  8    p=0.009   H=6.776 bit/char  H_av=0.062 bit/char
 L     | cnt=  7    p=0.008   H=6.969 bit/char  H_av=0.056 bit/char
 w     | cnt=  6    p=0.007   H=7.191 bit/char  H_av=0.049 bit/char
 Ÿ     | cnt=  6    p=0.007   H=7.191 bit/char  H_av=0.049 bit/char
 #     | cnt=  5    p=0.006   H=7.455 bit/char  H_av=0.043 bit/char
 T     | cnt=  5    p=0.006   H=7.455 bit/char  H_av=0.043 bit/char
 !     | cnt=  5    p=0.006   H=7.455 bit/char  H_av=0.043 bit/char
 S     | cnt=  5    p=0.006   H=7.455 bit/char  H_av=0.043 bit/char
 x     | cnt=  4    p=0.005   H=7.776 bit/char  H_av=0.035 bit/char
 -     | cnt=  4    p=0.005   H=7.776 bit/char  H_av=0.035 bit/char
 b'\n' | cnt=  4    p=0.005   H=7.776 bit/char  H_av=0.035 bit/char
 p     | cnt=  4    p=0.005   H=7.776 bit/char  H_av=0.035 bit/char
 v     | cnt=  4    p=0.005   H=7.776 bit/char  H_av=0.035 bit/char
 M     | cnt=  3    p=0.003   H=8.191 bit/char  H_av=0.028 bit/char
 E     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 W     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 j     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 ¼     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 I     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 A     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 ¶     | cnt=  1    p=0.001   H=9.776 bit/char  H_av=0.011 bit/char
 V     | cnt=  1    p=0.001   H=9.776 bit/char  H_av=0.011 bit/char
 F     | cnt=  1    p=0.001   H=9.776 bit/char  H_av=0.011 bit/char
 U     | cnt=  1    p=0.001   H=9.776 bit/char  H_av=0.011 bit/char
 k     | cnt=  1    p=0.001   H=9.776 bit/char  H_av=0.011 bit/char
-------------------------------------------

Average Entropy H = 4.406 bit/char
Total Entropy of 877 characters H=3864.40 bit = 484.00 byte
```

---

## Konsolenausgabe

```
Analyze the file:  c:\Users\ralfk\GIT_KT\lab_suite\labs\01_02_Informationstheorie\sidedata/sampletext.txt

-----File Contents:---------------------------------------------------
#das ist mein modifizierter Text --lol --. hahahah rofl lmao

#ich mag das so sehr, dass ich es in einem Textfile speichern muss. Es ist so lustig, dass ich es mit der ganzen Welt teilen mÃ¶chte. Vielleicht wird es ja viral und jeder wird darÃ¼ber lachen. Wer weiÃŸ, vielleicht wird es sogar ein Meme!

#Ich hoffe, dass du genauso viel SpaÃŸ beim Lesen dieses Textes hast wie ich beim Schreiben hatte. Es ist einfach zu lustig, um es fÃ¼r mich zu behalten. Also teile es mit deinen Freunden und lass uns gemeinsam lachen!

#Und denk daran, immer SpaÃŸ zu haben und das Leben nicht zu ernst zu nehmen. Manchmal ist es wichtig, einfach nur zu lachen und das Leben zu genieÃŸen. Also lass uns gemeinsam lachen und das Leben feiern!

#In diesem Sinne, viel SpaÃŸ beim Lesen und Teilen dieses Textes! Lachen ist die beste Medizin, also lass uns gemeinsam lachen und das Leben genieÃŸen!
Number of characters: 877
Character Dictionary: {'#': 5, 'd': 34, 'a': 46, 's': 63, ' ': 150, 'i': 62, 't': 28, 'm': 26, 'e': 112, 'n': 62, 'o': 12, 'f': 9, 'z': 10, 'r': 23, 'T': 5, 'x': 4, '-': 4, 'l': 31, '.': 8, 'h': 33, '\n': 4, 'c': 22, 'g': 12, ',': 9, 'p': 4, 'u': 25, 'E': 2, 'W': 2, 'Ã': 9, '¶': 1, 'V': 1, 'w': 6, 'j': 2, 'v': 4, '¼': 2, 'b': 12, 'Ÿ': 6, 'M': 3, '!': 5, 'I': 2, 'S': 5, 'L': 7, 'A': 2, 'F': 1, 'U': 1, 'k': 1}

-------Table of characters:----------------
       | cnt=150    p=0.171   H=2.548 bit/char  H_av=0.436 bit/char
 e     | cnt=112    p=0.128   H=2.969 bit/char  H_av=0.379 bit/char
 s     | cnt= 63    p=0.072   H=3.799 bit/char  H_av=0.273 bit/char
 i     | cnt= 62    p=0.071   H=3.822 bit/char  H_av=0.270 bit/char
 n     | cnt= 62    p=0.071   H=3.822 bit/char  H_av=0.270 bit/char
 a     | cnt= 46    p=0.052   H=4.253 bit/char  H_av=0.223 bit/char
 d     | cnt= 34    p=0.039   H=4.689 bit/char  H_av=0.182 bit/char
 h     | cnt= 33    p=0.038   H=4.732 bit/char  H_av=0.178 bit/char
 l     | cnt= 31    p=0.035   H=4.822 bit/char  H_av=0.170 bit/char
 t     | cnt= 28    p=0.032   H=4.969 bit/char  H_av=0.159 bit/char
 m     | cnt= 26    p=0.030   H=5.076 bit/char  H_av=0.150 bit/char
 u     | cnt= 25    p=0.029   H=5.133 bit/char  H_av=0.146 bit/char
 r     | cnt= 23    p=0.026   H=5.253 bit/char  H_av=0.138 bit/char
 c     | cnt= 22    p=0.025   H=5.317 bit/char  H_av=0.133 bit/char
 o     | cnt= 12    p=0.014   H=6.191 bit/char  H_av=0.085 bit/char
 g     | cnt= 12    p=0.014   H=6.191 bit/char  H_av=0.085 bit/char
 b     | cnt= 12    p=0.014   H=6.191 bit/char  H_av=0.085 bit/char
 z     | cnt= 10    p=0.011   H=6.455 bit/char  H_av=0.074 bit/char
 f     | cnt=  9    p=0.010   H=6.607 bit/char  H_av=0.068 bit/char
 ,     | cnt=  9    p=0.010   H=6.607 bit/char  H_av=0.068 bit/char
 Ã     | cnt=  9    p=0.010   H=6.607 bit/char  H_av=0.068 bit/char
 .     | cnt=  8    p=0.009   H=6.776 bit/char  H_av=0.062 bit/char
 L     | cnt=  7    p=0.008   H=6.969 bit/char  H_av=0.056 bit/char
 w     | cnt=  6    p=0.007   H=7.191 bit/char  H_av=0.049 bit/char
 Ÿ     | cnt=  6    p=0.007   H=7.191 bit/char  H_av=0.049 bit/char
 #     | cnt=  5    p=0.006   H=7.455 bit/char  H_av=0.043 bit/char
 T     | cnt=  5    p=0.006   H=7.455 bit/char  H_av=0.043 bit/char
 !     | cnt=  5    p=0.006   H=7.455 bit/char  H_av=0.043 bit/char
 S     | cnt=  5    p=0.006   H=7.455 bit/char  H_av=0.043 bit/char
 x     | cnt=  4    p=0.005   H=7.776 bit/char  H_av=0.035 bit/char
 -     | cnt=  4    p=0.005   H=7.776 bit/char  H_av=0.035 bit/char
 b'\n' | cnt=  4    p=0.005   H=7.776 bit/char  H_av=0.035 bit/char
 p     | cnt=  4    p=0.005   H=7.776 bit/char  H_av=0.035 bit/char
 v     | cnt=  4    p=0.005   H=7.776 bit/char  H_av=0.035 bit/char
 M     | cnt=  3    p=0.003   H=8.191 bit/char  H_av=0.028 bit/char
 E     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 W     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 j     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 ¼     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 I     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 A     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 ¶     | cnt=  1    p=0.001   H=9.776 bit/char  H_av=0.011 bit/char
 V     | cnt=  1    p=0.001   H=9.776 bit/char  H_av=0.011 bit/char
 F     | cnt=  1    p=0.001   H=9.776 bit/char  H_av=0.011 bit/char
 U     | cnt=  1    p=0.001   H=9.776 bit/char  H_av=0.011 bit/char
 k     | cnt=  1    p=0.001   H=9.776 bit/char  H_av=0.011 bit/char
-------------------------------------------

Average Entropy H = 4.406 bit/char
Total Entropy of 877 characters H=3864.40 bit = 484.00 byte
```

---

## Konsolenausgabe

```
Analyze the file:  c:\Users\ralfk\GIT_KT\lab_suite\labs\01_02_Informationstheorie\sidedata/sampletext.txt

-----File Contents:---------------------------------------------------
#das ist mein modifizierter Text --lol --. hahahah rofl lmao

#ich mag das so sehr, dass ich es in einem Textfile speichern muss. Es ist so lustig, dass ich es mit der ganzen Welt teilen mÃ¶chte. Vielleicht wird es ja viral und jeder wird darÃ¼ber lachen. Wer weiÃŸ, vielleicht wird es sogar ein Meme!

#Ich hoffe, dass du genauso viel SpaÃŸ beim Lesen dieses Textes hast wie ich beim Schreiben hatte. Es ist einfach zu lustig, um es fÃ¼r mich zu behalten. Also teile es mit deinen Freunden und lass uns gemeinsam lachen!

#Und denk daran, immer SpaÃŸ zu haben und das Leben nicht zu ernst zu nehmen. Manchmal ist es wichtig, einfach nur zu lachen und das Leben zu genieÃŸen. Also lass uns gemeinsam lachen und das Leben feiern!

#In diesem Sinne, viel SpaÃŸ beim Lesen und Teilen dieses Textes! Lachen ist die beste Medizin, also lass uns gemeinsam lachen und das Leben genieÃŸen!
Number of characters: 877
Character Dictionary: {'#': 5, 'd': 34, 'a': 46, 's': 63, ' ': 150, 'i': 62, 't': 28, 'm': 26, 'e': 112, 'n': 62, 'o': 12, 'f': 9, 'z': 10, 'r': 23, 'T': 5, 'x': 4, '-': 4, 'l': 31, '.': 8, 'h': 33, '\n': 4, 'c': 22, 'g': 12, ',': 9, 'p': 4, 'u': 25, 'E': 2, 'W': 2, 'Ã': 9, '¶': 1, 'V': 1, 'w': 6, 'j': 2, 'v': 4, '¼': 2, 'b': 12, 'Ÿ': 6, 'M': 3, '!': 5, 'I': 2, 'S': 5, 'L': 7, 'A': 2, 'F': 1, 'U': 1, 'k': 1}

-------Table of characters:----------------
       | cnt=150    p=0.171   H=2.548 bit/char  H_av=0.436 bit/char
 e     | cnt=112    p=0.128   H=2.969 bit/char  H_av=0.379 bit/char
 s     | cnt= 63    p=0.072   H=3.799 bit/char  H_av=0.273 bit/char
 i     | cnt= 62    p=0.071   H=3.822 bit/char  H_av=0.270 bit/char
 n     | cnt= 62    p=0.071   H=3.822 bit/char  H_av=0.270 bit/char
 a     | cnt= 46    p=0.052   H=4.253 bit/char  H_av=0.223 bit/char
 d     | cnt= 34    p=0.039   H=4.689 bit/char  H_av=0.182 bit/char
 h     | cnt= 33    p=0.038   H=4.732 bit/char  H_av=0.178 bit/char
 l     | cnt= 31    p=0.035   H=4.822 bit/char  H_av=0.170 bit/char
 t     | cnt= 28    p=0.032   H=4.969 bit/char  H_av=0.159 bit/char
 m     | cnt= 26    p=0.030   H=5.076 bit/char  H_av=0.150 bit/char
 u     | cnt= 25    p=0.029   H=5.133 bit/char  H_av=0.146 bit/char
 r     | cnt= 23    p=0.026   H=5.253 bit/char  H_av=0.138 bit/char
 c     | cnt= 22    p=0.025   H=5.317 bit/char  H_av=0.133 bit/char
 o     | cnt= 12    p=0.014   H=6.191 bit/char  H_av=0.085 bit/char
 g     | cnt= 12    p=0.014   H=6.191 bit/char  H_av=0.085 bit/char
 b     | cnt= 12    p=0.014   H=6.191 bit/char  H_av=0.085 bit/char
 z     | cnt= 10    p=0.011   H=6.455 bit/char  H_av=0.074 bit/char
 f     | cnt=  9    p=0.010   H=6.607 bit/char  H_av=0.068 bit/char
 ,     | cnt=  9    p=0.010   H=6.607 bit/char  H_av=0.068 bit/char
 Ã     | cnt=  9    p=0.010   H=6.607 bit/char  H_av=0.068 bit/char
 .     | cnt=  8    p=0.009   H=6.776 bit/char  H_av=0.062 bit/char
 L     | cnt=  7    p=0.008   H=6.969 bit/char  H_av=0.056 bit/char
 w     | cnt=  6    p=0.007   H=7.191 bit/char  H_av=0.049 bit/char
 Ÿ     | cnt=  6    p=0.007   H=7.191 bit/char  H_av=0.049 bit/char
 #     | cnt=  5    p=0.006   H=7.455 bit/char  H_av=0.043 bit/char
 T     | cnt=  5    p=0.006   H=7.455 bit/char  H_av=0.043 bit/char
 !     | cnt=  5    p=0.006   H=7.455 bit/char  H_av=0.043 bit/char
 S     | cnt=  5    p=0.006   H=7.455 bit/char  H_av=0.043 bit/char
 x     | cnt=  4    p=0.005   H=7.776 bit/char  H_av=0.035 bit/char
 -     | cnt=  4    p=0.005   H=7.776 bit/char  H_av=0.035 bit/char
 b'\n' | cnt=  4    p=0.005   H=7.776 bit/char  H_av=0.035 bit/char
 p     | cnt=  4    p=0.005   H=7.776 bit/char  H_av=0.035 bit/char
 v     | cnt=  4    p=0.005   H=7.776 bit/char  H_av=0.035 bit/char
 M     | cnt=  3    p=0.003   H=8.191 bit/char  H_av=0.028 bit/char
 E     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 W     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 j     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 ¼     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 I     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 A     | cnt=  2    p=0.002   H=8.776 bit/char  H_av=0.020 bit/char
 ¶     | cnt=  1    p=0.001   H=9.776 bit/char  H_av=0.011 bit/char
 V     | cnt=  1    p=0.001   H=9.776 bit/char  H_av=0.011 bit/char
 F     | cnt=  1    p=0.001   H=9.776 bit/char  H_av=0.011 bit/char
 U     | cnt=  1    p=0.001   H=9.776 bit/char  H_av=0.011 bit/char
 k     | cnt=  1    p=0.001   H=9.776 bit/char  H_av=0.011 bit/char
-------------------------------------------

Average Entropy H = 4.406 bit/char
Total Entropy of 877 characters H=3864.40 bit = 484.00 byte
```
