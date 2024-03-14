---
layout: page
---

## Mini-homework 1

In questo MHW, sceglierete l'idea progettuale che seguirete per tutti gli esercizi successivi.
L'idea deve essere ispirata ad un sito web esistente; il sito non deve essere troppo complesso, perché l'obiettivo è che nell'ultimo esercizio del corso siate in grado di replicarne
le funzionalità principali, gestendo sia il lato client che il lato server. Ad esempio, le seguenti tipologie di sito web potrebbero essere adatte:
- blog o magazine online;
- social network;
- ristorazione;
- e-commerce;
- gestione di eventi (es. concerti).

Il primo MHW consiste quindi nella replicazione dell'aspetto della pagina web principale del sito scelto, usando solamente HTML e CSS.
In particolare, i requisiti di questo esercizio sono:
- utilizzare layout Flexbox;
- utilizzare specifici elementi HTML:
  - `nav`, `header`, `article`, `section`, `footer`;
- realizzare overlay di testo su immagini;
- utilizzare specifiche proprietà CSS:
  - layout e sfondo: `margin`, `padding`, `height`, `position`, `border`, `border-radius`, `background-color`;
  - font: `font-weight`, `font-style`, `font-family`, `font-size`, `color`, `line-height`;
- utilizzare almeno un font da Google Fonts;
- utilizzare media query per adattare la pagina a dispositivi mobile.

### Consegna

Per partecipare a questo MHW, è **obbligatorio** comunicarci preventivamente (entro i primi 5 giorni dall'assegnazione del MHW) il sito web che intendete replicare, attraverso questo [form](https://forms.gle/UdThfPuiYCLveCkJ6).

La consegna del MHW dovrà essere effettuata sul vostro repository GitHub e dovrà includere:
- i file `mhw1.html`, `mhw1.css` e le immagini da inserire nella pagina;
- una presentazione in PowerPoint, `mhw1.pptx`, che riporta l'URL del sito web di riferimento e uno screenshot della pagina che si è cercato di replicare.

**Importante**: i file devono essere caricati direttamente nella cartella principale del repository, non in sottocartelle né in file compressi (es. zip).
Inoltre, il nome del repository **deve essere testualmente `mhw1`**, non `MHW1` o `minihomework1` o qualunque altra cosa.


### Altre specifiche

Per una piena valutazione, rispettate le seguenti specifiche:

- **Utilizzate l'HTML e il CSS che abbiamo visto a lezione.**
  Non utilizzate codice HTML/CSS che non abbiamo studiato.
  Non utilizzate librerie aggiuntive (es. Bootstrap).
  - **Nota:** qualora riscontriate problemi relativi all'ordine con cui certi elementi si sovrappongono
    (ad es., l'overlay e il testo dell'header; oppure l'header e l'immagine di profilo),
    utilizzate la proprietà [`z-index`](https://developer.mozilla.org/en-US/docs/Web/CSS/z-index). 
- **Non usate JavaScript**.
- **Rispettate la separazione delle responsabilità**.
  Il vostro codice HTML deve descrivere il contenuto e la struttura della pagina, e il vostro codice CSS deve descrivere l'aspetto della pagina.
- **Mobile web**. Aggiungete opportunamente il codice HTML e CSS necessario affinchè il sito sia fruibile da dispositivi mobili
  (effettuate i test tramite il _device mode_ di Google Chrome).
- **Seguite le linee guida** che abbiamo presentato durante le lezioni.
- **Minimizzate la ridondanza nel CSS.** Cercate di non avere regole di stile ridondanti, se c'è il modo di sfruttare l'ereditarietà o selettori appropriati.
- **Usate nomi descrittivi, indentate il codice,** e in generale seguite le buone norme relativa alla programmazione.
