---
tipo: scheda_pianta
categoria: orticola
nome_comune: Valeriana (Songino, Dolcetta)
nome_scientifico: Valerianella locusta
famiglia: Caprifoliaceae
ciclo: annuale
periodo_semina: "Agosto-Ottobre (principale); Febbraio-Marzo"
periodo_raccolta: "Ottobre-Aprile"
distanza_pianta_cm: 8
distanza_fila_cm: 15
profondita_semina_cm: 0.5
esposizione: sole pieno o mezz'ombra
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: medio
difficolta: 1
consociazioni_buone:
  - Cipolla
  - Carota
  - Cavolo
  - Pomodoro (sotto, autunno)
consociazioni_da_evitare:
  - Lattuga giovane (concorrenza simile)
successioni_buone:
  - Quasi tutto
predecessori_da_evitare:
  - Valeriana stessa
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - foglia
---

# 🌿 Valeriana (Songino)

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Piccola pianta a rosetta basale, foglie tenere a forma di cucchiaio, sapore delicato e leggermente nocciolato. Diversa dalla valeriana medicinale (Valeriana officinalis, usata per i suoi rizomi calmanti): qui parliamo del **songino** o **dolcetta**, classica insalata invernale che resiste a temperature anche sotto zero. Varietà: a chicco grosso, verde scuro d'inverno, d'Olanda.

## Semina e trapianto
- Solo semina diretta, a spaglio o in fila
- **Periodo principale**: agosto-ottobre (raccolta autunno-inverno). Possibile anche febbraio-marzo per coltura tardiva
- Profondità: 0.5-1 cm
- Distanze: 8-10 cm tra le piantine dopo diradamento, 15 cm tra le file
- Germinazione lenta a temperature alte (sopra 20°C entra in dormienza), preferisce temperature fresche

## Cura
- Esposizione: sole pieno autunno-inverno, mezz'ombra in semina tardo-estiva
- Irrigazione: regolare ma non eccessiva, ama l'umidità ma non i ristagni
- Pacciamatura sottile aiuta soprattutto dopo l'emergenza
- Concimazione minima

## Avversità tipiche
- **Lumache**: il principale problema su piantine giovani
- **Marciume del colletto**: ristagni, drenaggio importante
- **Oidio**: rara, principalmente su semine tardive
- Generalmente coltura molto robusta

## Raccolta e conservazione
- Si recide la **rosetta intera** al colletto quando ha 6-8 foglie ben sviluppate
- **Resiste al gelo** fino a -10°C, si raccoglie anche sotto la neve (qualità migliore dopo gelate leggere, gli zuccheri si concentrano)
- Conservazione: 3-5 giorni in frigo. Consumo a crudo (mai cotta, rovinerebbe sapore)

## Consociazioni e rotazioni
- **Compagne**: cipolla, carota, cavolo. Ottima sotto-coltura nell'orto autunnale, sfrutta spazi vuoti dopo le solanacee
- **Da evitare**: lattuga giovane in stesso filare (concorrenza)
- **Rotazione**: 2 anni per la valeriana

## Note clima costiero
Coltura **perfetta per l'inverno costiero centro-italiano**: cresce bene con le minime miti tipiche della costa, non risente di salsedine, è una delle insalate più "automatiche" per il periodo dicembre-marzo. Spesso si autosemina nell'orto se lasciata fiorire (autosemina spontanea utile). Il vento marino non la disturba.

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

#pianta #orticola #foglia
