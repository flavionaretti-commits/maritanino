# MARITANINO

Cruscotto digitale del plesso Maritano: una Home unica per raggiungere
organizzazione, strumenti, documenti, servizi e risorse del plesso.

## Installazione come PWA

### iPhone / iPad
1. Apri l'indirizzo di MARITANINO con Safari.
2. Tocca **Condividi**.
3. Tocca **Aggiungi alla schermata Home**.
4. Conferma con **Aggiungi**.

### Android
1. Apri MARITANINO con Chrome.
2. Apri il menu del browser.
3. Tocca **Installa app** oppure **Aggiungi a schermata Home**.
4. Conferma.

La Home viene memorizzata per poter essere aperta anche senza rete.
I documenti e i servizi esterni richiedono invece connessione Internet e,
quando previsto, le relative autorizzazioni.

## Aggiornamenti

Per aggiornare la Home basta sostituire `index.html` nella repository.
Quando MARITANINO è online, il service worker prova sempre prima a caricare
la versione più recente dalla rete.

Se in futuro viene modificato `service-worker.js` o cambia la lista dei file
precaricati, aumenta il valore di `CACHE_NAME`, per esempio:
`maritanino-shell-v2`.

## Autore

Sviluppata da **prof. Flavio Naretti – referente del plesso Maritano**.

## Licenze

- Codice: GNU GPL v3.0 (`LICENSE`)
- Contenuti e note sui materiali esterni: `LICENSE-CONTENUTI.md`
