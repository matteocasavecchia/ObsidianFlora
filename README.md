# 🌱 ObsidianFlora — Vault Agricoltura

Knowledge base personale per orto e frutteto biologico, tarata sul clima **mediterraneo costiero del Centro Italia**. Costruita come [Obsidian](https://obsidian.md) vault, pensata per essere navigabile e interrogabile via wikilink e Dataview.

[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

## 📚 Indice

- [Cosa contiene](#cosa-contiene)
- [Struttura cartelle](#struttura-cartelle)
- [Convenzioni](#convenzioni)
- [Setup Obsidian](#setup-obsidian)
- [Come usarlo](#come-usarlo)
- [Licenza](#licenza)
- [Autore](#autore)
- [Contributi](#contributi)

## Cosa contiene

Il vault raccoglie schede pratiche e operative per la coltivazione e l'allevamento domestico, organizzate in più ambiti:

- **30 schede di orticole**: pomodoro, zucchina, melanzana, peperone, cetriolo, cavoli, insalate, radici, bulbi, legumi, cucurbitacee, mais (vedi `10_Schede_Piante/Orticole/`).
- **12 schede di aromatiche**: basilico, rosmarino, salvia, timo, origano, maggiorana, prezzemolo, menta, lavanda, erba cipollina, alloro, melissa (`10_Schede_Piante/Aromatiche/`).
- **10 schede di alberi da frutto**: olivo, agrumi (limone, arancio, mandarino), drupacee (susino, albicocco, mandorlo), fico, melograno, vite (`10_Schede_Piante/Alberi_da_Frutto/`).
- **Pollicoltura**: schede di razza, schede di gestione del pollaio, registro uova e calendario del pollaio, per un allevamento familiare di galline ovaiole (`11_Schede_Pollicoltura/`).
- **Allevamento da latte**: schede di razza (capre, pecore, asina), gestione, registri e calendario per un piccolo allevamento di ruminanti da latte (`12_Schede_Allevamento_Latte/`).
- **Caseificazione**: tecniche di lavorazione del latte, schede dei formaggi e registro di produzione (`13_Caseificazione/`).
- **10 tecniche colturali**: compostaggio, pacciamatura, irrigazione a goccia, consociazioni, rotazioni, difesa biologica, gestione salsedine e vento, semenzaio, sovesci, forme di allevamento e potatura (`30_Tecniche/`).
- **Calendario operativo**: 4 note stagionali + 12 note mensili con semine, raccolte, potature, difesa, lavorazioni tarate sul clima costiero centro-italiano (`20_Calendario/`).

Ogni scheda pianta contiene: frontmatter strutturato (famiglia botanica, ciclo, periodi, distanze, pH, consociazioni, rotazioni), caratteristiche e varietà tradizionali italiane, semina e trapianto, cura annuale, avversità tipiche con difese biologiche, raccolta e conservazione, note specifiche per costa mediterranea.

## Struttura cartelle

```
agricoltura/
├── 00_Indice/                     Home del vault
│   └── Home.md
├── 10_Schede_Piante/              Schede pianta per pianta
│   ├── Orticole/                  (30 schede)
│   ├── Aromatiche/                (12 schede)
│   ├── Alberi_da_Frutto/          (10 schede)
│   └── _MOC_Piante.md             Mappa di tutte le schede (Dataview)
├── 11_Schede_Pollicoltura/        Pollaio familiare
│   ├── Razze/                     Schede di razza (galline)
│   ├── Gestione/                  Schede di gestione del pollaio
│   ├── Registro/                  Registro uova
│   ├── Calendario_Pollaio.md      Promemoria stagionale del pollaio
│   └── _MOC_Pollicoltura.md
├── 12_Schede_Allevamento_Latte/   Piccoli ruminanti da latte (capre, pecore, asina)
│   ├── Razze/                     Schede di razza da latte
│   ├── Gestione/                  Alimentazione, mungitura, riproduzione, salute, anagrafe
│   ├── Registro/                  Registro mungitura, parti e sanitario
│   ├── Calendario_Allevamento.md  Promemoria stagionale (monte, parti, lattazione)
│   └── _MOC_Allevamento_Latte.md
├── 13_Caseificazione/             Lavorazione del latte
│   ├── Tecniche/                  Igiene, coagulazione, salatura, stagionatura...
│   ├── Formaggi/                  Schede ricetta per formaggio/latticino
│   ├── Registro/                  Registro di produzione casearia
│   └── _MOC_Caseificazione.md
├── 20_Calendario/
│   ├── Stagioni/                  4 note: primavera, estate, autunno, inverno
│   ├── Mensile/                   12 note: 01_Gennaio … 12_Dicembre
│   ├── calendario_master.md       Query Dataview riassuntiva
│   └── _MOC_Calendario.md
├── 30_Tecniche/                   10 note tecniche colturali
│   └── _MOC_Tecniche.md
├── 40_Diario/                     Daily notes (Periodic Notes plugin)
│   └── _README_Diario.md
├── 90_Template/                   Template Templater
│   ├── template_pianta_orticola.md
│   ├── template_pianta_aromatica.md
│   ├── template_albero_da_frutto.md
│   ├── template_tecnica.md
│   ├── template_diario.md
│   ├── template_razza_gallina.md
│   ├── template_gestione_pollaio.md
│   ├── template_razza_lattifera.md
│   ├── template_gestione_allevamento.md
│   ├── template_tecnica_casearia.md
│   └── template_formaggio.md
└── _Assets/                       Immagini e allegati
```

I prefissi numerici servono solo a ordinare le cartelle nel pannello laterale di Obsidian (Indice in cima, Template e Assets in fondo). `_MOC_*.md` sono Maps of Content che indicizzano via Dataview tutte le note della cartella corrispondente.

## Convenzioni

### Frontmatter strutturato

Ogni scheda pianta ha un blocco YAML in cima con campi standard (esempio per orticole):

```yaml
---
tipo: scheda_pianta
categoria: orticola
nome_comune: Pomodoro
nome_scientifico: Solanum lycopersicum
famiglia: Solanaceae
ciclo: annuale
periodo_semina: "Febbraio-Marzo (semenzaio); Aprile-Maggio (trapianto)"
periodo_raccolta: "Luglio-Ottobre"
distanza_pianta_cm: 50
distanza_fila_cm: 90
esposizione: sole pieno
consociazioni_buone:
  - Basilico
  - Carota
tags:
  - pianta
  - orticola
---
```

Questi campi vengono letti dai blocchi Dataview nei MOC, che si autopopolano quando si aggiungono nuove schede.

### Wikilink in stile alias

Quando il termine naturale italiano differisce dal nome del file (plurale, genere diverso, frutto vs pianta), si usa la sintassi **alias** di Obsidian:

```markdown
[[Pomodoro|Pomodori]] in piena produzione
[[Olivo|Olive]] tardive
[[Vite|Uva]] da tavola
[[Limone|limone]] verdello
```

Quando il termine coincide col nome del file (es. "Pomodoro" come titolo di voce), si usa il link bare `[[Pomodoro]]`.

### Tag

Tag tematici minimi, condivisi tra schede della stessa famiglia o categoria:
- `#pianta #orticola #solanacee`
- `#pianta #aromatica #mediterraneo`
- `#tecnica #suolo`
- `#calendario #autunno`

## Setup Obsidian

### Plugin consigliati

| Plugin | A cosa serve |
|---|---|
| **Dataview** | Indispensabile. Tutte le tabelle nei MOC e nel calendario master sono query Dataview |
| **Templater** | Per usare i template in `90_Template/` con campi dinamici (data, titolo) |
| **Periodic Notes** | Per le daily notes del diario di campo |
| **Calendar** | Vista calendario sopra le daily notes |
| **Tasks** | Gestione attività con scadenze e ricorrenze (utile per lavori stagionali) |
| **Excalidraw** | Per disegnare la mappa dell'orto, schemi di consociazione |

### Configurazione Periodic Notes

- Daily notes folder: `agricoltura/40_Diario`
- Daily notes format: `YYYY-MM-DD`
- Daily notes template: `agricoltura/90_Template/template_diario`

### Configurazione Templater

- Template folder location: `agricoltura/90_Template`
- (Opzionale) Trigger Templater on new file creation

## Come usarlo

### Aggiungere una nuova pianta

1. Apri Obsidian e crea una nuova nota nella cartella appropriata (es. `10_Schede_Piante/Orticole/`)
2. Dai alla nota il nome della pianta in singolare maiuscolo (es. `Patata`)
3. Inserisci il template Templater corrispondente (`template_pianta_orticola`)
4. Compila i campi del frontmatter e le sezioni del corpo
5. La nota apparirà automaticamente nelle tabelle Dataview del MOC

### Aggiungere una voce di diario

Usa Periodic Notes per creare la daily note di oggi, oppure crea manualmente una nota `YYYY-MM-DD.md` in `40_Diario/`. Il template `template_diario` ha già il frontmatter con campi `piante`, `interventi`, `meteo` che possono essere interrogati via Dataview dalle schede pianta.

### Cercare informazioni

- **Per pianta**: apri `_MOC_Piante.md` e usa le tabelle Dataview, oppure cerca direttamente nella cartella.
- **Per mese**: apri `_MOC_Calendario.md` e seleziona il mese corrente.
- **Per tecnica**: apri `_MOC_Tecniche.md`.
- **Wikilink**: cliccando su `[[Pomodoro]]` ovunque nel vault arrivi alla scheda relativa.

## Licenza

Questo lavoro è rilasciato sotto licenza **[Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/)**.

Sei libero di:

- **Condividere** — copiare e ridistribuire il materiale in qualsiasi formato
- **Modificare** — remixare, trasformare e creare opere derivate, anche per uso commerciale

Alle seguenti condizioni:

- **Attribuzione** — devi citare l'autore, indicare un link alla licenza e segnalare se sono state apportate modifiche
- **StessaLicenza** — se modifichi o crei opere derivate, devi distribuirle con la stessa licenza CC BY-SA 4.0

Vedi `LICENSE` per il testo completo, o https://creativecommons.org/licenses/by-sa/4.0/legalcode.

## Autore

**Matteo Casavecchia** — con l'aiuto di un assistente AI per organizzazione, struttura e prima compilazione dei contenuti. Le note sono basate su pratica orticola biologica mediterranea, tradizione italiana, e fonti consolidate di agronomia.

## Contributi

Suggerimenti, correzioni e ampliamenti sono benvenuti. Apri una **issue** o invia una **pull request** sulla [repo GitHub](https://github.com/matteocasavecchia/ObsidianFlora).

Per chi vuole contribuire schede su nuove piante o tecniche:

1. Forka la repo
2. Crea una nuova nota seguendo i template in `90_Template/`
3. Rispetta le convenzioni di frontmatter e wikilink alias
4. Apri una pull request

## Disclaimer

Le informazioni in questo vault sono di natura divulgativa e basate su pratica orticola comune. Per applicazioni professionali, agricoltura su larga scala, uso di prodotti fitosanitari o questioni di sicurezza alimentare, consulta sempre un agronomo qualificato e la normativa locale.
