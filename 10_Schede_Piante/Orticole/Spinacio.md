---
tipo: scheda_pianta
categoria: orticola
nome_comune: Spinacio
nome_scientifico: Spinacia oleracea
famiglia: Amaranthaceae
ciclo: annuale
periodo_semina: "Settembre-Marzo (costa, evitando freddo intenso)"
periodo_raccolta: "Novembre-Maggio"
distanza_pianta_cm: 15
distanza_fila_cm: 25
profondita_semina_cm: 2
esposizione: sole pieno (mezz'ombra in semina autunnale)
ph_min: 6.5
ph_max: 7.5
fabbisogno_idrico: medio-alto, costante
difficolta: 2
consociazioni_buone:
  - Fragola
  - Cavolo
  - Pisello
  - Rapanello
consociazioni_da_evitare:
  - Bietola (stessa famiglia)
  - Barbabietola
successioni_buone:
  - Solanacee
  - Cucurbitacee
predecessori_da_evitare:
  - Spinacio, bietola, barbabietola
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - foglia
---

# 🥬 Spinacio

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Verdura a foglia ricca di ferro, vitamine e ossalati. Cresce nei mesi freschi, va a seme rapidamente con il caldo. Varietà classiche: gigante d'inverno (resistente al freddo), matador, monstrueux de Viroflay (foglia grande), varietà a foglia liscia e a foglia "bollosa" (savoy). Per costa centro-italiana lo spinacio è coltura autunno-inverno-primavera.

## Semina e trapianto
- Solo semina diretta (lo spinacio non gradisce il trapianto)
- Sulla costa: da settembre a marzo, evitando le settimane più fredde
- Profondità: 2 cm
- Distanze: 15 cm sulla fila dopo diradamento, 25 cm tra le file
- Germinazione lenta (8-15 giorni), pre-bagnatura del solco aiuta

## Cura
- Esposizione: sole pieno autunno-inverno-primavera, mezz'ombra solo per semine tardive che vanno verso l'estate
- Irrigazione: regolare, mai stress idrico (=andata a seme immediata)
- Pacciamatura organica
- Concimazione: compost in preparazione. Lo spinacio ama il terreno fertile e ricco di azoto
- **Gestione ossalati**: lo spinacio accumula ossalati, soprattutto a fine ciclo. Raccogliere giovane riduce il contenuto

## Avversità tipiche
- **Peronospora dello spinacio** (Peronospora farinosa): macchie giallastre, muffa sotto la foglia. Aerare, eliminare piante colpite, rame in casi gravi
- **Afidi**: sapone molle, predatori
- **Minatori fogliari**: gallerie chiare nelle foglie. Eliminare foglie colpite
- **Andata a seme**: lo spinacio è una pianta a giorno lungo, va a seme quando le giornate si allungano (da aprile in poi). Per evitarla: semina autunno-inverno, varietà resistenti per primavera

## Raccolta e conservazione
- **Foglia per foglia**: dalle esterne, lasciando il cuore per ricacciare. Una pianta produce per 4-6 settimane
- **Intera**: si taglia al colletto quando la pianta è ben formata (50-60 giorni)
- Mai raccogliere con foglie bagnate (marcisce subito)
- Conservazione: 2-3 giorni in frigo. Sbianchito e congelato ottimo. Sott'olio dopo cottura

## Consociazioni e rotazioni
- **Compagne**: fragola (storica), cavolo, pisello (azoto), ravanello
- **Da evitare**: bietola, barbabietola (stessa famiglia, malattie comuni)
- **Rotazione**: 3 anni per spinacio/bietola/barbabietola (stessa famiglia)

## Note clima costiero
Coltura ideale per autunno-inverno-primavera sulla costa centro-italiana. Le minime miti non lo bloccano, le estati torride sì (in estate si rimpiazza con la **tetragonia** o "spinacio della Nuova Zelanda", Tetragonia tetragonioides, che resiste al caldo). Tolleranza salsedine media. In presenza di gelate intense conviene proteggere con tessuto non tessuto.

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
- [[autunno]] · [[inverno]] · [[primavera]]

#pianta #orticola #foglia
