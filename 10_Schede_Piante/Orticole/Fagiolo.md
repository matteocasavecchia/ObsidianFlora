---
tipo: scheda_pianta
categoria: orticola
nome_comune: Fagiolo
nome_scientifico: Phaseolus vulgaris
famiglia: Fabaceae
ciclo: annuale
periodo_semina: "Aprile-Luglio"
periodo_raccolta: "Luglio-Ottobre"
distanza_pianta_cm: 10
distanza_fila_cm: 60
profondita_semina_cm: 3
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: medio
difficolta: 1
consociazioni_buone:
  - Mais
  - Zucca / zucchina
  - Carota
  - Sedano
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
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - fabacee
  - legumi
---

# 🟤 Fagiolo (da sgranare)

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Legume estivo originario dell'America, naturalizzato in tutta Europa. Esistono **fagioli rampicanti** (1.5-2.5 m, su sostegno) e **fagioli nani** (40-60 cm, autoreggenti). Varietà classiche italiane da sgranare: borlotto di Vigevano, cannellino, di Spagna (grosso), Zolfino del Pratomagno, lamon, cuneo, occhio nero. I fagiolini (mangiabaccelli) hanno scheda dedicata.

## Semina e trapianto
- Solo semina diretta, su terreno caldo (suolo sopra 12°C)
- Aprile-luglio sulla costa, scalare ogni 30 giorni per produzione continua
- Profondità: 3-4 cm
- Distanze: 10 cm sulla fila per nani, 30 cm per rampicanti su sostegno. 60-80 cm tra le file
- A postarella: 4-5 semi per buca con palo al centro per i rampicanti

## Cura
- Esposizione: sole pieno
- Irrigazione: regolare, soprattutto in fioritura e formazione baccelli. Mai sulle foglie
- Pacciamatura organica indispensabile in estate
- Concimazione: compost in preparazione, mai azoto
- **Sostegno robusto per i rampicanti**: pali di nocciolo o canne incrociate, rete da pisello alta 2 m, sistema "tipi" indiani con 3 pali legati in cima

## Avversità tipiche
- **Tonchio del fagiolo** (Acanthoscelides obtectus): la peste della conservazione, larve nei semi secchi. Congelatore 48 ore appena sgranati
- **Antracnosi** (Colletotrichum lindemuthianum): macchie marrone scuro su baccelli. Usare semi sani, ruotare
- **Ruggine**: pustole arancioni sotto le foglie. Rame in casi gravi
- **Afidi, ragnetto rosso**: rimedi classici
- **Marciume del colletto**: ristagni, terreno mai compatto

## Raccolta e conservazione
- **Fagiolo fresco da sgranare** ("scapola"): baccelli ancora verdi ma semi formati e ben pieni. Sgranati al momento
- **Fagiolo secco**: piante secche in campo, baccelli marroni, sgranati a posteriori (battitura su telo)
- Conservazione fresca: 1 settimana in frigo. Secca: 2+ anni in barattoli ermetici dopo congelamento

## Consociazioni e rotazioni
- **Tre sorelle**: classica consociazione mais (sostegno) + fagiolo rampicante (azoto) + zucca (copertura). Funziona benissimo
- **Compagne**: carota, sedano, bietola, cetriolo, lattuga
- **Da evitare**: Amaryllidaceae, finocchio
- **Rotazione**: 4 anni per fabacee. Eccellente predecessore di tutte le verdure azotofile

## Note clima costiero
Il fagiolo ama il caldo estivo: la costa centro-italiana è ideale. Tolleranza salsedine media. In agosto torrido può rallentare: una pacciamatura spessa e bagnature regolari mantengono produzione. Da considerare la semina scalare per evitare il blocco di metà estate: una a fine aprile e una a giugno-luglio per produzione fino a ottobre.

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Irrigazione_a_Pioggia]]
- [[primavera]] · [[estate]] · [[autunno]]

#pianta #orticola #fabacee #legumi
