---
tipo: scheda_pianta
categoria: orticola
nome_comune: Broccolo
nome_scientifico: Brassica oleracea var. italica
famiglia: Brassicaceae
ciclo: annuale
periodo_semina: "Giugno-Agosto (semenzaio); Agosto-Settembre (trapianto)"
periodo_raccolta: "Ottobre-Marzo"
distanza_pianta_cm: 50
distanza_fila_cm: 70
profondita_semina_cm: 1
esposizione: sole pieno
ph_min: 6.5
ph_max: 7.5
fabbisogno_idrico: medio-alto
difficolta: 2
consociazioni_buone:
  - Lattuga
  - Sedano
  - Aneto
  - Aglio
  - Camomilla
consociazioni_da_evitare:
  - Altre brassicacee
  - Fragola
successioni_buone:
  - Legumi
predecessori_da_evitare:
  - Brassicacee
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - brassicacee
---

# 🥦 Broccolo

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Più semplice del cavolfiore, ha il vantaggio di produrre prima un corimbo centrale e poi numerose **broccolette laterali**: una sola pianta produce per settimane. Varietà tipiche: broccolo calabrese (compatto), broccolo verde a getti, broccolo nero (gambi viola scuro). Da non confondere con le cime di rapa (altra specie, Brassica rapa, che si comporta diversamente).

## Semina e trapianto
- Semenzaio da fine giugno ad agosto
- Trapianto agosto-settembre con 4-5 foglie
- Distanze: 50 cm sulla fila, 70 cm tra le file
- Buca con compost o letame maturo

## Cura
- Esposizione: sole pieno
- Irrigazione: regolare, mai sulle foglie. La pianta soffre stress idrici sia in eccesso che in difetto
- Pacciamatura organica
- Concimazione: macerato di ortica ogni 3 settimane. Per spingere le broccolette laterali dopo la raccolta del corimbo centrale, una buona concimazione organica subito dopo
- Rincalzo a 2-3 settimane dal trapianto

## Avversità tipiche
- Stesse di cavolo e cavolfiore: cavolaia, nottue, afidi cinerini, mosca del cavolo, ernia delle crucifere, altica
- Le reti antinsetto restano la difesa più efficace e pulita

## Raccolta e conservazione
- Corimbo centrale: si raccoglie quando i fiorellini sono ancora chiusi, compatti, di colore intenso. Se cominciano ad aprirsi (gialli) si è in ritardo
- Tagliare 10-15 cm sotto il corimbo, lasciando la pianta in posto
- **Broccolette laterali**: nascono dalle ascelle fogliari dopo la raccolta centrale. Si raccolgono a mano a mano per 4-8 settimane
- Conservazione: 1 settimana in frigo. Sbianchite e congelate mantengono benissimo. Sott'olio dopo bollitura

## Consociazioni e rotazioni
- Come per cavolo e cavolfiore
- **Rotazione**: minimo 4 anni per le brassicacee

## Note clima costiero
Coltura ottima per autunno-inverno costiero. Tollera bene venti e umidità marina. Le minime miti permettono produzione di broccolette fino a marzo inoltrato.

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

#pianta #orticola #brassicacee
