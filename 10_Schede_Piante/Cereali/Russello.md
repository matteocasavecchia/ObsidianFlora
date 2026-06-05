---
tipo: scheda_pianta
categoria: cereale
nome_comune: Russello
nome_scientifico: Triticum turgidum subsp. durum
famiglia: Poaceae
ciclo: annuale
periodo_semina: "Ottobre-Dicembre"
periodo_raccolta: "Giugno-Luglio"
calendario:
  - tipo: semina
    da_settimana: 42
    a_settimana: 50
    luna: calante
  - tipo: raccolta
    da_settimana: 24
    a_settimana: 28
    luna: calante
distanza_pianta_cm: 5
distanza_fila_cm: 15
profondita_semina_cm: 4
esposizione: sole pieno
ph_min: 6.0
ph_max: 8.0
fabbisogno_idrico: basso
difficolta: 2
consociazioni_buone:
  - Leguminose (sovescio precedente)
consociazioni_da_evitare:
  - Altri cereali
successioni_buone:
  - Favino
  - Veccia
predecessori_da_evitare:
  - Frumento
  - Orzo
tags:
  - pianta
  - cereale
  - poaceae
  - grano_antico
---

# 🌾 Russello

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Frumento duro siciliano fra i più antichi e rappresentativi, detto anche **Ruscia** o Russia. Pianta **alta** (fino a 180 cm), spiga aristata di colore dorato-rossiccio (da cui il nome), cariosside ambrata. Buona resa in semola e ottima qualità panificatoria e pastaria; era uno dei grani principe della Sicilia interna. Rustico e adatto al biologico, sopporta bene il caldo e l'asciutto.

## Semina e trapianto
- **Semina diretta** autunnale, ottobre-dicembre
- Profondità: 3-5 cm
- Dose: ~180 kg/ha, semina rada per la taglia alta
- Buona adattabilità ai terreni argillosi e collinari

## Cura
- Esposizione: sole pieno
- Irrigazione: in asciutta; tollera bene la siccità
- Concimazione: azoto moderato per non aggravare l'allettamento
- Controllo infestanti: la taglia alta è un'arma naturale contro le malerbe

## Avversità tipiche
- **Allettamento**: il limite delle taglie alte; contenere azoto e fittezza
- **Ruggini** e **septoria** in primavere piovose
- **Fusariosi**: rotazione e residui ben gestiti

## Raccolta e conservazione
- Periodo: `=this.periodo_raccolta`, a piena maturazione
- Granella ambrata conservata secca e pulita
- Semola di pregio per pane e pasta tradizionali siciliani

## Consociazioni e rotazioni
- Coltura pura: conta la **rotazione**
- **Buoni predecessori**: favino, veccia
- **Da evitare**: ristoppio e altri cereali

## Note clima costiero
Grano duro di vocazione meridionale e mediterranea: si trova a suo agio con inverni miti, primavere asciutte e estati calde, come sulla costa centro-italiana. Tollera bene siccità e suoli salini. La taglia alta lo espone al **vento marino** in spigatura: gestione attenta dell'azoto e, dove serve, frangivento.

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
- Grani antichi: [[Timilia]] · [[Maiorca]] · [[Saragolla]]
- [[autunno]] · [[estate]]

#pianta #cereale #grano_antico
