# DizioGiocoJS (DizioGioco)

> Metti in gioco le tue conoscenze delle parole italiane!

**LA LICENZA GNU GPL ( https://github.com/davidenegrini/diziogiocojs/blob/master/LICENSE ) COPRE SIA IL CODICE SORGENTE CHE L'IDEA DEL GIOCO ED IL SUO MECCANISMO**

**Se siete interessati a sviluppare un gioco con questa idea di fondo potete scrivere via email a davidenegrini[at]outlook[dot]com**

DizioGioco è una app nata nel 2012 per Windows Phone 7 e dal 2013 non è più stata aggiornata: ora è diventata un semplice repository su GitHub.

Attualmente sviluppata in JavaScript con jQuery.

Accedi al gioco: **https://davidenegrini.github.io/diziogiocojs/**

## Come giocare

Più facile a farsi che a dirsi: il gioco consiste nel trovare la parola, tratta casualmente da un dizionario italiano, restringendo, man mano si inseriscono nuove parole, il campo delle possibilità.

Lo scopo è indovinare una specifica parola dal dizionario: si inizia inserendo una parola a caso e il gioco risponde dicendo se quella da indovinare viene prima o dopo in ordine alfabetico definendo i nuovi estremi. In questo gioco quindi la parola da indovinare è compresa in ordine alfabetico tra le due scritte: se ad esempio restringiamo il campo tra "aereo" e "barca", una parola possibile è "azzurro", ma non lo saranno sicuramente più "abaco" o "giro".

Questo fino a quando non verrà inserita la parola da trovare, momento in cui il gioco finisce perché... hai vinto la partita!

 - La classificazione della difficoltà si basa su teoriche frequenze di uso nella lingua.
 - I verbi sono solitamente considerati solo all'infinito.
 - Nel dizionario interno sono presenti solo le lettere dalla "a" alla "z" senza accenti, segni diacritici, trattini, punti o altro.
