# Italiano con Roberto Fader 🇮🇹

Materiale didattico interattivo di **Roberto Fader** per imparare l'italiano attraverso la cultura italiana.

Il sito è una raccolta di lezioni: la pagina principale (`index.html`) è il catalogo, e ogni lezione vive nella sua cartella dentro `lezioni/`.

```
index.html                         ← catalogo di tutte le lezioni
lezioni/
  01-musica-italiana/index.html    ← lezione 01
  02-.../index.html                ← le prossime lezioni
```

## Aggiungere una nuova lezione

1. Copiare la cartella di una lezione esistente, ad esempio `lezioni/01-musica-italiana/`, con un nuovo nome (`lezioni/02-cucina-italiana/`).
2. Modificare i contenuti del nuovo `index.html` (titolo, testi, esercizi, soluzioni).
3. Nel nuovo file cambiare anche `var prefix='robertoit-musica-v1-';` con un prefisso unico (es. `'robertoit-cucina-v1-'`), così i progressi di ogni lezione restano separati.
4. In `index.html` (il catalogo) copiare un blocco `<li>` della lista `lessons` e aggiornare link, numero, titolo e descrizione.

## Lezione 01: La musica italiana oggi

**Livello:** A2–B1  
**Durata indicativa:** 60 minuti  
**Lingue:** italiano, con supporto lessicale e didattico in russo.

La lezione comprende:
- introduzione e obiettivi comunicativi;
- lettura originale sull'opera, la canzone d'autore, il pop e il Festival di Sanremo;
- 12 voci lessicali in italiano con traduzione russa;
- quattro strutture grammaticali e un esercizio autocorrettivo;
- sei domande di comprensione con spiegazioni;
- note culturali su Sanremo, Carnevale di Venezia e cappuccino;
- attività di conversazione, produzione scritta, soluzioni per l'insegnante;
- sintesi vocale italiana, quando supportata dal dispositivo.

## Aprire e pubblicare

Il sito è composto solo da file HTML statici. Non richiede build, dipendenze, account, database o tracciamento.

Per pubblicarlo come sito pubblico:

1. Aprire il repository su GitHub.
2. Andare in **Settings → Pages**.
3. Scegliere **Deploy from a branch**, quindi **main** e **/(root)**.
4. Salvare le impostazioni.

Dopo aver abilitato GitHub Pages, l'indirizzo previsto è:

https://luisfader.github.io/robertoit/

La prima lezione si trova in https://luisfader.github.io/robertoit/lezioni/01-musica-italiana/

Gli URL sopra funzionano solo quando GitHub Pages viene attivato e il deploy si completa.

## Note didattiche

La lettura è un testo originale ispirato a una lezione di italiano sull'argomento, non una riproduzione della registrazione. Le date del Carnevale di Venezia cambiano di anno in anno; il consumo del cappuccino al mattino è una consuetudine, non un divieto.

Il tasto **RU** nasconde o mostra gli aiuti in russo. Il quiz e le frasi grammaticali sono corretti direttamente nel browser. Il testo scritto e l'avanzamento sono salvati esclusivamente nel `localStorage` del dispositivo. Il pulsante «Ascolta il testo» usa, se disponibile, la sintesi vocale italiana del sistema e non la registrazione originale.

## Personalizzazione

Palette ispirata all'Italia: verde profondo, rosso terracotta, crema e oro. Layout responsive, navigazione interna, controlli accessibili e modalità di stampa. Ogni lezione contiene i propri stili e la propria logica in un unico file, per facilitare la distribuzione.

**Autore del materiale:** Roberto Fader.
