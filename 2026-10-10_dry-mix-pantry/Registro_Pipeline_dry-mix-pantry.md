# Registro Pipeline — dry mix pantry

- **Keyword principale:** dry mix pantry
- **Mercato / lingua:** Amazon.com — inglese US
- **Tipologia:** B — Ricettario / cucina: homemade dry mixes da dispensa, cucina da zero a basso costo (nicchia "Amish pantry / dry mix cookbook")
- **Cartella progetto:** `2026-10-10_dry-mix-pantry/` (repository `angelus68/social-login-prestashop`, branch `claude/cool-dirac-8k4lla`)
- **Avvio pipeline:** 2026-10-10
- **Stato:** in lavorazione

## Competitor di riferimento

- *Amish Pantry Cookbook: Budget-Friendly From Scratch…* — ASIN B0HJXTPBFK — https://www.amazon.com/dp/B0HJXTPBFK (SERP "dry mix pantry", posizione 1 al 2026-10-10)
- Altri competitor della nicchia: da individuare in Fase 1 (SERP della keyword) e Fase 2.

## Piano di lavoro approvato

| # | Fase | Skill | Nel piano | Stato | Note |
|---|---|---|---|---|---|
| 1 | Avatar cliente | lsp-avatar-analisi | ★ | da fare | fonte dati: Amazon via fetch diretto (opzione B), senza sessione Chrome |
| 2 | Concept & Positioning | lsp-book-concept-positioning | ★ | da fare | |
| 3 | Copertina — Momento A | lsp-cover-studio | ★ | da fare | generatore immagini: Magnific (Higgsfield non collegato) |
| 4 | Outline | lsp-outline-studio | ★ | da fare | estratti/indici competitor via fetch diretto o fonti terze |
| 5 | DNA stilistico | lsp-dna-stilistico | ★ | da fare | ricettario: modulazione teoria vs ricette |
| 6 | Scrittura + Interni | lsp-interni-studio | ★ | da fare | interni a colori con foto: Magnific |
| 7 | Revisione | lsp-revisione-studio | ★ | da fare | |
| 8 | Copertina — Momento B | lsp-cover-studio | ★ | da fare | dopo conteggio pagine definitivo |
| 9 | Immagini marketing / A+ | lsp-aplus-studio | ★ | da fare | destinazione: Contenuto A+; Magnific |
| 10 | Listing | lsp-listing-studio | ★ | da fare | SERP/categorie via fetch diretto |
| 11 | Traduzione | lsp-traduzione-studio | — | | opzionale, da rivalutare a libro finito |

## Vincoli dell'ambiente (sessione cloud)

- Nessuna estensione Claude in Chrome: i dati Amazon si raccolgono via fetch diretto (scelta ★ dell'utente: opzione B) e, dove Amazon blocca, con materiali caricati dall'utente.
- Higgsfield non collegato: generazione immagini con **Magnific** (scelta ★ dell'utente) nelle fasi 3, 6, 8, 9.
- Modulo lsp-brand-kit presente: PDF on brand per ogni consegna.
- Al 2026-10-10 16:21 UTC l'host `www.amazon.com` risulta negato dalla policy di rete dell'ambiente: da sbloccare nelle impostazioni dell'ambiente (Network access).

## Decisioni chiave

- Titolo ★: da decidere (Fase 2 / Fase 3)
- Pen name ★: da decidere (Fase 2 / Fase 3)
- Trim size / pagine: da definire (Fase 6)
- Generatore immagini ★: Magnific
- Raccolta dati Amazon ★: opzione B (fetch diretto dall'ambiente)

## Cartella di pubblicazione

- Stato: da preparare
- Percorso: `PUBBLICAZIONE_KDP_dry-mix-pantry/`

## Diario

- 2026-10-10 Pipeline avviata. Piano approvato dall'utente: fasi attive 1-10, fase 11 esclusa (opzionale, a libro finito). Scelte ★: dati Amazon via opzione B, immagini con Magnific.
