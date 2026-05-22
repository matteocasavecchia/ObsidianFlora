---
tipo: gestione_pollaio
titolo: <% tp.file.title %>
area: 
difficolta: 2
frequenza: 
stagione: 
materiali: 
strumenti: 
tags:
  - pollicoltura
  - gestione
---

# 🛠️ <% tp.file.title %>

> Area: `=this.area` · Difficoltà: `=this.difficolta`/5 · Frequenza: `=this.frequenza`

## A cosa serve
_(scopo, perché è importante per il benessere e la produzione)_

## Quando farlo
- Stagione / periodo: `=this.stagione`
- Frequenza: `=this.frequenza`

## Materiali e strumenti
- Materiali: `=this.materiali`
- Strumenti: `=this.strumenti`

## Procedimento
1. _Passo 1_
2. _Passo 2_
3. _Passo 3_

## Accorgimenti per il clima costiero
_(caldo e umidità estiva, salsedine, vento marino, ventilazione e lettiera...)_

## Errori comuni
- 
- 

## Segnali da tenere d'occhio
_(comportamento, deposizione, stato di penne e cresta, lettiera...)_

## Diario di campo collegato
```dataview
TABLE file.name AS "Nota", meteo AS "Meteo"
FROM "agricoltura/40_Diario"
WHERE contains(file.outlinks, this.file.link)
SORT file.name DESC
LIMIT 10
```

## Riferimenti
- [[_MOC_Pollicoltura]]

#pollicoltura #gestione
