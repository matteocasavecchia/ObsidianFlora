---
tipo: scheda_pianta
categoria: cereale
nome_comune: Gentil Rosso
nome_scientifico: Triticum aestivum
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
    a_settimana: 31
    luna: calante
distanza_pianta_cm: 5
distanza_fila_cm: 15
profondita_semina_cm: 3
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: basso
difficolta: 2
consociazioni_buone:
  - Leguminose (sovescio precedente)
consociazioni_da_evitare:
  - Altri cereali
successioni_buone:
  - Favino
  - Trifoglio
predecessori_da_evitare:
  - Frumento
  - Orzo
tags:
  - pianta
  - cereale
  - poaceae
  - grano_antico
---

# 🌾 Gentil Rosso

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Frumento **tenero** italiano molto antico, diffusissimo in tutta la penisola prima della "rivoluzione verde". Esistono molte popolazioni (Gentil rosso, Gentil bianco, Gentil rosso mutico/aristato). Pianta **alta** (fino a 150-170 cm), spiga rossiccia, rustica e poco esigente. Glutine debole, ottimo per pane a lievito madre, schiacciate e dolci. Pianta da popolazione, con variabilità interna che ne sostiene la resilienza.

## Semina e trapianto
- **Semina diretta** autunnale, ottobre-novembre
- Profondità: 2-4 cm
- Dose: ~180-200 kg/ha, semina non fitta (taglia alta)
- Si adatta a terreni collinari e di medio impasto

## Cura
- Esposizione: sole pieno
- Irrigazione: in asciutta, buona rusticità
- Concimazione: azoto basso, valorizza l'azoto di una leguminosa
- Controllo infestanti: la taglia alta compete bene con le malerbe

## Avversità tipiche
- **Allettamento**: rischio sulle piante alte; azoto e fittezza contenuti
- **Ruggini**, **oidio** e **septoria** in primavere umide
- **Fusariosi**: rotazione e gestione dei residui

## Raccolta e conservazione
- Periodo: `=this.periodo_raccolta`
- Granella tenera conservata secca e pulita
- Farina a pietra per pane, schiacciate e dolci da forno

## Consociazioni e rotazioni
- Coltura pura: conta la **rotazione**
- **Buoni predecessori**: favino, trifoglio
- **Da evitare**: ristoppio e altri cereali

## Note clima costiero
Frumento tenero da collina, in costa va seminato per tempo su terreni ben drenati: come la Verna teme caldo-umido e ristagni più dei duri. Buona la rusticità complessiva; sulle piante alte sorvegliare l'allettamento da **vento marino**. Sulla fascia calda e secca rende meglio in posizioni fresche e ventilate.

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
- Grani antichi: [[Verna]] · [[Solina]] · [[Maiorca]]
- [[autunno]] · [[estate]]

#pianta #cereale #grano_antico
