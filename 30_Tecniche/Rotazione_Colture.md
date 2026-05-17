---
tipo: tecnica
titolo: Rotazione delle colture
area: pianificazione
difficolta: 2
tempo_richiesto: "Pianificazione annuale: 2 ore"
stagione: invernale (per programmare l'anno)
materiali: []
strumenti:
  - Mappa dell'orto
  - Quaderno o tabella digitale (Dataview su frontmatter)
tags:
  - tecnica
  - pianificazione
  - rotazione
---

# 🔄 Rotazione delle colture

> Area: `=this.area` · Difficoltà: `=this.difficolta`/5 · Tempo: `=this.tempo_richiesto`

## A cosa serve
Non coltivare mai la stessa famiglia botanica nella stessa parcella per più anni di seguito. La rotazione interrompe i cicli dei patogeni del suolo (nematodi, funghi, batteri), evita l'esaurimento mirato dei nutrienti (ogni famiglia ha esigenze diverse), riduce la pressione parassitaria, migliora la struttura del terreno (radici diverse arieggiano e penetrano a profondità diverse). È **la pratica biologica più importante** per la salute del suolo a medio termine.

## Quando farla
- Pianificazione: in inverno (gennaio), prima di seminare l'anno
- Durata minima del ciclo di rotazione: 4 anni (ideale 5-7 per famiglie problematiche come solanacee e brassicacee)

## Materiali e strumenti
- Mappa dell'orto suddiviso in 4 (o più) parcelle uguali
- Storico dei 3-4 anni precedenti
- Tabella delle famiglie botaniche delle colture (vedi sotto)

## Le 4 categorie funzionali

| Categoria | Esempi | Esigenze | Lascia il suolo |
|---|---|---|---|
| **Esigenti** (azotofile) | Solanacee (pomodoro, melanzana, peperone, patata), cucurbitacee (zucca, zucchina, cetriolo, anguria, melone), mais | Letame/compost, fertilità alta | Impoverito |
| **Mediamente esigenti** | Brassicacee (cavoli, broccolo, cavolfiore, rape), apiacee (carota, sedano, finocchio), asteracee (lattuga, radicchio) | Compost, fertilità media | Mediamente impoverito |
| **Poco esigenti** (radici, bulbi) | Amaryllidaceae (cipolla, aglio, scalogno, porro), bietola, spinacio | Compost vecchio o niente | Poco impattato |
| **Migliorative** (azoto-fissatrici) | Fabacee (fagiolo, pisello, fava, cece, lupino), sovesci di trifoglio, veccia | Niente azoto | Arricchito di azoto |

## Schema base a 4 anni

| Anno | Parcella A | Parcella B | Parcella C | Parcella D |
|---|---|---|---|---|
| **Anno 1** | Esigenti (pomodoro) | Mediamente esigenti (cavoli) | Poco esigenti (cipolla) | Migliorative (fagioli) |
| **Anno 2** | Migliorative | Esigenti | Mediamente esigenti | Poco esigenti |
| **Anno 3** | Poco esigenti | Migliorative | Esigenti | Mediamente esigenti |
| **Anno 4** | Mediamente esigenti | Poco esigenti | Migliorative | Esigenti |
| **Anno 5** | = Anno 1 | = Anno 1 | = Anno 1 | = Anno 1 |

La logica: ogni anno le colture "scalano" di una posizione. **Le esigenti seguono sempre le migliorative**, sfruttando l'azoto che hanno fissato nel suolo. Le poco esigenti seguono le mediamente esigenti, non hanno bisogno di terreno ricco.

## Procedimento
1. **Dividere l'orto in parcelle uguali** (4 minimo, meglio 6-8 per maggiore flessibilità)
2. **Categorizzare** le piante che si vogliono coltivare
3. **Compilare la tabella** Anno 1 con la rotazione di base
4. **Programmare gli anni successivi** facendo "scalare" le categorie
5. **Verificare le eccezioni** (vedi sotto)
6. **Annotare nel diario** quale famiglia è stata in ogni parcella (utile a lungo termine)

## Famiglie da non far seguire a se stesse (minimo 3-4 anni)

- **Solanacee**: pomodoro, melanzana, peperone, patata (4+ anni)
- **Brassicacee**: cavoli, broccolo, cavolfiore, rape, ravanello (4-5 anni, per ernia delle crucifere fino a 7)
- **Cucurbitacee**: zucca, zucchina, cetriolo, melone, anguria (3-4 anni)
- **Fabacee**: fagiolo, pisello, fava, cece (4 anni)
- **Apiacee**: carota, sedano, finocchio, prezzemolo (3 anni)
- **Asteracee**: lattuga, radicchio, indivia, scarola, carciofo (3 anni)
- **Amaryllidaceae**: cipolla, aglio, porro, scalogno (4-5 anni per marciume bianco)

## Sovesci e copertura del suolo
In ogni rotazione si può inserire un **sovescio invernale** (segale, veccia, trifoglio, favino) sulle parcelle che resterebbero altrimenti nude. Il sovescio si interra a fine inverno-inizio primavera, arricchisce il suolo di sostanza organica e azoto, mantiene attiva la microfauna. Vedi [[Sovesci]].

## Accorgimenti per il clima costiero
Sulla costa mediterranea, la durata della stagione vegetativa è lunga: si possono inserire **due colture l'anno nella stessa parcella** (es. fave invernali + zucchine estive). In questo caso, contare le due colture come "un anno di rotazione" della famiglia. La salinità lieve favorisce alcune colture (bietola, spinacio) e penalizza altre (legumi sono sensibili): nei terreni costieri molto salini, considerare l'aspetto.

## Errori comuni
- Coltivare le stesse colture nello stesso posto perché "tanto vanno bene": dopo 3-4 anni si accumula la pressione di patogeni e nematodi
- Confondere la "specie" con la "famiglia": pomodoro-patata sono entrambi solanacee, attaccati dagli stessi parassiti
- Ignorare le crucifere: l'ernia delle crucifere persiste 7+ anni nel suolo, richiede rotazione lunga
- Tabelle rigide senza adattare al proprio caso: la rotazione è una guida, non una legge

## Piante / situazioni in cui si applica
- Tutto l'orto biologico e sostenibile
- Vasi e contenitori: meno critica ma comunque utile alternare terriccio o disinfettarlo
- Vigne, frutteti, oliveti: rotazione meno applicabile (piante perenni), ma il **sovescio tra le file** è efficace

## Diario di campo collegato
```dataview
TABLE file.name AS "Nota", meteo AS "Meteo"
FROM "agricoltura/40_Diario"
WHERE contains(interventi, this.file.link) OR contains(file.outlinks, this.file.link)
SORT file.name DESC
LIMIT 10
```

## Riferimenti
- [[_MOC_Tecniche]]
- [[Consociazioni]]
- [[Sovesci]]
- [[Compostaggio]]

#tecnica #pianificazione #rotazione
