---
tipo: scheda_razza
categoria: gallina
nome_razza: <% tp.file.title %>
origine: 
attitudine: ovaiola
uova_anno: 
colore_uovo: 
peso_uovo_g: 
peso_gallina_kg: 
peso_gallo_kg: 
inizio_deposizione_mesi: 
rusticita: media
tendenza_cova: 
temperamento: 
spazio_min_mq_capo: 
adatta_clima_costiero: 
difficolta: 2
tags:
  - pollicoltura
  - razza
---

# 🐔 <% tp.file.title %>

> Attitudine: `=this.attitudine` · Uova/anno: `=this.uova_anno` · Rusticità: `=this.rusticita` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
_(origine, morfologia, livrea, taglia, varietà; cosa la distingue)_

## Attitudine e produzione uova
- Uova all'anno: `=this.uova_anno`
- Colore guscio: `=this.colore_uovo`
- Peso medio uovo: `=this.peso_uovo_g` g
- Inizio deposizione: `=this.inizio_deposizione_mesi` mesi
- Continuità in inverno / dopo la muta: _(cala molto, regge, ecc.)_

## Gestione e spazio
- Peso gallina: `=this.peso_gallina_kg` kg · gallo: `=this.peso_gallo_kg` kg
- Spazio minimo consigliato: `=this.spazio_min_mq_capo` m²/capo
- Recinto / razzolamento: _(ama spaziare, tollera spazi ridotti, capacità di volo...)_
- Tendenza alla cova: `=this.tendenza_cova`

## Alimentazione
_(note specifiche di razza: tendenza all'ingrasso, fabbisogno proteico in deposizione, integrazioni)_

## Rusticità e clima costiero
- Rusticità: `=this.rusticita`
- Caldo / umidità estiva: _(tolleranza, accorgimenti ombra e acqua)_
- Salsedine e vento marino: _(riparo, lettiera, ventilazione pollaio)_

## Salute e avversità tipiche
- Parassiti: _(pidocchi pollini, acari rossi, coccidiosi...)_
- Predisposizioni di razza: _(se note)_
- Profilassi consigliata: _(vedi [[Salute_Profilassi]])_

## Carattere e convivenza
- Temperamento: `=this.temperamento`
- Convivenza nel gruppo / con altre razze: _(docile, dominante, rumorosa...)_

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
- [[_MOC_Pollicoltura]]

#pollicoltura #razza
