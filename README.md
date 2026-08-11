# Corriera per la commemorazione di Francesco Guccini

Pagina statica pronta per GitHub Pages per organizzare una condivisione di spese tra privati.

## Impostazione attuale

- quota indicativa: **25 €**
- pullman: **56 posti**
- costo preventivato: **823 €**
- soglia prudenziale: **36 partecipanti**
- raccolta tramite **PayPal Colletta**
- Google Form per raccogliere i dati dei partecipanti
- restituzione delle quote se l'iniziativa non viene organizzata
- eventuale residuo destinato alle spese comuni e a un pranzo conviviale al ritorno
- contatore adesioni manuale

## Prima di pubblicare

Apri `index.html` e sostituisci:

```text
https://forms.google.com/INSERISCI-QUI-IL-TUO-FORM
https://www.paypal.com/pool/INSERISCI-QUI-LA-TUA-COLLETTA
```

con i link reali.

## Aggiornare il numero di partecipanti

Cerca in fondo a `index.html`:

```javascript
const participants = 0;
```

e modifica `0` con il numero di adesioni confermate.

## Pubblicazione su GitHub Pages

1. Crea un repository GitHub, ad esempio `corriera-guccini`.
2. Carica `index.html`, `style.css` e `README.md`.
3. Vai in **Settings → Pages**.
4. In **Build and deployment**, seleziona **Deploy from a branch**.
5. Seleziona il branch `main` e la cartella `/root`.
6. Salva.

GitHub pubblicherà quindi l'indirizzo della pagina.

## Nota privacy

Nel sito pubblico non inserire dati personali dei partecipanti.
I dati personali vanno raccolti solo tramite il modulo dedicato.

## Nota sui pagamenti

Non sono richieste API o chiavi PayPal nel sito.
La pagina contiene soltanto un link esterno alla Colletta PayPal.
