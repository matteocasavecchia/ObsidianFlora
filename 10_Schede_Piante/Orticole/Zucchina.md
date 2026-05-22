---
tipo: scheda_pianta
categoria: orticola
nome_comune: Zucchina
nome_scientifico: Cucurbita pepo
famiglia: Cucurbitaceae
ciclo: annuale
periodo_semina: "Aprile-Giugno (diretta); Marzo (semenzaio)"
periodo_raccolta: "Giugno-Ottobre"
distanza_pianta_cm: 80
distanza_fila_cm: 120
profondita_semina_cm: 2
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.0
fabbisogno_idrico: alto e regolare
difficolta: 2
consociazioni_buone:
  - Mais
  - Fagiolo rampicante
  - Ravanello
  - Nasturzio
  - Borragine
consociazioni_da_evitare:
  - Patata
  - Cetriolo (stessa famiglia)
successioni_buone:
  - Legumi
  - Insalate
predecessori_da_evitare:
  - Cucurbitacee (zucca, cetriolo, melone, cocomero)
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Subirrigazione]]"
tags:
  - pianta
  - orticola
  - cucurbitacee
---

# 🥒 Zucchina

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Coltura generosa, produce per mesi con poche cure. In costa mediterranea va benissimo a partire da aprile inoltrato. Varietà classiche: striata pugliese, romanesca (a coste), genovese (chiara, allungata), tonda di Nizza. Esistono cultivar a portamento compatto (cespuglio) o rampicante (ottimo a parete o su pergola, libera molto spazio a terra).

## Semina e trapianto
- Semina diretta da metà aprile sulla costa, in postarella con 2-3 semi a buca, profondità 2 cm; si dirada lasciando la pianta migliore
- In semenzaio da marzo in vasetti grandi (10 cm), trapianto a metà-fine aprile
- Distanze: 80 cm sulla fila per le cespugliose, 120 cm tra le file. Le rampicanti a 100-150 cm anche tra le piante
- Letame o compost maturo nella postarella, ama il terreno ricco

## Cura
- Esposizione: sole pieno
- Irrigazione: abbondante e regolare, a goccia al piede. Mai sulle foglie (oidio garantito). Pacciamatura indispensabile per ridurre evaporazione estiva
- Concimazione: ricarica di compost a metà ciclo se la produzione cala
- Sarchiature leggere finché la pianta non chiude il filare
- Su varietà rampicanti, palo o rete: fiori e frutti più puliti, meno marciumi, raccolta facile
- Impollinazione: fiori maschili e femminili separati sulla stessa pianta. In assenza di api (giardini cittadini, primissimo periodo) si può impollinare a mano staccando un fiore maschile e strofinando il polline sullo stigma del femminile

## Avversità tipiche
- **Oidio**: la malattia di gran lunga più frequente, soprattutto da luglio in poi. Aerare il filare, eliminare foglie basse e ingiallite, zolfo bagnabile sotto i 28°C, decotto di equiseto in prevenzione, bicarbonato di sodio (15 g per litro + olio vegetale)
- **Virosi (mosaico)**: pianta deformata, foglie a mosaico verde chiaro/scuro. Vettore principale gli afidi. Eliminare piante colpite, controllare afidi
- **Peronospora**: meno frequente dell'oidio sulla zucchina, comunque rame in poltiglia se serve
- **Marciume apicale del frutto**: stesso meccanismo del pomodoro, irrigazione irregolare e carenza di calcio
- **Cimice asiatica, afidi**: macerati e sapone molle
- **Lumache** in primavera sulle piantine giovani: cenere, gusci d'uovo, trappole di birra, raccolta serale

## Raccolta e conservazione
- Si raccoglie giovane (15-25 cm a seconda della varietà), prima che il seme si formi: la pianta continua a produrre solo se non si lasciano frutti maturare
- Frequenza: ogni 1-2 giorni in piena estate
- Frutti dimenticati diventano legnosi ma si possono usare per zuppe, ripieni grandi, o lasciare per autoprodurre semi
- Fiori (maschili soprattutto) ottimi fritti o ripieni: raccolta al mattino
- Conservazione: 1 settimana in frigo. Conservazione lunga: sott'olio, sott'aceto, surgelate a cubetti

## Consociazioni e rotazioni
- **Tre sorelle**: mais (sostegno), fagiolo rampicante (azoto), zucca/zucchina (copertura del suolo). Strategia precolombiana adatta anche all'orto mediterraneo
- **Compagne**: ravanello (confonde le piralidi), nasturzio (trappola per afidi), borragine (attira impollinatori)
- **Da evitare**: altre cucurbitacee (malattie comuni), patata (competizione idrica)
- **Rotazione**: minimo 3 anni prima di tornare con cucurbitacee sulla stessa parcella

## Note clima costiero
Soffre meno la salsedine di altre cucurbitacee. Il vento può rompere le foglie grandi: in zone esposte conviene impiantare in posizione un po' riparata o vicino a un frangivento. La produzione in agosto cala drasticamente con il caldo torrido: spesso conviene fare due cicli, uno primaverile a maggio e uno tardo a luglio per produrre fino a ottobre.

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Subirrigazione]]
- [[primavera]] · [[estate]]

#pianta #orticola #cucurbitacee
