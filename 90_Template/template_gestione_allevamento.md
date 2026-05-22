---
tipo: gestione_allevamento
titolo: <% tp.file.title %>
area: 
difficolta: 2
frequenza: 
stagione: 
materiali: 
strumenti: 
tags:
  - allevamento_latte
  - gestione
---

# 🛠️ <% tp.file.title %>

> Area: `=this.area` · Difficoltà: `=this.difficolta`/5 · Frequenza: `=this.frequenza`

## A cosa serve
_(scopo, perché è importante per il benessere, la produzione e la qualità del latte)_

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
_(caldo e umidità estiva, salsedine, vento marino, ventilazione e lettiera, gestione del pascolo...)_

## Errori comuni
- 
- 

## Segnali da tenere d'occhio
_(cosa osservare su animali, latte, ambiente)_

## Diario di campo collegato
```dataview
TABLE file.name AS "Nota", meteo AS "Meteo"
FROM "agricoltura/40_Diario"
WHERE contains(file.outlinks, this.file.link)
SORT file.name DESC
LIMIT 10
```

## Riferimenti
- [[_MOC_Allevamento_Latte]]

#allevamento_latte #gestione
