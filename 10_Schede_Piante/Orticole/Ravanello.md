---
tipo: scheda_pianta
categoria: orticola
nome_comune: Ravanello
nome_scientifico: Raphanus sativus
famiglia: Brassicaceae
ciclo: annuale
periodo_semina: "Febbraio-Ottobre (scalare ogni 15 giorni)"
periodo_raccolta: "25-40 giorni dopo la semina"
distanza_pianta_cm: 4
distanza_fila_cm: 20
profondita_semina_cm: 1
esposizione: sole pieno o mezz'ombra
ph_min: 6.0
ph_max: 7.0
fabbisogno_idrico: medio-alto, costante
difficolta: 1
consociazioni_buone:
  - Carota (segnafila)
  - Lattuga
  - Pomodoro
  - Cetriolo
  - Pisello
  - Fagiolo
consociazioni_da_evitare:
  - Altre brassicacee
  - Hyssopus
successioni_buone:
  - Quasi tutto (ciclo breve, riempitivo)
predecessori_da_evitare:
  - Brassicacee
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - brassicacee
  - radici
---

# 🌰 Ravanello

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
La coltura più rapida dell'orto: dalla semina alla raccolta in 25-40 giorni. Ottima per riempire spazi tra piante a ciclo lungo, per insegnare a chi inizia, e come "segnafila" su semine lente come la carota (germina prima e segnala dove sono le file). Varietà classiche: tondo rosso, mezzo lungo bianco-punta-rossa, sassolino, ramolaccio (varietà grande tipo daikon).

## Semina e trapianto
- Solo semina diretta
- Da febbraio a ottobre, scalare ogni 15 giorni per raccolto continuo
- Profondità: 1 cm
- Distanze: 4-5 cm sulla fila dopo diradamento, 20 cm tra le file
- Diradamento a 3-4 cm tra le piantine

## Cura
- Esposizione: sole pieno in primavera/autunno, mezz'ombra in estate (caldo intenso = pianta amara e fibrosa)
- Irrigazione: abbondante e costante, il ravanello deve crescere veloce per essere tenero e dolce. Sbalzi idrici = ravanelli spaccati e piccanti
- Pacciamatura leggera in estate
- Concimazione minima: troppo azoto = foglie grandi e radice piccola

## Avversità tipiche
- **Altica**: piccoli fori tondi sulle foglie giovani, in primavera. Pacciamatura, irrigazione costante (l'altica ama il secco), reti antinsetto
- **Mosca del cavolo**: gallerie nelle radici. Reti antinsetto sopra il filare
- **Lumache** sui ravanelli giovani
- **Spaccature radice**: irregolarità irrigua

## Raccolta e conservazione
- Appena la radice raggiunge la dimensione tipica della varietà: tardare di pochi giorni = ravanello "legnoso" o spugnoso
- Tirare a mano, tagliare le foglie a 2 cm dal colletto
- **Le foglie sono commestibili** e ottime cotte come spinaci o nelle minestre
- Conservazione: 1 settimana in frigo. Sottaceti, lattofermentati
- I ramolacci grandi si conservano in sabbia umida per mesi

## Consociazioni e rotazioni
- **Compagne**: praticamente tutte le verdure dell'orto. **Segnafila con la carota** (classico), pomodoro (sotto), lattuga, pisello, fagiolo
- **Da evitare**: altre brassicacee (rotazione), isssopo
- **Rotazione**: meno critica per il ciclo breve, ma rispettare comunque 2-3 anni per non concentrare patogeni delle brassicacee

## Note clima costiero
Coltura facile e veloce per tutta la stagione fresca sulla costa. In piena estate va parzialmente ombreggiato e tenuto umido o diventa piccante e legnoso. Eccellente per riempire piccoli spazi tra le grandi colture estive (sotto i pomodori giovani, ad esempio): si raccoglie prima che le solanacee chiudano lo spazio.

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
- [[primavera]] · [[estate]] · [[autunno]]

#pianta #orticola #brassicacee #radici
