---
tipo: scheda_pianta
categoria: orticola
nome_comune: Fagiolino
nome_scientifico: Phaseolus vulgaris (varietà mangiatutto)
famiglia: Fabaceae
ciclo: annuale
periodo_semina: "Aprile-Luglio (scalare ogni 20 giorni)"
periodo_raccolta: "Giugno-Ottobre"
distanza_pianta_cm: 8
distanza_fila_cm: 50
profondita_semina_cm: 3
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: medio-alto
difficolta: 1
consociazioni_buone:
  - Mais
  - Zucchina / zucca
  - Carota
  - Pomodoro
  - Bietola
  - Cetriolo
consociazioni_da_evitare:
  - Cipolla
  - Aglio
  - Porro
  - Finocchio
successioni_buone:
  - Solanacee
  - Cucurbitacee
  - Cavoli
predecessori_da_evitare:
  - Fabacee
tags:
  - pianta
  - orticola
  - fabacee
  - legumi
---

# 🟢 Fagiolino

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
È un fagiolo (Phaseolus vulgaris) le cui varietà sono selezionate per **mangiare il baccello intero**, tenero, senza filo. Categorie: **nani** (40-50 cm), **rampicanti** (fino a 2 m), e per forma del baccello: cilindrico (tondino), piatto (Helda, corallo), giallo (burro), viola. Varietà classiche: Saxa (nano cilindrico), Marconi (rampicante piatto), corallo nano, Meraviglia di Venezia (piatto giallo). Coltura semplice, produttiva, ideale per chi inizia.

## Semina e trapianto
- Solo semina diretta su terreno caldo (sopra 12°C)
- Aprile-luglio, **scalare ogni 20 giorni** per produzione continua: il fagiolino esaurisce dopo 3-4 settimane di raccolto
- Profondità: 3-4 cm
- Distanze: 8-10 cm sulla fila per nani, 25-30 cm per rampicanti. 50-60 cm tra file (80 per rampicanti)
- A postarella su sostegno per rampicanti

## Cura
- Esposizione: sole pieno
- Irrigazione: regolare, fondamentale in fioritura e formazione baccelli. Goccia al piede, mai sulle foglie
- Pacciamatura organica
- Concimazione: compost in preparazione, niente azoto
- Rincalzo leggero per i nani a 2-3 settimane dall'emergenza
- Sostegno per i rampicanti (palo, rete, "tipi")

## Avversità tipiche
- **Ragnetto rosso**: estate calda e secca, nebulizzazioni e predatori
- **Afide nero, afide del fagiolo**: sapone molle, predatori
- **Ruggine**: rame
- **Antracnosi**: macchie marroni su baccelli. Usare semi sani
- **Marciume del colletto**: ristagni d'acqua

## Raccolta e conservazione
- Baccelli giovani, teneri, ancora privi di filo. Il seme deve essere appena visibile (bombatura leggera). Se diventa grosso, baccello fibroso
- **Raccolta ogni 2-3 giorni** in piena produzione: indispensabile per non bloccare la pianta
- Conservazione: 1 settimana in frigo. Sbianchiti e congelati ottimi. Sott'aceto, sott'olio dopo bollitura

## Consociazioni e rotazioni
- **Compagne**: pomodoro (a riparo dal vento dei rampicanti), mais (tre sorelle), zucchina, carota, bietola, cetriolo
- **Da evitare**: Amaryllidaceae, finocchio
- **Rotazione**: 4 anni per fabacee

## Note clima costiero
Coltura estiva facile per costa centro-italiana. La salsedine non lo disturba. In agosto torrido può fermare la fioritura: pacciamatura, irrigazione regolare, eventuale ombreggiatura nelle ore più calde. Le semine scalari risolvono il "buco" di metà estate.

## Diario di campo collegato
```dataview
TABLE meteo AS "Meteo", interventi AS "Interventi"
FROM "agricoltura/40_Diario"
WHERE contains(piante, this.file.link) OR contains(file.outlinks, this.file.link)
SORT file.name DESC
LIMIT 10
```

## Note personali
- 

## Riferimenti
- [[_MOC_Piante]]
- [[primavera]] · [[estate]] · [[autunno]]

#pianta #orticola #fabacee #legumi
