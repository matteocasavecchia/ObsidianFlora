---
tipo: scheda_pianta
categoria: orticola
nome_comune: Sedano
nome_scientifico: Apium graveolens
famiglia: Apiaceae
ciclo: biennale (coltivato come annuale)
periodo_semina: "Febbraio-Aprile (semenzaio protetto); trapianto Maggio-Giugno"
periodo_raccolta: "Settembre-Dicembre"
distanza_pianta_cm: 30
distanza_fila_cm: 40
profondita_semina_cm: 0.5
esposizione: sole pieno (gradita mezz'ombra nelle ore calde estive)
ph_min: 6.0
ph_max: 7.0
fabbisogno_idrico: alto (costante, mai asciutto)
difficolta: 3
consociazioni_buone:
  - Cavolo
  - Pomodoro
  - Fagiolo
  - Porro
  - Cetriolo
consociazioni_da_evitare:
  - Mais
  - Prezzemolo
  - Carota
  - Pastinaca
successioni_buone:
  - Legumi
  - Cucurbitacee
  - Cavoli
predecessori_da_evitare:
  - Apiaceae (carota, finocchio, prezzemolo)
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Subirrigazione]]"
tags:
  - pianta
  - orticola
  - apiaceae
---

# 🥬 Sedano

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Ortaggio aromatico esigente in acqua e fertilità, della stessa famiglia di carota e finocchio. Due tipi principali: il **sedano da coste** (Apium graveolens var. dulce), di cui si mangiano i piccioli carnosi, e il **sedano rapa** (var. rapaceum), di cui si consuma l'ingrossamento ipogeo. Esiste anche il **sedano da taglio** (o da brodo), rustico e foglioso, molto più facile, ottimo per insaporire. Per la costa centro-italiana il sedano da taglio è il più semplice; il sedano da coste richiede più cure e imbianchimento.

## Semina e trapianto
- Periodo: `=this.periodo_semina`
- Profondità semina: `=this.profondita_semina_cm` cm, seme molto piccolo, appena coperto
- Distanze: `=this.distanza_pianta_cm` cm sulla fila, `=this.distanza_fila_cm` cm tra le file
- Modalità: semenzaio protetto a 18-22 °C (germinazione lenta, 2-3 settimane, gradisce luce). Trapianto quando le piantine hanno 4-5 foglie e le minime stanno sopra i 10 °C, per evitare prefioritura (il freddo dopo trapianto induce la salita a seme)

## Cura
- Esposizione: `=this.esposizione`
- Irrigazione: il punto critico. Vuole terreno **sempre umido**; lo stress idrico rende le coste filacciose, amare e cave. Goccia o subirrigazione costante, pacciamatura per trattenere umidità
- Concimazione: terreno ricco di sostanza organica, letame maturo o compost abbondante alla preparazione; gradisce apporti azotati equilibrati
- Imbianchimento (solo sedano da coste): 2-3 settimane prima della raccolta si legano i piccioli e si rincalzano con terra o si avvolgono con carta/cartone per renderli teneri e chiari
- Sarchiature regolari, il sedano teme la competizione delle infestanti

## Avversità tipiche
- **Septoriosi** (Septoria apiicola): macchie brune con puntini neri sulle foglie, la malattia più comune. Sementi sane, rotazione, rame ai primi segnali
- **Ruggine del sedano** e **cercosporiosi**: macchie fogliari, gestione come sopra
- **Mosca del sedano** (Philophylla heraclei): mine fogliari. Reti anti-insetto, eliminazione foglie colpite
- **Afidi** e **lumache** (ghiotte delle giovani piante): macerati, sapone molle, barriere e trappole
- **Marciume del colletto** in terreni asfittici: migliorare drenaggio
- **Carenza di boro**: cuore cavo e spaccature, frequente in terreni calcarei costieri; correggere con sostanza organica
- Note clima costiero: l'umidità marina favorisce le malattie fungine fogliari, arieggiare l'impianto; il caldo intenso accelera la salita a seme, utile la mezz'ombra estiva

## Raccolta e conservazione
- Periodo: `=this.periodo_raccolta`
- Indici: coste ben sviluppate e croccanti per il da coste; palla soda e pesante per il sedano rapa. Il da taglio si raccoglie a foglie man mano che servono
- Conservazione: in frigo 1-2 settimane avvolto in panno umido. Le coste si congelano (sbollentate) per minestre; le foglie si essiccano o si congelano come aroma. Il sedano rapa si conserva a lungo in cantina fresca e asciutta

## Consociazioni e rotazioni
- **Compagne buone**: `=this.consociazioni_buone`
- **Da evitare**: `=this.consociazioni_da_evitare`
- **Buoni predecessori**: `=this.successioni_buone`
- **Da non far seguire a**: `=this.predecessori_da_evitare`
- **Rotazione**: almeno 3 anni prima di rimettere Apiaceae sulla stessa parcella

## Note clima costiero
Pianta adatta più all'autunno mite costiero che alla piena estate: la combinazione di caldo e siccità la mette in difficoltà e ne favorisce la prefioritura. Conviene puntare al ciclo che matura in autunno, con trapianti non troppo precoci e irrigazione costante per tutta l'estate. L'umidità notturna marina richiede attenzione alle malattie fogliari: sesti arieggiati e niente bagnature serali.

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Subirrigazione]]
- [[autunno]] · [[inverno]]

#pianta #orticola #apiaceae
