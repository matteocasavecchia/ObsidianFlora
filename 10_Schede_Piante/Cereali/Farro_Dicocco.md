---
tipo: scheda_pianta
categoria: cereale
nome_comune: Farro Dicocco
nome_scientifico: Triticum dicoccum
famiglia: Poaceae
ciclo: annuale
periodo_semina: "Ottobre-Novembre"
periodo_raccolta: "Luglio"
calendario:
  - tipo: semina
    da_settimana: 42
    a_settimana: 47
    luna: calante
  - tipo: raccolta
    da_settimana: 27
    a_settimana: 32
    luna: calante
distanza_pianta_cm: 5
distanza_fila_cm: 15
profondita_semina_cm: 3
esposizione: sole pieno
ph_min: 5.5
ph_max: 7.5
fabbisogno_idrico: basso
difficolta: 2
consociazioni_buone:
  - Leguminose (sovescio precedente)
consociazioni_da_evitare:
  - Altri cereali
successioni_buone:
  - Lenticchia
  - Cicerchia
  - Favino
predecessori_da_evitare:
  - Frumento
  - Farro
tags:
  - pianta
  - cereale
  - poaceae
  - grano_antico
  - farro
---

# 🌾 Farro Dicocco

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Il **farro medio** (Triticum dicoccum), il più coltivato dei tre farri e il "farro" per antonomasia delle zuppe italiane (è quello del Farro della Garfagnana IGP e di Monteleone di Spoleto). **Tetraploide**, cariosside **vestita** da decorticare, due chicchi per spighetta. Pianta rustica e frugale, taglia alta, ottima su terreni poveri e in collina. Glutine modesto, chicco che resta sodo in cottura: perfetto per zuppe, insalate di farro e minestre; macinato dà farina per pane e pasta.

## Semina e trapianto
- **Semina diretta** autunnale, ottobre-novembre, cariosside **vestita**
- Profondità: 2-4 cm
- Dose: ~140-180 kg/ha di cariosside vestita
- Frugale e rustico: adatto a terreni poveri e collinari

## Cura
- Esposizione: sole pieno
- Irrigazione: in asciutta, buona resistenza alla siccità
- Concimazione: minima, specie da ambienti poveri
- Controllo infestanti: rusticità e taglia alta competono bene

## Avversità tipiche
- Molto rustico, poche avversità
- **Allettamento** possibile sulle piante alte in terreni fertili
- Richiede **decorticatura** dopo la raccolta: passaggio in più rispetto ai frumenti nudi

## Raccolta e conservazione
- Periodo: `=this.periodo_raccolta`
- Si raccoglie **vestito**; va **decorticato** (sbramato) prima dell'uso
- Granella vestita conservata secca e pulita
- Chicco decorticato per zuppe e insalate; farina a pietra per pane e pasta

## Consociazioni e rotazioni
- Coltura pura: conta la **rotazione**
- **Buoni predecessori**: lenticchia, cicerchia, favino
- **Da evitare**: ristoppio, frumento e altri farri in successione stretta

## Note clima costiero
Cereale rustico e adattabile, regge bene il caldo asciutto mediterraneo e i terreni poveri e ben drenati della fascia costiera collinare. La cariosside vestita protegge il chicco in campo. Sulle piante alte attenzione all'allettamento da **vento marino**. È il farro più versatile in cucina: ottima coltura di nicchia per la piccola azienda costiera, anche in vendita diretta.

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
- Grani antichi: [[Farro_Monococco]] · [[Senatore_Cappelli]] · [[Solina]]
- [[autunno]] · [[estate]]

#pianta #cereale #grano_antico #farro
