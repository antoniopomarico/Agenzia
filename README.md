# AgenziaPro — versione iniziale

Gestionale web responsive per uso personale, con sei aree: Censimento, Acquisizione, Incarichi attivi, Appuntamenti, Valutatore immobiliare e Opportunità.

## Avvio
Apri `index.html` in un browser moderno oppure pubblica il contenuto su GitHub Pages.

## Installazione su iPhone
Dopo la pubblicazione HTTPS, apri il sito in Safari → Condividi → Aggiungi alla schermata Home.

## Dati e limiti importanti
- Questa prima versione salva i dati nel browser del dispositivo tramite `localStorage`.
- Non c'è ancora login né sincronizzazione tra dispositivi o utenti.
- Le foto vengono conservate localmente nel browser; usa immagini leggere.
- Esporta regolarmente un backup JSON con il pulsante "Esporta backup".
- La valutazione è un calcolo orientativo parametrico, non una perizia e non sostituisce comparabili verificati, OMI o sopralluogo.
- Prima di inserire nominativi, telefoni, dati catastali o documenti di terzi, considera gli obblighi GDPR, la sicurezza e i tempi di conservazione. Evita di caricare documenti d'identità o dati non necessari.

## Evoluzioni consigliate
1. Database cloud con account e sincronizzazione.
2. Ruoli e permessi, backup automatici e audit log.
3. Foto e allegati su storage protetto.
4. Calendario con notifiche.
5. Gerarchia Censimento → Zona → Indirizzo → Civico e collegamento diretto alle schede catastali.
