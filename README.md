# TFG_2022
Aquest repositor conté el codi que he fet servir per generar les prediccions per el meu TFG. També conté plots que s'han generat abans de fer la predicció per entendre les dades amb les que s'han treballat o despres de la predicció per entrendre millor la predicció.
També contè els fitxers de dades que s'han fet servir per el TFG. 


Per entendre els gràfics s’ha de saber el següent:

Les freqüències petites (125,125,...) es relacionen amb els sorolls greus, i les freqüències grans (8000,4000,...) es relacionen amb els sorolls aguts. En l'eix Y trobarem el resultat de la prova en la freqüència indicada, és a dir, a quina "pressió" necessita el client per començar a escoltar. Per degeneració de l'orella, és a dir, en fer-se gran, les freqüències que es perden més ràpidament són les altes, és a dir els aguts.
S'ha de tenir en compte que les audiometries són proves subjectives, tant per la banda del client com per la banda de l'audioprotetista. S'ha de tenir en compte un error d'uns 5 dB-HZ
Com es podran veure en els gràfics, a partir del 2019 hi ha una disminució de la freqüència en la que es fan audiometries, això passa per dues raons, la primera és per un canvi de política dintre l'empresa i l'altre és per culpa de la covid.
Per poder generar els diferents plots s’ha hagut de passar el temps del format Any-Mes-Dia a format float. Com a resultat,1.0e9 equival a l’any 2001 i 1.6e9 equival a l’any 2022. 
