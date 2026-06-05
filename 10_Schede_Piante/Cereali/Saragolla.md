---
tipo: scheda_pianta
categoria: cereale
nome_comune: Saragolla
nome_scientifico: Triticum turgidum subsp. turanicum
famiglia: Poaceae
ciclo: annuale
periodo_semina: "Ottobre-Novembre"
periodo_raccolta: "Giugno-Luglio"
calendario:
  - tipo: semina
    da_settimana: 42
    a_settimana: 48
    luna: calante
  - tipo: raccolta
    da_settimana: 24
    a_settimana: 29
    luna: calante
distanza_pianta_cm: 5
distanza_fila_cm: 15
profondita_semina_cm: 4
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.8
fabbisogno_idrico: basso
difficolta: 2
consociazioni_buone:
  - Leguminose (sovescio precedente)
consociazioni_da_evitare:
  - Altri cereali
successioni_buone:
  - Favino
  - Veccia
  - Pisello
predecessori_da_evitare:
  - Frumento
  - Orzo
tags:
  - pianta
  - cereale
  - poaceae
  - grano_antico
---

# 🌾 Saragolla

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Antico frumento del gruppo turanicum (affine al Khorasan, il "Kamut" commerciale), diffuso nell'Appennino centro-meridionale, in Abruzzo, Molise e Puglia. Cariosside **grande, allungata e ambrata**, spiga aristata. Pianta alta e rustica, di origine mediterraneo-orientale, adattata ad ambienti caldi e asciutti. Glutine ben tollerato da molti, sapore dolce e ricco; ottimo per pasta, pane e dolci. Esistono diverse popolazioni locali chiamate "saragolla", da seme conservato di anno in anno.

## Semina e trapianto
- **Semina diretta** autunnale, ottobre-novembre
- Profondità: 3-5 cm
- Dose: ~180-200 kg/ha, semina non fitta (pianta alta)
- Predilige terreni di medio impasto, ben drenati

## Cura
- Esposizione: sole pieno
- Irrigazione: in asciutta; tollera molto bene la siccità di fine ciclo
- Concimazione: azoto contenuto, sfrutta l'azoto residuo di una leguminosa
- Controllo infestanti: la taglia alta soffoca bene le malerbe

## Avversità tipiche
- **Allettamento**: rischio sulle piante alte, contenere azoto e fittezza
- **Ruggini** e **septoria** in primavere umide: rusticità buona ma sorvegliare
- **Fusariosi della spiga**: rotazione e gestione dei residui

## Raccolta e conservazione
- Periodo: `=this.periodo_raccolta`, a maturazione piena
- Granella conservata pulita e secca (umidità ~13%), al riparo dagli insetti dei granai
- Si valorizza in semola per pasta e pane; ottima anche in chicchi decorticati

## Consociazioni e rotazioni
- Coltura pura: conta la **rotazione**
- **Buoni predecessori**: favino, veccia, pisello (azoto)
- **Da evitare**: ristoppio e altri cereali in successione stretta

## Note clima costiero
Frumento mediterraneo per vocazione: ama inverni miti e primavere asciutte e calde, condizioni tipiche della costa centro-italiana. Buona tolleranza alla siccità e discreta alla salsedine. Sulle piante alte il **vento marino** in spigatura è il rischio principale (allettamento): contenere la concimazione e valutare un frangivento.

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
- Grani antichi: [[Senatore_Cappelli]] · [[Timilia]] · [[Russello]]
- [[autunno]] · [[estate]]

#pianta #cereale #grano_antico
