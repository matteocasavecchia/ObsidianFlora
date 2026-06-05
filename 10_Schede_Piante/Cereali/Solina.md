---
tipo: scheda_pianta
categoria: cereale
nome_comune: Solina
nome_scientifico: Triticum aestivum
famiglia: Poaceae
ciclo: annuale
periodo_semina: "Settembre-Novembre"
periodo_raccolta: "Luglio-Agosto"
calendario:
  - tipo: semina
    da_settimana: 38
    a_settimana: 47
    luna: calante
  - tipo: raccolta
    da_settimana: 28
    a_settimana: 33
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
  - Orzo
tags:
  - pianta
  - cereale
  - poaceae
  - grano_antico
---

# 🌾 Solina

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Frumento **tenero** abruzzese da montagna, coltivato da secoli sull'Appennino fino a quote elevate. Pianta alta e rustica, spiga mutica (senza ariste), straordinariamente **resistente al freddo e adatta ai terreni poveri** di altura. Glutine debole, farina dal sapore caratteristico, base del pane tradizionale abruzzese e di paste fresche locali. Presidio della biodiversità cerealicola appenninica, da seme contadino.

## Semina e trapianto
- **Semina diretta** autunnale, da settembre in montagna fino a novembre in collina
- Profondità: 2-4 cm
- Dose: ~180-200 kg/ha
- Eccellente per ambienti freddi, d'altura e marginali

## Cura
- Esposizione: sole pieno
- Irrigazione: in asciutta, grande rusticità
- Concimazione: minima, è un grano da terreni poveri; eccesso d'azoto dannoso
- Controllo infestanti: rusticità e taglia alta competono bene

## Avversità tipiche
- **Allettamento** sulle piante alte in ambienti fertili o ventosi
- **Ruggini** e malattie fungine in annate umide
- Resa contenuta, tipica dei grani rustici di montagna

## Raccolta e conservazione
- Periodo: `=this.periodo_raccolta`, tardivo (ambienti freschi d'altura)
- Granella tenera conservata secca e pulita
- Farina a pietra per pane e paste fresche tradizionali

## Consociazioni e rotazioni
- Coltura pura: conta la **rotazione**
- **Buoni predecessori**: lenticchia, cicerchia, favino (legumi di montagna)
- **Da evitare**: ristoppio e altri cereali

## Note clima costiero
È un grano **da freddo e da altura**: il suo ambiente ideale è la montagna, non la costa calda. In pianura litoranea soffre il caldo precoce, che ne anticipa e accorcia il ciclo riducendo la resa, e i ristagni. Annotata qui per completezza della collezione e per eventuali appezzamenti collinari freschi e interni; sulla fascia costiera calda i duri (Senatore Cappelli, Russello, Timilia) restano più vocati.

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
- Grani antichi: [[Verna]] · [[Gentil_Rosso]] · [[Farro_Monococco]]
- [[autunno]] · [[estate]]

#pianta #cereale #grano_antico
