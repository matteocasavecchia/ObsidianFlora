---
tipo: scheda_pianta
categoria: orticola
nome_comune: Zucca
nome_scientifico: Cucurbita maxima / C. moschata / C. pepo
famiglia: Cucurbitaceae
ciclo: annuale
periodo_semina: "Aprile-Giugno"
periodo_raccolta: "Settembre-Novembre"
distanza_pianta_cm: 120
distanza_fila_cm: 200
profondita_semina_cm: 3
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: medio-alto
difficolta: 2
consociazioni_buone:
  - Mais
  - Fagiolo (tre sorelle)
  - Tagete
  - Borragine
  - Nasturzio
consociazioni_da_evitare:
  - Altre cucurbitacee
  - Patata
successioni_buone:
  - Legumi
  - Insalate
  - Cavoli
predecessori_da_evitare:
  - Cucurbitacee
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Conca_e_Solco]]"
tags:
  - pianta
  - orticola
  - cucurbitacee
---

# 🎃 Zucca

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Tre specie di "zucca" in coltivazione: **Cucurbita maxima** (zucche grosse a polpa arancione, es. marina di Chioggia, hokkaido, atlantic giant), **C. moschata** (zucca napoletana lunga, butternut/violina, trombetta d'Albenga), **C. pepo** (zucche piccole estive e zucche ornamentali, include anche zucchine e patisson). Coltura semplice, ottima conservazione invernale, produttivissima. Le moschate sono particolarmente adatte al clima mediterraneo.

## Semina e trapianto
- Semina diretta da aprile in postarella
- Semenzaio possibile per anticipare (in vasetti grandi, no trapianto a radice nuda)
- Profondità: 3 cm
- Distanze: variano molto secondo varietà:
  - Zucche grosse (maxima): 120 × 200 cm
  - Zucche allungate (moschata): 100 × 180 cm
  - Le rampicanti su pergola/rete possono stare più strette
- Buca generosa con compost/letame maturo, la zucca è ingorda

## Cura
- Esposizione: sole pieno
- Irrigazione: regolare in tutto il ciclo, abbondante in fioritura. A goccia al piede
- Pacciamatura organica spessa (riduce evaporazione, tiene puliti i frutti)
- Concimazione: macerato di consolida in fioritura
- **Allevamento verticale per moschate piccole** (butternut, trombetta): risparmiano spazio enormemente. Su pergola si sostengono i frutti in calza
- Sotto i frutti pesanti delle maxima: tavoletta o pacciame asciutto

## Avversità tipiche
- **Oidio**: zolfo, bicarbonato, equiseto
- **Peronospora**: rame
- **Marciume del frutto**: contatto col terreno bagnato
- **Cimice asiatica, afidi**: macerati e sapone molle
- **Lumache** sui frutti piccoli

## Raccolta e conservazione
- Quando il peduncolo è asciutto e legnoso, la buccia è dura e suona "sorda" al tatto
- Tagliare con peduncolo (8-10 cm), aiuta conservazione
- **Curing** (importante): 7-10 giorni al sole tiepido di settembre per indurire la buccia
- Conservazione: 4-8 mesi in cantina fresca e asciutta. Le moschate sono le più conservabili
- Trasformazione: gnocchi, vellutate, ripieni di tortelli, marmellata, semi tostati
- I **fiori** (raccolti al mattino) sono ottimi fritti o ripieni

## Consociazioni e rotazioni
- **Tre sorelle**: classica e funzionante. Mais (sostegno per fagiolo), fagiolo rampicante (azoto), zucca (copertura del suolo, controllo erbacce)
- **Compagne**: tagete, borragine, nasturzio
- **Da evitare**: altre cucurbitacee, patata
- **Rotazione**: 3-4 anni per cucurbitacee

## Note clima costiero
Coltura **eccellente per costa centro-italiana**: zucche moschate (butternut, violina, trombetta d'Albenga) producono frutti dolcissimi e conservabili. La trombetta d'Albenga in particolare è coltura tradizionale della costa ligure. Salsedine tollerata. Le grosse maxima vanno seminate a fine aprile per evitare cracking da maturazione tardiva con piogge autunnali.

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Irrigazione_a_Conca_e_Solco]]
- [[primavera]] · [[estate]] · [[autunno]]

#pianta #orticola #cucurbitacee
