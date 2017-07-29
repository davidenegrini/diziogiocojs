# DizioGiocoJS

> Metti in gioco le tue conoscenze delle parole italiane!

DizioGioco è una app nata nel 2012 per Windows Phone. Ora è una semplice pagina su GitHub.io che permette di giocarci senza grandi pretese.

Attualmente sviluppata completamente in JavaScript con jQuery.

Accedi al gioco: **https://davidenegrini.github.io/diziogiocojs/**

## Dinamica di gioco

Più facile a farsi che a dirsi: il gioco consiste nel trovare la parola, tratta casualmente da un dizionario italiano, restringendo, man mano si inseriscono nuove parole, il campo delle possibilità.

Lo scopo è indovinare una specifica parola dal dizionario: si inizia inserendo una parola a caso e il gioco risponde dicendo se quella da indovinare viene prima o dopo in ordine alfabetico definendo i nuovi estremi. In questo gioco quindi la parola da indovinare è compresa in ordine alfabetico tra le due scritte: se ad esempio restringiamo il campo tra "aereo" e "barca", una parola possibile è "azzurro", ma non lo saranno sicuramente più "abaco" o "giro".

Questo fino a quando non verrà inserita la parola da trovare, momento in cui il gioco finisce perché... hai vinto la partita!

## Caratteristiche del dizionario italiano integrato

 - Non ci sono parole con trattini, accenti (scrivere la parola togliendoli), punti o altri segni.
 - Presenti solo lettere dalla "a" alla "z".
 - I verbi sono considerati solo all'infinito.

## Cose da fare

Tratte dalle funzionalità già presenti sulla app.

- Possibilità di abbandonare la partita
- Suggerimenti
	- Vengono date le ultime due lettere della parola
	- Viene dato il numero di lettere
- Possibilità di segnalare parole
- Autocompletamento iniziali parola
- Condivisione sui social
