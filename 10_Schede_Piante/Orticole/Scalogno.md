---
tipo: scheda_pianta
categoria: orticola
nome_comune: Scalogno
nome_scientifico: Allium cepa var. aggregatum
famiglia: Amaryllidaceae
ciclo: annuale
periodo_semina: "Ottobre-Dicembre; Febbraio-Marzo"
periodo_raccolta: "Giugno-Luglio"
distanza_pianta_cm: 15
distanza_fila_cm: 25
profondita_semina_cm: 2
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: basso-medio
difficolta: 1
consociazioni_buone:
  - Pomodoro
  - Carota
  - Fragola
  - Lattuga
consociazioni_da_evitare:
  - Legumi
  - Cavolo
successioni_buone:
  - Solanacee
  - Cucurbitacee
predecessori_da_evitare:
  - Amaryllidaceae
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
tags:
  - pianta
  - orticola
  - amaryllidaceae
  - bulbi
---

# 🧅 Scalogno

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Bulbo che si moltiplica per divisione: da un bulbillo piantato si ottengono 4-8 bulbilli figli, raccolti a fine ciclo. Sapore più delicato e fine della cipolla, prezioso in cucina (salse, sott'aceto). Varietà classiche: scalogno di Romagna IGP (rosa), gris di Bretagna, jermor. Si pianta sempre per propagazione vegetativa, come l'aglio.

## Semina e trapianto
- Bulbillo conficcato per metà, punta in alto
- Periodo: ottobre-dicembre o febbraio-marzo
- Distanze: 15-20 cm sulla fila, 25 cm tra le file (cresce a cespuglio di 4-8 bulbi)
- Profondità: punta del bulbillo affiorante

## Cura
- Esposizione: sole pieno
- Irrigazione: minima, come l'aglio. Sospendere a fine ciclo
- Pacciamatura sottile
- Concimazione: compost in preparazione
- Sarchiature regolari

## Avversità tipiche
- Le stesse di cipolla e aglio (marciume bianco, ruggine, mosca della cipolla)
- Generalmente resistente

## Raccolta e conservazione
- Quando le foglie sono ingiallite (giugno-luglio)
- Sollevare l'intero cespuglio con forca, separare i bulbi a mano
- Curing 2-3 settimane in luogo arieggiato
- Conservazione: 6-9 mesi in luogo fresco. Trasformazione classica: sotto aceto (cipolline borettane)

## Consociazioni e rotazioni
- Come aglio e cipolla
- **Rotazione**: 4-5 anni per Amaryllidaceae

## Note clima costiero
Stessa logica di cipolla e aglio: ottimo per la costa, semina autunnale preferibile. Si conserva bene grazie alla buccia "papiracea" che si forma nelle estati asciutte.

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]]
- [[autunno]] · [[inverno]] · [[estate]]

#pianta #orticola #amaryllidaceae #bulbi
