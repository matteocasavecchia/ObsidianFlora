---
tipo: tecnica
titolo: Consociazioni
area: pianificazione
difficolta: 2
tempo_richiesto: "Pianificazione annuale: 2-3 ore"
stagione: tutto l'anno
materiali: []
strumenti:
  - Carta e matita (o tabella digitale)
tags:
  - tecnica
  - pianificazione
  - consociazioni
---

# 🌱 Consociazioni

> Area: `=this.area` · Difficoltà: `=this.difficolta`/5 · Tempo: `=this.tempo_richiesto`

## A cosa serve
Coltivare insieme piante che si avvantaggiano a vicenda. Le piante consociate possono: respingere parassiti reciproci (carota + cipolla = doppio scudo contro mosche), occupare strati diversi di suolo e luce (mais alto + zucca a terra + fagiolo che sale), fissare azoto per le vicine (legumi + cavoli, solanacee), attirare impollinatori e predatori utili (borragine, tagete), confondere parassiti con odori contrastanti. Le buone consociazioni aumentano produzione totale, riducono attacchi parassitari, riducono la necessità di trattamenti.

## Quando farla
- Stagione: tutto l'anno, ma la pianificazione annuale si fa in **inverno** (gennaio-febbraio) prima di seminare
- Adattamento: anche durante l'anno si possono inserire consociazioni "tampone" (basilico sotto pomodori dopo il trapianto, lattuga tra i finocchi)

## Materiali e strumenti
- Carta e matita per disegnare la mappa annuale dell'orto
- Tabella delle compatibilità (vedi sotto)
- Frontmatter delle [[_MOC_Piante|schede piante]]: campi `consociazioni_buone` e `consociazioni_da_evitare` di ogni scheda

## Tabella sintetica consociazioni

| Coltura | Compagne consigliate | Da evitare |
|---|---|---|
| **Pomodoro** | Basilico, carota, cipolla, aglio, tagete, prezzemolo | Cavoli, finocchio, patata |
| **Cipolla / Aglio / Porro** | Carota (storica), pomodoro, lattuga, fragola | Legumi (pisello, fagiolo, fava) |
| **Carota** | Cipolla, porro, aglio, lattuga, pomodoro | Aneto, sedano, finocchio |
| **Cavoli** | Lattuga, sedano, aneto, aglio, camomilla | Pomodoro, fragola, altre brassicacee |
| **Cucurbitacee (zucca, zucchina)** | Mais, fagiolo rampicante, ravanello, nasturzio | Patata, altre cucurbitacee |
| **Fagiolo / Pisello** | Mais, carota, lattuga, sedano | Cipolla, aglio, porro, finocchio |
| **Lattuga** | Carota, ravanello, fragola, cavolo, cetriolo | Sedano, prezzemolo, girasole |
| **Finocchio** | (Quasi nessuna, allelopatico) | Quasi tutto: pomodoro, fagiolo, cavolo |
| **Mais** | Fagiolo, zucca (Tre Sorelle), cetriolo | Pomodoro, sedano |

## Procedimento
1. **Mappa**: disegnare le parcelle dell'orto a scala
2. **Coltura principale**: scegliere la coltura "dominante" di ogni parcella per la stagione
3. **Sotto-coltura / vicina**: aggiungere una o due compagne secondo tabella
4. **Tempi**: consociazioni a ciclo diverso (lattuga primaverile sotto pomodoro che diventerà grande in estate)
5. **Aromatica di bordo**: aiuola o fila di basilico, tagete, calendula, borragine ai bordi (attrae predatori utili e impollinatori)
6. **Verifica conflitti**: controllare ogni accoppiamento sulla tabella o sulle schede pianta

## I tre principi delle consociazioni

1. **Diversità degli strati** (suolo / aria): carota fittone profondo + cipolla bulbo + lattuga foglia superficiale
2. **Complementarietà nutrizionale**: legumi (azoto-fissatori) + colture azotofile (cavoli, solanacee, mais)
3. **Difesa reciproca**: odori contrastanti confondono parassiti (carota-cipolla), piante repellenti vicino a colture sensibili (tagete vicino alle solanacee per nematodi)

## Tre Sorelle (esempio classico)
La consociazione precolombiana **mais + fagiolo rampicante + zucca**:
- Mais fornisce sostegno verticale al fagiolo
- Fagiolo fissa azoto che nutre mais e zucca
- Zucca con le foglie larghe copre il suolo, riduce erbacce ed evaporazione

Funziona benissimo anche in orto domestico mediterraneo, attenzione solo a non piantare troppo fitto.

## Accorgimenti per il clima costiero
Nelle estati torride della costa, le piante alte (mais, pomodoro indeterminato, girasole) possono fare ombra parziale e benefica a piante più sensibili al caldo (lattuga, cetriolo, ravanello). La borragine attrae api utili agli agrumi e alle cucurbitacee. Tagete e calendula a margine dell'orto attirano sirfidi e coccinelle, predatori naturali di afidi (frequenti sulla costa).

## Errori comuni
- Mettere insieme piante della stessa famiglia (concentrano patogeni)
- Accostare piante allelopatiche (finocchio, girasole) ad altre senza isolarle
- Trascurare i tempi: lattuga messa sotto un pomodoro già grande non riceve abbastanza luce
- Densità eccessiva: troppo bene = competizione

## Piante / situazioni in cui si applica
- Tutto l'orto biologico
- Aiuole di aromatiche
- Verghi misti (alberi da frutto con aromatiche e fiori al piede)
- Frutteto-orto integrato

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
- [[Rotazione_Colture]]
- [[Difesa_Biologica]]

#tecnica #pianificazione #consociazioni
