---
layout: page
---

## Esercizio HTML-CSS

In questo Esercizio, utilizzerete le nozioni di HTML e CSS che abbiamo visto a lezione.


### 1. Aspetto generale

La struttura della pagina è a vostra scelta, ma dovrà contenere i seguenti elementi:
* una **intestazione (header)** con il titolo della pagina e un'immagine di sfondo;
* un **menù di navigazione**, disposto orizzontalmente in alto o verticalmente a lato, contenente dei link alle altre sezioni del sito (non è necessario che le pagine a cui fanno riferimento i link esistano);
* una sezione di **contenuti**, che rappresenta il corpo principale della pagina. Questa sezione dovrà essere a sua volta divisa in "blocchi" di informazione (da disporre a vostro piacere utilizzando Flexbox), specifiche per il vostro progetto di sito (es., se si tratta di un quotidiano inline, ogni blocco può rappresentare una notizia; se si tratta di un'agenzia di viaggi, ogni blocco può rappresentare un volo o una prenotazione);
* un **footer** che contiene informazioni sulla pagina (tra cui nome, cognome, matricola).

[A questo link](imgs/mhw1_esempio.png) un esempio di visualizzazione della pagina completa.

### 2. Misure delle sezioni

Stabilite in dettaglio la disposizione delle sezioni del sito (header, menù di navigazione, contenuti, blocchi all'interno dei contenuti, footer) e le distanze tra i diversi elementi della pagina. Illustrate il vostro progetto nella presentazione in maniera analoga a quanto vedete in questa immagine:

![](imgs/specs.png)

È richiesto l'uso delle seguenti proprietà CSS: `margin`, `padding`, `height`, `position`, `border`, `border-radius`, `background-color`.

### 3. Caratteri, dimensioni e colori

Definite il carattere, il colore e la dimensione del testo in ciascuna delle sezioni della pagina definite in "Aspetto generale". Se i blocchi di contenuto sono a loro volta divisibili in sotto-parti, usate uno stile diverso per ciascuna.

Per ogni sezione di testo, definite tramite CSS:
* un carattere principale (da Google Fonts) e un carattere di riserva (non da Google Fonts);
* la dimensione del testo;
* lo stile del testo;
* il colore del testo;
* l'allineamento rispetto al contenitore.

E' richiesto l'uso delle seguenti proprietà CSS: `font-weight`, `font-style`, `font-family`, `font-size`, `color`, `line-height`.

### 4. Immagini

L'intestazione ha un'immagine di sfondo, che non si ripete. Al di sopra dell'immagine vi è un overlay semitrasparente, di colore `rgba(0, 0, 0, .3)`.

La sezioni dei contenuti deve contenere un'immagine per ogni "blocco" di informazione.
