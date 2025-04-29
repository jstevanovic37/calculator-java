Preuzet je fork sa navedenog repozitorijuma.
Fajl Calculator.java ima ukupno 188 linije koda. 
Takodje, primecujem da ima nekoliko praznih linija koda, 
komentari i 
nekoliko viticastih zagrada koje nisu potrebne i mogu se izbaciti.
LOC(lines of code) predstavlja linije koda koje se izvrsavaju. LOC za fajl Calculator.java je 102 linije koda.
LOC za fajl Start.java 14.
Staticka analiza obavlja se pomocu lint alata SonarLint koji je deo iz softverske porodice SonarQube.
Takodje, metode get i set treba da se bolje definisu.
Analiza koda: 18 linija koda nije ispravna, 
duplirani uslovi u if bloku 24 linija koda,
32-37 linija koda(long conditional) dugacka serija if uslova,
duplirane vrednostiif bloka 42-46 linija koda,
63 linija koda sakriva stvarne greske( evaluateEkspresion je predugacka i treba je refraktorisati,
metoda Calculate u 74 liniji koda ne vraca nista,
77 linija koda nije definisana,
84 linija koda nije pregledna,
95,105,118,130,146,170,182 linije koda(Calculate) treba bilje definisati.
