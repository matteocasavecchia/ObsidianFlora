---
tipo: scheda_razza_cunicola
categoria: coniglio
nome_razza: <% tp.file.title %>
origine: 
attitudine: carne
peso_macellazione_kg: 
eta_macellazione_mesi: 
accrescimento_g_giorno: 
resa_macellazione_pct: 
indice_conversione: 
prolificita: 
eta_primo_parto_mesi: 
peso_femmina_kg: 
peso_maschio_kg: 
rusticita: media
temperamento: 
spazio_min_mq_capo: 
adatta_clima_costiero: 
difficolta: 2
tags:
  - cunicoltura
  - razza
---

# 🐰 <% tp.file.title %>

> Specie: `=this.categoria` · Attitudine: `=this.attitudine` · Macellazione: `=this.peso_macellazione_kg` kg a `=this.eta_macellazione_mesi` mesi · Difficoltà: `=this.difficolta`/5

## Caratteristiche
_(origine, morfologia, mantello, taglia; cosa la distingue e perché adatta al clima mediterraneo costiero)_

## Attitudine e produzione di carne
- Peso alla macellazione: `=this.peso_macellazione_kg` kg
- Età alla macellazione: `=this.eta_macellazione_mesi` mesi
- Accrescimento medio: `=this.accrescimento_g_giorno` g/giorno
- Resa al macello: `=this.resa_macellazione_pct`%
- Indice di conversione: `=this.indice_conversione`

## Riproduzione
- Prolificità: `=this.prolificita` nati per parto
- Età al primo parto: `=this.eta_primo_parto_mesi` mesi
- Stagionalità / parti l'anno: _(cadenza dei parti, gestione fattrici e nidi)_

## Gestione e spazio
- Peso adulto: femmina `=this.peso_femmina_kg` kg · maschio `=this.peso_maschio_kg` kg
- Spazio minimo consigliato: `=this.spazio_min_mq_capo` m²/capo
- Ricovero / gabbie: _(gabbie o recinto a terra, drenaggio, protezione dai predatori)_

## Alimentazione
_(fieno a volontà, foraggio verde, mangime pellettato in ingrasso; acqua sempre disponibile; evitare bruschi cambi di dieta)_

## Rusticità e clima costiero
- Rusticità: `=this.rusticita`
- Caldo / umidità estiva: _(rischio colpi di calore, ombra, ventilazione, acqua)_
- Salsedine e vento marino: _(riparo, drenaggio della lettiera)_

## Salute e avversità tipiche
_(coccidiosi, malattia emorragica virale, mixomatosi; profilassi vaccinale e igiene)_

## Carattere e convivenza
- Temperamento: `=this.temperamento`
- Convivenza: _(separazione dei maschi, box individuali per le fattrici)_

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
- [[_MOC_Cunicoltura]]

#cunicoltura #razza
