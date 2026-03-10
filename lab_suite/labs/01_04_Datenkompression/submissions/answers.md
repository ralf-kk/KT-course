# Fragebogen: Wort-Entropie (word_dictionary.py)

Nach dem Ausführen von `word_dictionary.py` mit eigenem Text in `sampletext.txt`:

**Konsolenausgabe einfügen:** Nutze das Merge-Symbol in der Task-Card, um die Ausgabe aus `console_log.txt` hier einzufügen. Anschließend die Ausgabe **kommentieren**.

---

**1. Konsolenausgabe**

*(Wird per „Konsolenausgabe einfügen“ unten eingefügt. Danach bitte kommentieren.)*

---

**2. Deine Kommentierung**

- Wie unterscheidet sich die Wort-Entropie von der Zeichen-Entropie (entropy1.py)?  
  *[kurz beschreiben]*
Die Zeichen-Entropie betrachtet die Verteilung einzelner Buchstaben, während die Wort-Entropie die Verteilung ganzer Wörter betrachtet. Dadurch ist die Wort-Entropie meist größer, weil es viel mehr unterschiedliche Wörter als einzelne Zeichen gibt.

- Was sagt die Entropie in Byte im Vergleich zur tatsächlichen Dateigröße aus?  
  *[kurz begründen]*
Die Entropie gibt die theoretisch minimale Größe nach optimaler Kompression an. Die reale Dateigröße ist größer, weil der Text unkomprimiert gespeichert ist und zusätzlich Format- und Kodierungsinformationen enthält.
---

## Konsolenausgabe

```
Analyze the file:  C:\Users\ralfk\GIT_KT\lab_suite\labs\01_04_Datenkompression\submissions\sidedata/sampletext.txt
```

---

## Konsolenausgabe

```
Analyze the file:  c:\Users\ralfk\GIT_KT\lab_suite\labs\01_04_Datenkompression\sidedata/sampletext.txt
Total number of words:     155
Number of different words: 98

-------Table of words:-----------------------------------------
                             es | cnt=  7    p=0.045   H=4.469 bit/word   H_av=0.202 bit/word
                            und | cnt=  7    p=0.045   H=4.469 bit/word   H_av=0.202 bit/word
                             zu | cnt=  7    p=0.045   H=4.469 bit/word   H_av=0.202 bit/word
                            ist | cnt=  5    p=0.032   H=4.954 bit/word   H_av=0.160 bit/word
                            das | cnt=  5    p=0.032   H=4.954 bit/word   H_av=0.160 bit/word
                         lachen | cnt=  4    p=0.026   H=5.276 bit/word   H_av=0.136 bit/word
                          Leben | cnt=  4    p=0.026   H=5.276 bit/word   H_av=0.136 bit/word
                           dass | cnt=  3    p=0.019   H=5.691 bit/word   H_av=0.110 bit/word
                            ich | cnt=  3    p=0.019   H=5.691 bit/word   H_av=0.110 bit/word
                           wird | cnt=  3    p=0.019   H=5.691 bit/word   H_av=0.110 bit/word
                          SpaÃŸ | cnt=  3    p=0.019   H=5.691 bit/word   H_av=0.110 bit/word
                           beim | cnt=  3    p=0.019   H=5.691 bit/word   H_av=0.110 bit/word
                           lass | cnt=  3    p=0.019   H=5.691 bit/word   H_av=0.110 bit/word
                            uns | cnt=  3    p=0.019   H=5.691 bit/word   H_av=0.110 bit/word
                      gemeinsam | cnt=  3    p=0.019   H=5.691 bit/word   H_av=0.110 bit/word
                             so | cnt=  2    p=0.013   H=6.276 bit/word   H_av=0.081 bit/word
                             Es | cnt=  2    p=0.013   H=6.276 bit/word   H_av=0.081 bit/word
                         lustig | cnt=  2    p=0.013   H=6.276 bit/word   H_av=0.081 bit/word
                            mit | cnt=  2    p=0.013   H=6.276 bit/word   H_av=0.081 bit/word
                           viel | cnt=  2    p=0.013   H=6.276 bit/word   H_av=0.081 bit/word
                          Lesen | cnt=  2    p=0.013   H=6.276 bit/word   H_av=0.081 bit/word
                         dieses | cnt=  2    p=0.013   H=6.276 bit/word   H_av=0.081 bit/word
                        einfach | cnt=  2    p=0.013   H=6.276 bit/word   H_av=0.081 bit/word
                           Also | cnt=  2    p=0.013   H=6.276 bit/word   H_av=0.081 bit/word
                           #das | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                           mein | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                  modifizierter | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                           Text | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          --lol | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                             -- | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                        hahahah | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                           rofl | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                           lmao | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                           #ich | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                            mag | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                           sehr | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                             in | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          einem | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                       Textfile | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                      speichern | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                           muss | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                            der | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                         ganzen | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                           Welt | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                         teilen | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                        mÃ¶chte | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                     Vielleicht | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                             ja | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          viral | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          jeder | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                       darÃ¼ber | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                            Wer | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          weiÃŸ | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                     vielleicht | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          sogar | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                            ein | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          Meme! | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                           #Ich | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          hoffe | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                             du | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                        genauso | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                         Textes | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                           hast | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                            wie | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                      Schreiben | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          hatte | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                             um | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                           fÃ¼r | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                           mich | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                       behalten | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          teile | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                         deinen | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                       Freunden | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                        lachen! | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                           #Und | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                           denk | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          daran | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          immer | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          haben | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          nicht | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          ernst | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                         nehmen | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                       Manchmal | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                        wichtig | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                            nur | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                      genieÃŸen | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                        feiern! | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                            #In | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                         diesem | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          Sinne | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                         Teilen | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                        Textes! | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                         Lachen | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                            die | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                          beste | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                        Medizin | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                           also | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
                     genieÃŸen! | cnt=  1    p=0.006   H=7.276 bit/word   H_av=0.047 bit/word
-----------------------------------------------------------------

Average Entropy H = 6.281 bit/word
Total Entropy of 155 words H=973.586 bit (122 bytes)
Size of text file: 881 bytes
```
