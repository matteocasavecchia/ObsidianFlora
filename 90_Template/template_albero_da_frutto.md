---
tipo: scheda_pianta
categoria: albero_da_frutto
nome_comune: <% tp.file.title %>
nome_scientifico: 
famiglia: 
periodo_raccolta: 
periodo_potatura: 
forma_allevamento: 
portainnesto_consigliato: 
esposizione: sole pieno
resistenza_salsedine: media
resistenza_freddo: 
entrata_in_produzione_anni: 
autofertile: true
impollinatori_richiesti: 
sesto_impianto_m: 
tags:
  - pianta
  - albero_da_frutto
---

# 🌳 <% tp.file.title %>

> Famiglia: `=this.famiglia` · Raccolta: `=this.periodo_raccolta` · Potatura: `=this.periodo_potatura`

## Caratteristiche
_(descrizione generale, varietà consigliate per il clima mediterraneo costiero, portamento)_

## Impianto
- Esposizione: `=this.esposizione`
- Sesto di impianto: `=this.sesto_impianto_m` m
- Portainnesto: `=this.portainnesto_consigliato`
- Forma di allevamento: `=this.forma_allevamento`
- Periodo migliore: _(novembre-marzo a radice nuda, autunno-primavera in vaso)_
- Buca, drenaggio, ammendanti: _(specificare)_

## Cura annuale
- Concimazione: _(autunnale di fondo + copertura primaverile)_
- Irrigazione: _(soprattutto nei primi anni; estate calda-secca)_
- Lavorazioni: _(cotica erbosa, pacciamatura, sarchiatura)_

## Potatura
- Periodo: `=this.periodo_potatura`
- Tipo: _(formazione, produzione, riforma)_
- Tagli chiave: _(cosa togliere, cosa lasciare)_

## Impollinazione e produzione
- Autofertile: `=this.autofertile`
- Impollinatori richiesti: `=this.impollinatori_richiesti`
- Entrata in produzione: `=this.entrata_in_produzione_anni` anni
- Produzione media a maturità: _(kg per pianta)_

## Avversità tipiche
- Parassiti: _(mosca, cocciniglia, oziorrinco, rodilegno...)_
- Malattie: _(occhio di pavone, gommosi, marciumi radicali, fumaggini...)_
- Difesa biologica: _(rame, zolfo, trappole feromoni, predatori)_

## Resistenza al contesto costiero
- Salsedine: `=this.resistenza_salsedine`
- Freddo: `=this.resistenza_freddo`
- Vento: _(richiede frangivento?)_

## Raccolta e conservazione
- Indici di maturazione: _(colore, consistenza, distacco)_
- Conservazione: _(fresca, frigo, sciroppi, marmellate, essiccazione...)_

## Diario di campo collegato
```dataview
TABLE meteo AS "Meteo", interventi AS "Interventi"
FROM "agricoltura/40_Diario"
WHERE contains(piante, this.file.link) OR contains(file.outlinks, this.file.link)
SORT file.name DESC
LIMIT 10
```

## Riferimenti
- [[_MOC_Piante]]

#pianta #albero_da_frutto
