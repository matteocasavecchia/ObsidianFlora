---
tipo: tecnica
titolo: <% tp.file.title %>
area: 
difficolta: 2
tempo_richiesto: 
stagione: 
materiali: 
strumenti: 
tags:
  - tecnica
---

# 🛠️ <% tp.file.title %>

> Area: `=this.area` · Difficoltà: `=this.difficolta`/5 · Tempo: `=this.tempo_richiesto`

## A cosa serve
_(scopo, vantaggi, quando ha senso applicarla)_

## Quando farla
- Stagione: `=this.stagione`
- Frequenza: _(una tantum, mensile, annuale...)_

## Materiali e strumenti
- Materiali: `=this.materiali`
- Strumenti: `=this.strumenti`

## Procedimento
1. _Passo 1_
2. _Passo 2_
3. _Passo 3_

## Accorgimenti per il clima costiero
_(salsedine, vento marino, umidità, estate secca...)_

## Errori comuni
- 
- 

## Piante / situazioni in cui si applica
- 

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

#tecnica
