# Lezione 1

## Obiettivi 
- Creare un progetto iniziale che funga da base per le successive lezioni.

## Descrizione 
Creare un progetto in Java, con un IDE a piacere (si suggerisce Eclipse o IntelliJ) che rappresenti il seguente dominio.  
Ogni dettaglio non esplicitato è di libera interpretazione.  
I dati gestiti possono essere letti da input o direttamente hard-codati (per il momento), alias scritti direttamente nel sorgente.

## Dominio 
Si è interessati a rappresentare le informazioni riguardanti la gestione di un bestiario (Archivio di mostri).  
All'interno del bestiario, in questa versione iniziale, sono presenti 3 specie di mostri:
- viverne
- slime verdi
- slime rossi

Si è interessati a memorizzare, per ogni specie:
- nome (nickname, un nome proprio dell'esemplare)
- cibo preferito
- età
- data in cui è entrato a far parte dello zoo
- peso
- altezza

Inoltre, per viverne memorizzare la lunghezza della coda; per gli slime la viscosità.


## Operazioni richieste 

Deve essere possibile effettuare le seguenti interrogazioni al sistema: 
- per ogni specie, ricerca dell'esemplare più alto e più basso
- per ogni specie, ricerca dell'esemplare più pesante e più leggero
- per i mostri dotati di coda, l'esemplare con la coda più lunga di tutto il bestiario nel complesso
- per i mostri dotati viscosi come gli slime, l'esemplare con la maggiore viscosità