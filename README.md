# Osservatorio Welfare Italia

Un cruscotto dati e archivio pubblico sul welfare della non autosufficienza in Italia, pensato per chi lavora nei servizi, nella ricerca e nelle istituzioni.

## Cosa fa

Raccoglie in un solo posto i dati ufficiali su spesa sociale dei comuni, posti letto, ospiti dei presidi, trasferimenti INPS e dettaglio dei singoli interventi (assistenza domiciliare, centri diurni, contributi economici, affido, dormitori) — comune per comune, regione per regione.

## Fonti dati

- ISTAT
- INPS
- Ministero della Salute

## Stack tecnico

- Database: PostgreSQL su Neon (~1,7 milioni di righe tra spesa comunale e indicatori)
- Backend: funzioni serverless su Vercel
- Frontend: HTML/JS puro, nessun framework, con Chart.js per i grafici

## Piattaforma live

https://piattaforma-welfare-web.vercel.app/

## Stato del progetto

Progetto aperto, non un prodotto commerciale. Costruito imparando strada facendo — segnalazioni, correzioni e contributi sono benvenuti.

## Licenza

MIT
