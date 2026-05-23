---
tipo: scheda_pianta
categoria: orticola
nome_comune: Indivia (Scarola, Riccia)
nome_scientifico: Cichorium endivia
famiglia: Asteraceae
ciclo: annuale
periodo_semina: "Giugno-Settembre"
periodo_raccolta: "Settembre-Marzo"
distanza_pianta_cm: 30
distanza_fila_cm: 40
profondita_semina_cm: 0.5
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: medio-alto
difficolta: 2
consociazioni_buone:
  - Finocchio (curiosa eccezione)
  - Cipolla
  - Carota
consociazioni_da_evitare:
  - Lattuga
  - Radicchio (stessa famiglia)
successioni_buone:
  - Legumi
predecessori_da_evitare:
  - Asteracee
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - asteracee
  - foglia
---

# 🥗 Indivia

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Due tipologie principali, stesso genere botanico: **scarola** (Cichorium endivia var. latifolia, foglie larghe e tese) e **indivia riccia** (var. crispum, foglie frastagliate e arricciate). Sapore amarognolo leggero, foglie più resistenti al caldo della lattuga, ottime cotte (scarola in particolare) o crude. Coltura tipica dell'autunno italiano.

## Semina e trapianto
- Semenzaio da giugno a settembre, trapianto dopo 4 settimane a 4-5 foglie
- Alternativa: semina diretta poi diradamento
- Distanze: 30 cm sulla fila, 40 cm tra le file
- Buca con compost maturo

## Cura
- Esposizione: sole pieno
- Irrigazione: regolare, evitare ristagni che causano marciumi del cuore
- Pacciamatura organica
- **Imbianchimento del cuore**: 10-15 giorni prima del taglio si legano le foglie esterne sopra il cuore con elastico o rafia (asciutto, mai con foglie bagnate). Il cuore non vedendo luce diventa giallo-bianco, croccante e dolce. Operazione facoltativa ma fa la differenza in cucina
- Concimazione: compost iniziale, eventualmente macerato di ortica leggero

## Avversità tipiche
- **Marciume del cuore**: causa principale umidità eccessiva e legatura con foglie bagnate. Drenaggio, pacciamatura asciutta
- **Lumache**
- **Afidi**: sapone molle
- **Tip-burn**: bordi foglie bruniti per sbalzi idrici
- **Sclerotinia**: marciume gelatinoso del cespo, rotazione lunga

## Raccolta e conservazione
- Tagliare al colletto quando il cespo è ben formato (60-90 giorni)
- Per scarola con cuore imbianchito, raccogliere 2 settimane dopo la legatura
- Conservazione: 1 settimana in frigo
- Trasformazione: scarola in padella con olive e capperi (tradizione napoletana), in zuppe, ripieni di pizza

## Consociazioni e rotazioni
- **Da evitare** con lattuga e radicchio (stessa famiglia, stessi parassiti)
- Cipolla e carota vanno bene
- **Rotazione**: 3 anni per asteracee

## Note clima costiero
Buona coltura autunno-invernale per costa centro-italiana. Resiste meglio della lattuga al caldo tardo-estivo, quindi è una buona scelta per le prime semine di settembre quando ancora fa caldo. Tollera bene salsedine. La scarola riesce a tirare avanti fino a fine inverno con la copertura delle foglie esterne legate.

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Irrigazione_a_Pioggia]]
- [[autunno]] · [[inverno]]

#pianta #orticola #asteracee #foglia
