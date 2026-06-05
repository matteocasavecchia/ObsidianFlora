---
tipo: scheda_pianta
categoria: cereale
nome_comune: Maiorca
nome_scientifico: Triticum aestivum
famiglia: Poaceae
ciclo: annuale
periodo_semina: "Novembre-Dicembre"
periodo_raccolta: "Giugno"
calendario:
  - tipo: semina
    da_settimana: 45
    a_settimana: 51
    luna: calante
  - tipo: raccolta
    da_settimana: 23
    a_settimana: 27
    luna: calante
distanza_pianta_cm: 5
distanza_fila_cm: 15
profondita_semina_cm: 3
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

# 🌾 Maiorca

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Frumento **tenero** siciliano antico dalla cariosside e dalla farina **bianchissime**, tra i più pregiati grani teneri dell'isola. Spiga mutica (senza ariste), pianta alta e rustica. Farina fine e dolce, povera di glutine, tradizionalmente usata per **dolci** (biancomangiare, biscotti, cassatelle), pani bianchi e per addensare. Storicamente un grano "di lusso" per la candida farina. Va distinta dai duri siciliani (Timilia, Russello): la Maiorca è tenera e da pasticceria.

## Semina e trapianto
- **Semina diretta** tardo-autunnale, novembre-dicembre
- Profondità: 2-4 cm
- Dose: ~180-200 kg/ha
- Adatta a terreni di medio impasto, ben drenati

## Cura
- Esposizione: sole pieno
- Irrigazione: in asciutta; buona tolleranza alla siccità mediterranea
- Concimazione: azoto basso, valorizza una leguminosa in precessione
- Controllo infestanti: la taglia alta soffoca le malerbe

## Avversità tipiche
- **Allettamento** sulle piante alte; contenere azoto e fittezza
- **Ruggini**, **oidio**, **septoria** in primavere umide
- Glutine debole: non adatta alla pasta, ottima da forno e pasticceria

## Raccolta e conservazione
- Periodo: `=this.periodo_raccolta`, precoce come i grani siciliani
- Granella tenera e chiara, conservata secca e pulita
- Farina bianca a pietra per dolci e pani fini

## Consociazioni e rotazioni
- Coltura pura: conta la **rotazione**
- **Buoni predecessori**: favino, veccia
- **Da evitare**: ristoppio e altri cereali

## Note clima costiero
Grano tenero di vocazione meridionale: regge il caldo asciutto mediterraneo meglio dei teneri appenninici (Verna, Solina), pur restando un tenero sensibile ai ristagni e al caldo-umido. Sulla costa centro-italiana dà buoni risultati in terreni ben drenati e ventilati. Taglia alta: occhio all'allettamento da **vento marino** in spigatura.

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
- Grani antichi: [[Timilia]] · [[Russello]] · [[Senatore_Cappelli]]
- [[inverno]] · [[estate]]

#pianta #cereale #grano_antico
