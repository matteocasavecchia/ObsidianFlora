---
tipo: scheda_pianta
categoria: cereale
nome_comune: Timilia
nome_scientifico: Triticum turgidum subsp. durum
famiglia: Poaceae
ciclo: annuale
periodo_semina: "Novembre-Gennaio (o Febbraio-Marzo come marzuolo)"
periodo_raccolta: "Giugno"
calendario:
  - tipo: semina
    da_settimana: 45
    a_settimana: 52
    luna: calante
  - tipo: raccolta
    da_settimana: 23
    a_settimana: 27
    luna: calante
distanza_pianta_cm: 5
distanza_fila_cm: 15
profondita_semina_cm: 4
esposizione: sole pieno
ph_min: 6.0
ph_max: 8.0
fabbisogno_idrico: basso
difficolta: 2
consociazioni_buone:
  - Leguminose (sovescio precedente)
consociazioni_da_evitare:
  - Altri cereali
successioni_buone:
  - Favino
  - Veccia
predecessori_da_evitare:
  - Frumento
  - Orzo
tags:
  - pianta
  - cereale
  - poaceae
  - grano_antico
---

# 🌾 Timilia

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Frumento duro siciliano antichissimo, detto anche **Tumminìa** o "grano marzuolo" perché può essere seminato tardi, fin verso marzo, completando un ciclo breve. Spiga nera aristata, cariosside piccola, resa modesta ma straordinaria rusticità e tolleranza alla siccità: storicamente il grano delle annate avare e dei terreni difficili. È la semola del celebre **pane nero di Castelvetrano**. Sapore intenso, colore scuro, ottimo indice di tollerabilità.

## Semina e trapianto
- **Semina diretta**: tradizionalmente tardo-autunnale (novembre-gennaio); come **marzuolo** anche a fine inverno (febbraio-marzo)
- Profondità: 3-5 cm
- Ciclo breve: matura presto, tra i primi a essere mietuto
- Adatta a terreni poveri e siccitosi

## Cura
- Esposizione: sole pieno
- Irrigazione: in asciutta, fra i frumenti più resistenti alla siccità
- Concimazione: minima, è un grano frugale; eccesso d'azoto controproducente
- Controllo infestanti: ciclo rapido e rusticità aiutano

## Avversità tipiche
- Rusticità elevata, poche avversità in clima caldo-asciutto
- **Ruggini** possibili in primavere umide
- Resa contenuta: è il prezzo della rusticità, non un difetto sanitario

## Raccolta e conservazione
- Periodo: `=this.periodo_raccolta`, tra i primi grani a maturare
- Granella piccola e scura, conservata secca e pulita
- Semola scura per pane (pane nero), pasta e biscotti tradizionali

## Consociazioni e rotazioni
- Coltura pura: conta la **rotazione**
- **Buoni predecessori**: favino, veccia
- **Da evitare**: ristoppio e altri cereali in successione stretta

## Note clima costiero
Vocazione spiccatamente mediterranea e meridionale: ama il caldo secco e teme poco la siccità, quindi ben adatta a estati costiere asciutte. Ciclo breve e taglia non eccessiva la rendono meno esposta all'allettamento da vento rispetto ad altri grani antichi alti. Buona tolleranza ad ambienti aridi e salini.

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
- Grani antichi: [[Russello]] · [[Maiorca]] · [[Senatore_Cappelli]]
- [[inverno]] · [[estate]]

#pianta #cereale #grano_antico
