---
tipo: scheda_pianta
categoria: orticola
nome_comune: Cece
nome_scientifico: Cicer arietinum
famiglia: Fabaceae
ciclo: annuale
periodo_semina: "Marzo-Maggio"
periodo_raccolta: "Luglio-Settembre"
distanza_pianta_cm: 10
distanza_fila_cm: 40
profondita_semina_cm: 4
esposizione: sole pieno
ph_min: 6.0
ph_max: 8.0
fabbisogno_idrico: basso
difficolta: 2
consociazioni_buone:
  - Carota
  - Coriandolo
  - Sedano
  - Cavoli
consociazioni_da_evitare:
  - Cipolla
  - Aglio
  - Porro
successioni_buone:
  - Cereali
  - Solanacee
  - Cavoli
predecessori_da_evitare:
  - Fabacee
tags:
  - pianta
  - orticola
  - fabacee
  - legumi
---

# 🟡 Cece

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Legume mediterraneo per eccellenza, una delle piante più tolleranti alla siccità dell'orto. Cresce 30-60 cm, baccelli piccoli con 1-2 semi. Varietà: ceci a chicco grosso (Spagnolo, Cicerale), chicco piccolo (Pascià), ceci neri (Murgia pugliese), nero di Apricena. Coltura ideale per chi vuole legumi senza irrigazione estiva.

## Semina e trapianto
- Solo semina diretta, su terreno asciutto e ben drenato
- Marzo-aprile sulla costa, evitare terreni freddi e umidi
- Profondità: 4-5 cm
- Distanze: 10-15 cm sulla fila, 40 cm tra le file
- Mai letame, solo compost maturo

## Cura
- Esposizione: sole pieno
- Irrigazione: **praticamente assente**. Il cece teme l'eccesso d'acqua più della siccità. Vive di rugiade e poche piogge primaverili
- Pacciamatura solo in caso di estati torride per ridurre evaporazione
- Concimazione: compost in preparazione, niente azoto
- Sarchiature leggere

## Avversità tipiche
- **Tonchio del cece** (Callosobruchus chinensis): larve nei semi durante conservazione. Congelatore 48 ore appena raccolti i semi secchi
- **Rabbia del cece** (Ascochyta rabiei): macchie scure su foglie e baccelli. Rotazione lunga e varietà resistenti
- **Marciumi**: solo in terreno troppo umido, drenaggio fondamentale
- **Nottue**: rimedi classici

## Raccolta e conservazione
- **Ceci freschi** (rari, alcuni mangiano le piante intere giovani crude): raramente coltivati a questo scopo
- **Ceci secchi** (uso comune): quando le piante sono completamente secche in campo, baccelli marroni. Si tagliano intere le piante, si lasciano in luogo asciutto qualche giorno, poi si sgranano (battitura su telo)
- Conservazione: barattoli ermetici, 2+ anni dopo congelamento di 48 ore per sicurezza tonchio

## Consociazioni e rotazioni
- **Compagne**: carota, coriandolo, sedano, cavoli
- **Da evitare**: Amaryllidaceae (cipolla, aglio, porro)
- **Rotazione**: 4-5 anni per fabacee. Buon predecessore per cereali, cavoli, solanacee

## Note clima costiero
Coltura **straordinariamente adatta** alla costa centro-italiana: estati calde e secche sono il suo elemento. Tollera la salsedine. Stanco di irrigare in agosto? Il cece va benissimo. L'unica accortezza è evitare terreni che si compattano dopo piogge primaverili: drenaggio buono o terreno leggero. In zone con primavere molto piovose, conviene una semina tardiva (fine aprile-maggio).

## Diario di campo collegato
```dataview
TABLE meteo AS "Meteo", interventi AS "Interventi"
FROM "agricoltura/40_Diario"
WHERE contains(piante, this.file.link) OR contains(file.outlinks, this.file.link)
SORT file.name DESC
LIMIT 10
```

## Note personali
- 

## Riferimenti
- [[_MOC_Piante]]
- [[primavera]] · [[estate]]

#pianta #orticola #fabacee #legumi
