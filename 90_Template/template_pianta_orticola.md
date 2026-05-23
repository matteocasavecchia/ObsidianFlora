---
tipo: scheda_pianta
categoria: orticola
nome_comune: <% tp.file.title %>
nome_scientifico: 
famiglia: 
ciclo: annuale
periodo_semina: 
periodo_raccolta: 
distanza_pianta_cm: 
distanza_fila_cm: 
profondita_semina_cm: 
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: medio
difficolta: 2
consociazioni_buone: 
consociazioni_da_evitare: 
successioni_buone: 
predecessori_da_evitare: 
tags:
  - pianta
  - orticola
---

# 🥬 <% tp.file.title %>

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
_(descrizione generale, varietà adatte al clima costiero mediterraneo, esigenze chiave)_

## Semina e trapianto
- Periodo: `=this.periodo_semina`
- Profondità semina: `=this.profondita_semina_cm` cm
- Distanze: `=this.distanza_pianta_cm` cm sulla fila, `=this.distanza_fila_cm` cm tra le file
- Modalità: _(semina diretta, semenzaio, trapianto...)_

## Cura
- Esposizione: `=this.esposizione`
- Irrigazione: _(frequenza, accortezze estive, tipo di impianto)_
- Concimazione: _(letame maturo, compost, sovescio precedente...)_
- Sostegni / sarchiature / cimature: _(se applicabile)_

## Avversità tipiche
- Parassiti: _(es. afidi, tuta absoluta, oziorrinco...)_
- Malattie: _(peronospora, oidio, alternaria...)_
- Note clima costiero: _(salsedine, umidità, venti)_
- Strategie biologiche: _(consociazioni, macerati, predatori naturali)_

## Raccolta e conservazione
- Periodo: `=this.periodo_raccolta`
- Indici di maturazione: _(colore, consistenza, dimensione...)_
- Conservazione: _(fresco, sott'olio, essiccato, congelato...)_

## Consociazioni e rotazioni
- **Compagne buone**: `=this.consociazioni_buone`
- **Da evitare**: `=this.consociazioni_da_evitare`
- **Buoni predecessori**: `=this.successioni_buone`
- **Da non far seguire a**: `=this.predecessori_da_evitare`

## Diario di campo collegato
```dataview
TABLE meteo AS "Meteo", interventi AS "Interventi"
FROM "agricoltura/40_Diario"
WHERE contains(piante, this.file.link) OR contains(file.outlinks, this.file.link)
SORT file.name DESC
LIMIT 10
```

## 🍽️ Ricette collegate
```dataview
TABLE stagione AS "Stagione", portata AS "Portata"
FROM "agricoltura/50_Ricette"
WHERE tipo = "ricetta" AND contains(ingredienti_orto, this.file.link)
SORT file.name ASC
```

## Note personali
- 

## Riferimenti
- [[_MOC_Piante]]

#pianta #orticola
