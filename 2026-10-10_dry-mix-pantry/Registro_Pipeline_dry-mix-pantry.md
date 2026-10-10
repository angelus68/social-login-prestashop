# Registro Pipeline — dry mix pantry

- **Keyword principale:** dry mix pantry (variante lunga: dry mix pantry cookbook)
- **Mercato / lingua:** Amazon.com — inglese US
- **Tipologia:** B — Ricettario / cucina: ricettario di mix secchi da dispensa (homemade dry mixes in barattolo), full content con interni a colori
- **Cartella progetto:** `2026-10-10_dry-mix-pantry/` (repository `angelus68/social-login-prestashop`, branch `claude/festive-maxwell-ksfior`)
- **Avvio pipeline:** 2026-10-10
- **Stato:** in lavorazione — piano PROPOSTO, in attesa della conferma ★ dell'utente

## Intake (Fase 0) — assunzioni dichiarate

L'utente ha fornito il link del competitor che oggi occupa la posizione 1 organica per la ricerca "dry mix pantry" su Amazon.com e ha chiesto un libro migliore dei concorrenti. Dalla richiesta si ricavano senza ambiguità:

| Voce | Valore assunto | Da dove viene |
|---|---|---|
| Keyword principale | dry mix pantry | parametro `keywords=dry+mix+pantry` dell'URL Amazon fornito |
| Mercato / lingua | Amazon.com, inglese US | dominio dell'URL |
| Tipologia | B — Ricettario / cucina | il competitor è un ricettario di mix secchi |
| Competitor di riferimento | *The Amish Dry Mix Pantry Cookbook: 150 Easy, Budget-Friendly From-Scratch Baking Mixes, Soups, Gravies & Seasonings* — Molly Danvers, ASIN B0HJXTPBFK | URL fornito (incollato 3 volte, stesso libro) |
| Materiali già esistenti | nessuno nella cartella | nessun file caricato |

Se una di queste assunzioni è sbagliata, basta dirlo: si corregge qui e si riparte.

## Piano di lavoro PROPOSTO (Famiglia B — ricettario: tutte le fasi ★ consigliate)

| # | Fase | Skill | Nel piano | Stato | Note |
|---|---|---|---|---|---|
| 1 | Avatar cliente | lsp-avatar-analisi | ★ | in corso (ricognizione preliminare fatta; Data Mining Report bloccato: servono recensioni + screenshot SERP) | Amazon non raggiungibile dal cloud: vedi Diario |
| 2 | Concept & Positioning | lsp-book-concept-positioning | ★ | da fare | nicchia satura di cloni: la differenziazione è tutto |
| 3 | Copertina — Momento A | lsp-cover-studio | ★ | da fare | 3 bozze front cover; prerequisito generatore immagini |
| 4 | Outline | lsp-outline-studio | ★ | da fare | indici dei competitor dagli estratti Kindle (serve Chrome/Amazon) |
| 5 | DNA stilistico | lsp-dna-stilistico | ★ | da fare | per i ricettari è preziosa la modulazione teoria vs ricette |
| 6 | Scrittura + Interni | lsp-interni-studio | ★ | da fare | interni a colori con foto dei barattoli/piatti: il grosso del lavoro |
| 7 | Revisione | lsp-revisione-studio | ★ | da fare | tanto testo e tante quantità: gate obbligato prima del PDF |
| 8 | Copertina — Momento B | lsp-cover-studio | ★ | da fare | solo con conteggio pagine definitivo |
| 9 | Immagini marketing / A+ | lsp-aplus-studio | ★ | da fare | destinazione: Contenuto A+ |
| 10 | Listing | lsp-listing-studio | ★ | da fare | serve Chrome/Amazon per validare keyword e categorie |
| 11 | Traduzione | lsp-traduzione-studio | Opzionale | da valutare a libro finito | la nicchia è anglofona; mercato UK possibile |

### Prerequisiti tecnici da verificare prima di procedere

- **Chrome reale con sessione Amazon attiva** (fasi 1, 4, 10): dal cloud Amazon.com è bloccato dalla policy di rete (403 sul proxy). Opzioni: eseguire quelle fasi da Claude Code locale con l'estensione Claude in Chrome, oppure caricare nella cartella progetto i file che le fasi chiedono (recensioni `.md` + screenshot SERP `.pdf`).
- **Generatore di immagini** (fasi 3, 6, 8, 9): le schede citano il connettore Higgsfield; in questa sessione non è presente, mentre è disponibile il connettore Magnific (generazione e ritocco immagini). Da verificare con la skill copertina se è un sostituto accettabile.
- **Modulo `lsp-brand-kit`**: presente e funzionante (font Poppins di ripiego + Source Serif 4, logo ufficiale).

## Decisioni chiave

- Titolo ★: da decidere in Fase 2/3
- Pen name ★: da decidere in Fase 2/3
- Trim size / pagine: da definire in Fase 6

## Cartella di pubblicazione

- Stato: da preparare
- Percorso: `PUBBLICAZIONE_KDP_dry-mix-pantry/`

## Diario

- 2026-10-10 Pipeline avviata dalla keyword "dry mix pantry" e dal competitor B0HJXTPBFK. Intake con assunzioni dichiarate (vedi sopra). Piano proposto: tutte le fasi ★ (Famiglia B), traduzione opzionale.
- 2026-10-10 Amazon.com non raggiungibile dall'ambiente cloud (policy di rete: CONNECT 403; anche Goodreads e i blog di recensioni non risolvono). Raccolta dati fatta solo tramite ricerca web (snippet). Prodotta la ricognizione preliminare della nicchia: `00_ricerca_nicchia/Ricognizione_Nicchia_dry-mix-pantry.md` (+ PDF). NON è il Data Mining Report: la Fase 1 resta da completare con le recensioni reali.
- 2026-10-10 Punto di ripresa: (1) conferma o modifica del piano ★ da parte dell'utente; (2) recensioni dei competitor + screenshot SERP nella cartella progetto, oppure sessione locale con Chrome/Amazon; poi si invoca `lsp-avatar-analisi` per il Data Mining Report completo.
