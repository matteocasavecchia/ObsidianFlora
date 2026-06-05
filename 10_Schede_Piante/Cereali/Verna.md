---
tipo: scheda_pianta
categoria: cereale
nome_comune: Verna
nome_scientifico: Triticum aestivum
famiglia: Poaceae
ciclo: annuale
periodo_semina: "Ottobre-Novembre"
periodo_raccolta: "Luglio"
calendario:
  - tipo: semina
    da_settimana: 42
    a_settimana: 47
    luna: calante
  - tipo: raccolta
    da_settimana: 27
    a_settimana: 31
    luna: calante
distanza_pianta_cm: 5
distanza_fila_cm: 15
profondita_semina_cm: 3
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: basso
difficolta: 2
consociazioni_buone:
  - Leguminose (sovescio precedente)
consociazioni_da_evitare:
  - Altri cereali
successioni_buone:
  - Favino
  - Trifoglio
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

# 🌾 Verna

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Frumento **tenero** toscano, selezionato a metà Novecento e oggi simbolo del recupero dei grani antichi in Appennino. Pianta alta, spiga aristata bianca, rustica e adatta alla montagna e alla collina interna. Famoso per la **bassa forza del glutine (W basso)** e per studi che ne segnalano l'alta digeribilità: ottimo per pane a lievitazione naturale, dolci e farine integrali macinate a pietra. Non è da pasta (è tenero), ma da pane e da forno.

## Semina e trapianto
- **Semina diretta** autunnale, ottobre-novembre
- Profondità: 2-4 cm (la cariosside tenera è più piccola del duro)
- Dose: ~180-200 kg/ha
- Adatto a terreni collinari e montani, anche poveri

## Cura
- Esposizione: sole pieno
- Irrigazione: in asciutta; buona rusticità in ambiente fresco-umido
- Concimazione: azoto contenuto, valorizza una leguminosa in precessione
- Controllo infestanti: la taglia alta soffoca le malerbe

## Avversità tipiche
- **Allettamento** sulle piante alte: contenere azoto e fittezza
- **Ruggini**, **septoria** e **oidio** in primavere umide
- **Fusariosi della spiga**: rotazione e residui gestiti

## Raccolta e conservazione
- Periodo: `=this.periodo_raccolta`, leggermente più tardivo dei duri
- Granella tenera conservata secca e pulita
- Si macina a pietra in farina tipo 1, 2 o integrale per pane e dolci

## Consociazioni e rotazioni
- Coltura pura: conta la **rotazione**
- **Buoni predecessori**: favino, trifoglio, veccia (azoto)
- **Da evitare**: ristoppio e altri cereali in successione stretta

## Note clima costiero
Nato per la collina e la montagna toscana, in pianura costiera va seminato presto e su terreni ben drenati: soffre più del duro il caldo-umido e i ristagni. Sulla fascia costiera dà il meglio in posizioni fresche e ventilate; attenzione all'allettamento da **vento marino** sulle piante alte. Per la costa calda e secca i frumenti duri (Senatore Cappelli, Russello) sono più vocati; la Verna resta la scelta per pane tenero e farine da forno.

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
- Grani antichi: [[Gentil_Rosso]] · [[Solina]] · [[Senatore_Cappelli]]
- [[autunno]] · [[estate]]

#pianta #cereale #grano_antico
