---
tipo: scheda_razza_lattifera
categoria: capra
nome_razza: <% tp.file.title %>
origine: 
attitudine: latte
latte_litri_lattazione: 
durata_lattazione_giorni: 
grasso_pct: 
proteine_pct: 
peso_femmina_kg: 
peso_maschio_kg: 
prolificita: 
eta_primo_parto_mesi: 
rusticita: media
adatta_pascolo: 
temperamento: 
spazio_min_mq_capo: 
adatta_clima_costiero: 
difficolta: 2
tags:
  - allevamento_latte
  - razza
---

# 🐐 <% tp.file.title %>

> Specie: `=this.categoria` · Latte/lattazione: `=this.latte_litri_lattazione` L · Rusticità: `=this.rusticita` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
_(origine, morfologia, livrea, taglia, mantello; cosa la distingue e perché è adatta al clima mediterraneo costiero)_

## Attitudine e produzione di latte
- Latte per lattazione: `=this.latte_litri_lattazione` L
- Durata della lattazione: `=this.durata_lattazione_giorni` giorni
- Grasso: `=this.grasso_pct`% · Proteine: `=this.proteine_pct`%
- Attitudine casearia: _(resa al formaggio, profilo del latte)_

## Riproduzione
- Età al primo parto: `=this.eta_primo_parto_mesi` mesi
- Prolificità: `=this.prolificita`
- Stagionalità del calore / monte: _(stagionale o destagionalizzata)_

## Gestione e spazio
- Peso femmina: `=this.peso_femmina_kg` kg · maschio: `=this.peso_maschio_kg` kg
- Spazio minimo consigliato: `=this.spazio_min_mq_capo` m²/capo
- Attitudine al pascolo: `=this.adatta_pascolo`
- Ricovero e recinzioni: _(vedi [[Ricovero_Recinzioni]])_

## Alimentazione
_(pascolo, fieno, concentrati in lattazione; vedi [[Alimentazione_Pascolo]])_

## Rusticità e clima costiero
- Rusticità: `=this.rusticita`
- Caldo / umidità estiva: _(tolleranza, ombra, acqua)_
- Salsedine e vento marino: _(adattabilità, riparo)_

## Salute e avversità tipiche
_(mastiti, parassiti, zoppie; vedi [[Salute_Profilassi_Latte]])_

## Carattere e convivenza
- Temperamento: `=this.temperamento`
- Convivenza nel gruppo: _(gerarchia, gestibilità)_

## Note personali
- 

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
- [[_MOC_Caseificazione]]

#allevamento_latte #razza
