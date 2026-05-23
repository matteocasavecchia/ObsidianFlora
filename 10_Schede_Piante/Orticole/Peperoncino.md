---
tipo: scheda_pianta
categoria: orticola
nome_comune: Peperoncino
nome_scientifico: Capsicum annuum (anche C. frutescens, C. chinense)
famiglia: Solanaceae
ciclo: annuale (perenne in clima mite o in vaso riparato)
periodo_semina: "Gennaio-Marzo (semenzaio caldo); trapianto Maggio"
periodo_raccolta: "Luglio-Ottobre"
distanza_pianta_cm: 40
distanza_fila_cm: 60
profondita_semina_cm: 0.5
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.0
fabbisogno_idrico: medio (regolare, senza ristagni)
difficolta: 2
consociazioni_buone:
  - Basilico
  - Carota
  - Cipolla
  - Cetriolo
  - Tagete
consociazioni_da_evitare:
  - Finocchio
  - Cavoli
  - Altre solanacee (in rotazione)
successioni_buone:
  - Legumi
  - Cereali
predecessori_da_evitare:
  - Solanacee (pomodoro, melanzana, peperone, patata)
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
tags:
  - pianta
  - orticola
  - solanacee
---

# 🌶️ Peperoncino

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Stretto parente del peperone, dal frutto piccante per il contenuto di capsaicina (misurata in scala Scoville). Pianta cespugliosa, molto adatta al clima mediterraneo caldo e all'orto in vaso. Varietà per piccantezza crescente: **Peperoncino di Cayenna** e **Diavolicchio calabrese** (annuum, medio-piccanti, classici da essiccare), **Peperoncino a ciliegia** (tondo, anche dolce), fino ai chinense molto piccanti (**Habanero**, **Naga**). Sulla costa con inverni miti la pianta può essere svernata in vaso riparato e ripartire l'anno dopo, diventando di fatto perenne.

## Semina e trapianto
- Periodo: `=this.periodo_semina`
- Profondità semina: `=this.profondita_semina_cm` cm
- Distanze: `=this.distanza_pianta_cm` cm sulla fila, `=this.distanza_fila_cm` cm tra le file
- Modalità: semenzaio caldo (24-28 °C) da gennaio-marzo; germinazione lenta. Trapianto a maggio, con minime stabilmente sopra i 12-14 °C (più freddoloso del pomodoro). Interrare fino alle prime foglie

## Cura
- Esposizione: sole pieno, ama il caldo
- Irrigazione: regolare ma moderata, a goccia al piede, senza ristagni. Un lieve stress idrico in maturazione aumenta la piccantezza
- Concimazione: compost o letame maturo all'impianto; eccessi di azoto danno molta foglia e pochi frutti. Apporti di potassio favoriscono la fruttificazione
- Sostegno per le varietà cariche di frutti; cimatura iniziale per favorire la ramificazione
- Pacciamatura per umidità e calore al suolo

## Avversità tipiche
- **Afidi**: vettori di virosi, su germogli teneri. Sapone molle, macerati, coccinelle
- **Ragnetto rosso**: in estate calda e secca; umidità ambientale e olio di neem
- **Tripidi** e **aleurodidi** (mosca bianca): in serra o vaso; trappole cromatiche
- **Marciume apicale**: macchia nera sul fondo del frutto, fisiopatia da carenza di calcio e irrigazione irregolare. Umidità costante e pacciamatura
- **Oidio** e **botrite** in condizioni umide; arieggiare
- **Tracheoverticillosi/tracheofusariosi**: avvizzimenti, gestibili con rotazione
- Note clima costiero: pianta tra le più adatte alla costa calda; attenzione solo a vento (sostegni) e umidità marina che può favorire marciumi sui frutti maturi

## Raccolta e conservazione
- Periodo: `=this.periodo_raccolta`
- Indici: si raccoglie verde o, meglio, a colore pieno (rosso/giallo/arancio secondo varietà), quando la piccantezza è massima
- Conservazione: fresco pochi giorni; ottimo **essiccato** (al sole infilato a collana, "serta", o in essiccatore) e poi intero o in polvere. Anche sott'olio, sott'aceto o congelato
- Manipolazione: usare guanti con le varietà molto piccanti, la capsaicina irrita pelle e occhi

## Consociazioni e rotazioni
- **Compagne buone**: `=this.consociazioni_buone`
- **Da evitare**: `=this.consociazioni_da_evitare`
- **Buoni predecessori**: `=this.successioni_buone`
- **Da non far seguire a**: `=this.predecessori_da_evitare`
- **Rotazione**: minimo 3 anni prima di rimettere solanacee sulla stessa parcella

## Note clima costiero
È una delle solanacee che meglio sfrutta l'estate calda mediterranea: gradisce sole, calore e una certa parsimonia idrica. Sulla costa con inverni miti si può tentare lo svernamento in vaso (potatura corta, riparo dal freddo e dal vento), recuperando piante già adulte e produttive l'anno successivo. Vento e salsedine sono tollerati con un minimo di riparo.

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]]
- [[estate]] · [[autunno]]

#pianta #orticola #solanacee
