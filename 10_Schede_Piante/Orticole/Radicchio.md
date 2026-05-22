---
tipo: scheda_pianta
categoria: orticola
nome_comune: Radicchio
nome_scientifico: Cichorium intybus
famiglia: Asteraceae
ciclo: annuale o biennale
periodo_semina: "Giugno-Agosto"
periodo_raccolta: "Ottobre-Marzo"
distanza_pianta_cm: 30
distanza_fila_cm: 40
profondita_semina_cm: 0.5
esposizione: sole pieno (mezz'ombra in semina estiva)
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: medio
difficolta: 2
consociazioni_buone:
  - Finocchio (eccezione alla regola, sembra ok)
  - Cipolla
  - Pomodoro (a fine ciclo del pomodoro)
consociazioni_da_evitare:
  - Insalate (lattuga, indivia)
successioni_buone:
  - Legumi
predecessori_da_evitare:
  - Asteracee (lattuga, indivia, scarola, carciofo)
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - asteracee
  - foglia
---

# 🥗 Radicchio

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Cicoria coltivata, dal sapore amarognolo caratteristico. Le varietà italiane sono un patrimonio: rosso di Chioggia (testa tonda, precoce), rosso di Treviso precoce (allungato, foglie rosse e nervatura bianca), rosso di Treviso tardivo (richiede forzatura, dolce e croccante), variegato di Castelfranco (rosa con macchie rosse), pan di zucchero (verde chiaro, simile a lattuga romana, fa "cappuccio" naturalmente), rosso di Verona. Coltura tipica autunno-invernale del Nord Italia ma adatta anche al centro costiero.

## Semina e trapianto
- Semenzaio da giugno ad agosto secondo la varietà
- Trapianto dopo 4-5 settimane a 4-5 foglie vere
- Distanze: 30 cm sulla fila, 40 cm tra le file
- Buca con compost maturo

## Cura
- Esposizione: sole pieno autunno; in semenzaio estivo, ombreggiare le piantine
- Irrigazione: regolare, evitare ristagni che causano marciumi del cuore
- Pacciamatura organica utile
- Concimazione: compost iniziale è sufficiente, evitare eccesso azoto che riduce colorazione rossa e sapore
- **Imbianchimento dei tardivi**: per il Treviso tardivo classico si fa la **forzatura**: piante zollate, messe al buio in tunnel con acqua calda corrente o in cassoni interrati, le foglie si rinnovano bianche e croccanti. Operazione complessa, riservata a chi vuole esplorare la tecnica
- Per i precoci, l'imbianchimento si fa legando il cespo con un elastico/spago 1-2 settimane prima del taglio

## Avversità tipiche
- **Nottue**: rimedi classici
- **Lumache**: trappole, gusci d'uovo, cenere
- **Afidi**: sapone molle
- **Marciumi del cuore**: causa principale umidità eccessiva e ristagni. Drenaggio, pacciamatura asciutta sotto il cespo, irrigazione al piede
- **Tip-burn** (bordo foglie bruciato): carenza di calcio o sbalzo idrico

## Raccolta e conservazione
- Quando il cespo è ben formato (autunno-inverno)
- Tagliare al colletto con coltello
- **Il radicchio resiste a temperature anche sotto zero**: nelle zone del Nord Italia si raccoglie sotto la neve. Sulla costa centro-italiana è coltura "tranquilla" per inverno
- Conservazione: 1-2 settimane in frigo. Trasformazione: sott'olio dopo grigliatura, sott'aceto, in conserva di Treviso

## Consociazioni e rotazioni
- **Da evitare** con altre asteracee (lattuga, indivia, scarola)
- **Rotazione**: 3 anni per le asteracee

## Note clima costiero
Cresce molto bene sulla costa centro-italiana grazie agli inverni miti. Le varietà a foglia rossa (Chioggia, Treviso) sviluppano colore intenso con il freddo: le mattine fredde di novembre-dicembre fanno virare il cespo dal verde al rosso vivo. Tollera bene salsedine e venti.

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Irrigazione_a_Pioggia]]
- [[autunno]] · [[inverno]]

#pianta #orticola #asteracee #foglia
