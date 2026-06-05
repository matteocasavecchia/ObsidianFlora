---
tipo: scheda_pianta
categoria: cereale
nome_comune: Farro Monococco
nome_scientifico: Triticum monococcum
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

# 🌾 Farro Monococco

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Il **farro piccolo** (Triticum monococcum), il più antico frumento coltivato dall'uomo, addomesticato oltre 10.000 anni fa. **Diploide**, a un solo chicco per spighetta (da cui "monococco"). Cariosside **vestita** (rivestita dalle glume, va decorticata). Pianta esile e rustica, taglia alta, eccezionale frugalità: cresce su terreni poveri e marginali. Farina dorata, dolce, ricca di carotenoidi e proteine; glutine particolare, poco tenace, spesso meglio tollerato. Da pane a lievito madre, dolci e chicchi decorticati in zuppa.

## Semina e trapianto
- **Semina diretta** autunnale, ottobre-novembre, con la cariosside **vestita**
- Profondità: 2-4 cm
- Dose: più alta in peso per via delle glume (~140-180 kg/ha di cariosside vestita)
- Frugale: ideale per terreni poveri, sassosi, di collina

## Cura
- Esposizione: sole pieno
- Irrigazione: in asciutta, fra i cereali più resistenti alla siccità
- Concimazione: minima, è una specie da ambienti poveri
- Controllo infestanti: rusticità e taglia alta competono bene

## Avversità tipiche
- Molto rustico: poche avversità, tollera bene stress idrico e suoli poveri
- **Allettamento** possibile sulle piante alte in terreni fertili
- Resa bassa e necessità di **decorticatura**: il prezzo della sua antichità

## Raccolta e conservazione
- Periodo: `=this.periodo_raccolta`
- Si raccoglie **vestito**; richiede **decorticatura** (sbramatura) prima dell'uso o della molitura
- Granella vestita conservata secca e pulita (le glume proteggono il chicco)
- Farina dorata a pietra per pane e dolci; chicchi decorticati per zuppe

## Consociazioni e rotazioni
- Coltura pura: conta la **rotazione**
- **Buoni predecessori**: lenticchia, cicerchia, favino
- **Da evitare**: ristoppio, frumento e altri farri in successione stretta

## Note clima costiero
Specie rustica e frugale, tollera bene il caldo e l'asciutto della costa mediterranea e si accontenta di terreni poveri e ben drenati. La cariosside vestita protegge il chicco da umidità e parassiti in campo. Sulle piante alte sorvegliare l'allettamento da **vento marino**. Ottima scelta per appezzamenti marginali dove un frumento esigente non renderebbe.

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
- Grani antichi: [[Farro_Dicocco]] · [[Solina]] · [[Verna]]
- [[autunno]] · [[estate]]

#pianta #cereale #grano_antico #farro
