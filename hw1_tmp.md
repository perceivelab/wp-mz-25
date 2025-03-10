## Homework 1

Lo scopo dell'homework è quello di realizzare un sito web (3-5 pagine distinte, oltre a quelle di registrazione/login/logout) che integri quanto visto finora nel corso (HTML, CSS, JavaScript, PHP e interazione con DBMS), estendendo la tematica sviluppata nei precedenti mini-homework.

In particolare, è richiesto l'utilizzo di API REST da PHP (ad esempio, per servizi che richiedono l'utilizzo di credenziali segrete) e l'accesso a queste tramite JavaScript (accedendo tramite `fetch` ad API del vostro sito stesso).

### Funzionalità richieste

- Meccanismo di registrazione, login, logout degli utenti, con opportuna validazione dei dati (sia lato client che lato server).
Dal lato client, le minime validazioni richieste sono: username già in uso, password con una struttura ben definita (ad esempio, vincoli sulla lunghezza minima, sulla presenza di maiuscole, numeri, simboli, ecc.).
- La home page deve contenere dei contenui caricati accedendo tramite API REST a pagine PHP del vostro sito.
- La home page deve supportare meccanismi di interazione con l'utente tramite JavaScript e richieste asincrone, finalizzate al salvataggio su database di informazioni inserite dall'utente (ad esempio, "like" a elementi, commenti, chat, inserimento in un carrello, salvataggio tra preferiti, ricerca di contenuti, e così via).
- Le pagine oltre la home page sono a vostra scelta, col vincolo che l'eventuale caricamento di contenuti debba sempre avvenire tramite API REST.
- Il sito deve prevedere la possibilità di ricercare contenuti tramite API REST esterne oltre che inserire nel database alcuni dei contenuti scelti dall'utente.
- **In generale, sarà oggetto di valutazione l'uso di richieste asincrone tramite JavaScript al posto di ricaricamenti della pagina.**

### Consegna

La consegna del MHW dovrà essere effettuata sul vostro repository GitHub e dovrà includere:
- tutti i file necessari (HTML, CSS, JavaScript, PHP, immagini); la pagina principale del sito dovrà chiamarsi `index.php`;
- esportazione del database (file .sql, non la cartella data).

**Importante**: i file devono essere caricati direttamente nella cartella principale del repository, e non sotto forma di file compressi (es. zip).
Inoltre, il nome del repository **deve essere testualmente `hw1`**, non `HW1` o `homework1` o qualunque altra cosa.

### Altre specifiche

Per una piena valutazione, rispettate le seguenti specifiche:

- **Utilizzate le nozioni di HTML, CSS, JavaScript e PHP che abbiamo visto a lezione.**
- **Rispettate la separazione delle responsabilità**.
- **Seguite le linee guida** che abbiamo presentato durante le lezioni.
- **Usate nomi descrittivi, indentate il codice,** e in generale seguite le buone norme relativa alla programmazione.
