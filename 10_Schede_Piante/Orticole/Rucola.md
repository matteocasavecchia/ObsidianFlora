---
tipo: scheda_pianta
categoria: orticola
nome_comune: Rucola
nome_scientifico: Eruca sativa (rucola coltivata) / Diplotaxis tenuifolia (rucola selvatica)
famiglia: Brassicaceae
ciclo: annuale (coltivata) / perenne (selvatica)
periodo_semina: "Tutto l'anno (clima costiero), scalare"
periodo_raccolta: "30-40 giorni dopo la semina"
distanza_pianta_cm: 5
distanza_fila_cm: 20
profondita_semina_cm: 0.5
esposizione: sole pieno (mezz'ombra in estate)
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: medio
difficolta: 1
consociazioni_buone:
  - Lattuga
  - Carota
  - Pomodoro (sotto)
  - Fagiolo
consociazioni_da_evitare:
  - Altre brassicacee
successioni_buone:
  - Quasi tutto
predecessori_da_evitare:
  - Brassicacee
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - brassicacee
  - foglia
---

# 🌿 Rucola

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Due specie diverse vendute entrambe come "rucola". La **rucola coltivata** (Eruca sativa, foglia larga, sapore più delicato) e la **rucola selvatica** (Diplotaxis tenuifolia, foglia frastagliata, sapore più piccante e marcato). La selvatica è perenne e ricaccia per anni dallo stesso cespo, la coltivata è annuale e a ciclo breve. Crescita facilissima.

## Semina e trapianto
- Solo semina diretta, in fila o a spaglio
- Praticamente tutto l'anno sulla costa centro-italiana
- Profondità: 0.5 cm
- Distanze: 5 cm sulla fila, 15-20 cm tra le file. A spaglio in piccole superfici
- Semine scalari ogni 15-20 giorni per produzione continua

## Cura
- Esposizione: sole pieno autunno-inverno, mezz'ombra in estate
- Irrigazione: regolare. Stress idrico = sapore molto piccante, foglia coriacea
- Pacciamatura sottile
- Concimazione minima

## Avversità tipiche
- **Altica**: il nemico principale. Fori tondi sulle foglie, soprattutto a primavera. Reti antinsetto, irrigazione costante
- **Lumache** sulle piantine giovani
- **Andata a seme**: ciclo breve, fiorisce velocemente con il caldo. I fiori sono comunque commestibili e graziosi nelle insalate

## Raccolta e conservazione
- Taglio quando le foglie raggiungono 8-12 cm, mai aspettare oltre o diventa coriacea
- **Taglio-e-ricresce**: la pianta ricaccia 2-3 volte se si taglia 2 cm sopra il colletto
- Conservazione: 3-4 giorni in frigo
- Anche i fiori bianchi sono ottimi in insalata, decorativi e piccanti

## Consociazioni e rotazioni
- **Compagne**: lattuga (insieme fanno un'ottima insalata mista anche dal vivo), carota, pomodoro (sotto, sfrutta lo spazio prima che le solanacee chiudano), fagiolo
- **Da evitare**: altre brassicacee
- **Rotazione**: 2-3 anni per brassicacee

## Note clima costiero
La rucola selvatica è una pianta spontanea dei pascoli mediterranei costieri: si autosemina facilmente, una volta lasciata andare a seme nell'orto torna ogni anno. Tolleranza salsedine ottima. In piena estate va ombreggiata o si rifugia in un angolo fresco dell'orto. Eccellente coltura "riempi-spazi" tra le grandi colture estive.

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
- [[primavera]] · [[estate]] · [[autunno]] · [[inverno]]

#pianta #orticola #brassicacee #foglia
