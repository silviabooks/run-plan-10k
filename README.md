# Corsa 10K — Diario allenamento

Pagina singola (PWA) con il piano di 18 settimane per correre 10 km sotto l'ora.
Funziona offline dopo il primo caricamento e si installa sulla schermata home.

## Pubblicare su GitHub Pages

1. Crea un repository pubblico chiamato `corsa-10k` (o simile).
2. Carica **tutti i file di questa cartella nella radice** del repository (non in una sottocartella).
3. Vai in Settings → Pages → Source: `Deploy from a branch`, Branch: `main`, cartella `/ (root)`, Save.
4. Attendi 1-2 minuti. L'indirizzo sarà:
   `https://<tuo-utente>.github.io/corsa-10k/`
5. Apri quell'indirizzo dal telefono con Chrome. Dopo qualche secondo compare
   "Installa app" (o menu ⋮ → "Aggiungi a schermata Home").

## Note

- I dati sono salvati nel browser del telefono (localStorage), non sul server.
- Le sedute a intervalli includono un timer con segnali sonori ai cambi tra corsa e camminata.
- Esporta un backup ogni tanto dal pulsante in fondo alla pagina.
- Se aggiorni `index.html` in futuro, incrementa `CACHE` in `sw.js` (`corsa10k-v3`)
  per forzare il refresh della cache sul telefono.
