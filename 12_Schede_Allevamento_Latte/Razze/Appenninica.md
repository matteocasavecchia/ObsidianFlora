---
tipo: scheda_razza_lattifera
categoria: pecora
nome_razza: Appenninica
origine: Appennino centrale (Umbria, Marche, Toscana)
attitudine: duplice (carne e latte)
latte_litri_lattazione: 120
durata_lattazione_giorni: 160
grasso_pct: 6.5
proteine_pct: 5.5
peso_macellazione_kg: 22
eta_macellazione_mesi: 4
accrescimento_g_giorno: 250
resa_macellazione_pct: 50
prolificita: 1.4
eta_primo_parto_mesi: 15
peso_femmina_kg: 60
peso_maschio_kg: 90
rusticita: alta
adatta_pascolo: sì
temperamento: docile, rustica
spazio_min_mq_capo: 1.5
adatta_clima_costiero: sì
difficolta: 2
tags:
  - allevamento_latte
  - razza
---

# 🐑 Appenninica

> Specie: pecora · Attitudine: duplice (carne e latte) · Latte/lattazione: ~120 L · Rusticità: alta · Difficoltà: 2/5

## Caratteristiche
Razza ovina dell'Appennino centrale, diffusa tra Umbria, Marche e Toscana, di taglia medio-grande e vello bianco. Selezionata soprattutto per la carne (agnelli da latte e leggeri di buona conformazione), con una produzione di latte contenuta ma ricca, valorizzabile in piccola caseificazione. Molto rustica e adatta ai pascoli collinari e costieri del Centro Italia.

## Attitudine e produzione di latte
- Latte per lattazione: ~100-150 L (indicativo; dopo lo svezzamento dell'agnello)
- Durata della lattazione: ~150-180 giorni
- Grasso: ~6,5% · Proteine: ~5,5%
- Attitudine casearia: latte ricco e concentrato, buona resa; adatto a pecorino e ricotta in piccole quantità (vedi [[_MOC_Caseificazione]]).

## Attitudine e produzione di carne
- Peso alla macellazione: ~20-25 kg di peso vivo (agnello leggero o da taglio)
- Età alla macellazione: ~3-4 mesi
- Accrescimento medio: ~250 g/giorno
- Resa al macello: ~50%
- Qualità: carne di agnello apprezzata, è l'attitudine principale della razza.

## Riproduzione
- Età al primo parto: ~15 mesi
- Prolificità: ~1,3-1,5
- Stagionalità del calore / monte: prevalentemente stagionale; parti concentrati a fine inverno e primavera.

## Gestione e spazio
- Peso femmina: ~55-65 kg · maschio: ~80-95 kg
- Spazio minimo consigliato: ~1,5 m²/capo in ovile, più pascolo
- Attitudine al pascolo: ottima, valorizza pascoli collinari, appenninici e radure costiere.
- Ricovero e recinzioni: ricoveri semplici, asciutti e ventilati; recinzioni standard da ovini (vedi [[Ricovero_Recinzioni]]).

## Alimentazione
Pascolo e fieno come base, con integrazione di concentrati nell'ultimo periodo di gravidanza, in lattazione e per la finitura degli agnelli. Sale e minerali sempre disponibili (vedi [[Alimentazione_Pascolo]]).

## Rusticità e clima costiero
- Rusticità: alta
- Caldo / umidità estiva: buona tolleranza; garantire ombra e acqua nelle ore calde.
- Salsedine e vento marino: ben adattata agli ambienti tirrenici; cura piedi e vello nei periodi umidi.

## Salute e avversità tipiche
Attenzione a mastiti, parassitosi gastrointestinali e zoppie in terreni umidi; importanti la tosatura annuale e il controllo dei parassiti esterni (vedi [[Salute_Profilassi_Latte]]).

## Carattere e convivenza
- Temperamento: docile e rustica, gestibile al pascolo e alla mungitura.
- Convivenza nel gruppo: fortemente gregaria, ottima in gregge.

## Note personali
- 

## Diario di campo collegato
```dataview
TABLE file.name AS "Nota", meteo AS "Meteo"
FROM "agricoltura/40_Diario"
WHERE contains(file.outlinks, this.file.link)
SORT file.name DESC
LIMIT 10
```

## Riferimenti
- [[_MOC_Allevamento_Latte]]
- [[_MOC_Caseificazione]]
- [[Salute_Profilassi_Latte]]

#allevamento_latte #razza
