# Changelog

## 1.0.0 — 2026-11-03
- Prima versione: prezzo più basso degli ultimi 30 giorni prima dello sconto (Direttiva Omnibus, art. 17-bis Codice del Consumo).
- Storico prezzi per prodotto, combinazione, negozio, gruppo clienti e valuta, registrato a ogni variazione (salvataggio prodotto, combinazioni, prezzi specifici), con snapshot giornaliero via cron per sconti a data e regole catalogo.
- Avviso in scheda prodotto e (opzionale) negli elenchi; testo per lingua con segnaposto `{price}` e `{days}`.
- Nessun dato inventato: senza storico sufficiente l'avviso non compare.
