---
tipo: scheda_razza_equina
categoria: cavallo
nome_razza: <% tp.file.title %>
origine: 
attitudine: tiro
altezza_garrese_cm: 
peso_kg: 
mantello: 
rusticita: media
adatta_pascolo: 
temperamento: 
longevita_anni: 
spazio_min_mq_capo: 
adatta_clima_costiero: 
difficolta: 3
tags:
  - allevamento_latte
  - razza
  - equino
---

# 🐴 <% tp.file.title %>

> Specie: `=this.categoria` · Attitudine: `=this.attitudine` · Garrese: `=this.altezza_garrese_cm` cm · Rusticità: `=this.rusticita` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
_(origine, morfologia, taglia, mantello; cosa la distingue e perché adatta al clima mediterraneo costiero)_

## Attitudine e impiego
- Attitudine principale: `=this.attitudine`
- Impieghi nella piccola azienda: _(lavoro, sella, attacchi, esbosco, agriturismo...)_
- Andatura e doti di movimento: _(passo, trotto, resistenza)_

## Riproduzione
- Maturità per la monta: _(età)_
- Gestazione: ~11 mesi, un solo puledro per parto
- Stagionalità: _(poliestrale stagionale; gestione di calori e monte)_
- Accrescimento e svezzamento del puledro: _(note)_

## Gestione e spazio
- Garrese: `=this.altezza_garrese_cm` cm · peso: `=this.peso_kg` kg
- Spazio minimo consigliato: `=this.spazio_min_mq_capo` m²/capo (paddock/pascolo ampio + ricovero)
- Attitudine al pascolo: `=this.adatta_pascolo`
- Ricovero e recinzioni: _(robustezza, ombra, abbeveratoi; vedi [[Ricovero_Recinzioni]])_
- Zoccoli: pareggio/ferratura regolare ogni 6-8 settimane

## Alimentazione
_(fieno e pascolo come base, concentrati in proporzione al lavoro; acqua e sali sempre disponibili; attenzione a coliche e laminite; vedi [[Alimentazione_Pascolo]])_

## Rusticità e clima costiero
- Rusticità: `=this.rusticita`
- Caldo / umidità estiva: _(tolleranza, ombra, acqua, lavoro nelle ore fresche)_
- Salsedine e vento marino: _(adattabilità, cura di zoccoli e ricovero asciutto)_

## Salute e avversità tipiche
_(zoccoli, coliche, parassiti, vaccinazioni di base; laminite e dermatiti del fettone nei soggetti pesanti)_

## Carattere e convivenza
- Temperamento: `=this.temperamento`
- Convivenza: _(socialità, gerarchie, gestibilità)_

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
- [[_MOC_Tecniche]]

#allevamento_latte #razza #equino
