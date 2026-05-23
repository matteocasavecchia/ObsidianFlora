---
tipo: scheda_pianta
categoria: orticola
nome_comune: Cipolla
nome_scientifico: Allium cepa
famiglia: Amaryllidaceae
ciclo: biennale (coltivata come annuale)
periodo_semina: "Gennaio-Marzo (semenzaio); Settembre-Ottobre (autunnali)"
periodo_raccolta: "Giugno-Agosto (primaverili); Maggio-Giugno (autunnali)"
distanza_pianta_cm: 12
distanza_fila_cm: 25
profondita_semina_cm: 1
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: medio (basso a fine ciclo)
difficolta: 2
consociazioni_buone:
  - Carota (storica)
  - Bietola
  - Lattuga
  - Pomodoro
  - Fragola
  - Camomilla
consociazioni_da_evitare:
  - Legumi (pisello, fagiolo, fava)
  - Cavolo
successioni_buone:
  - Solanacee
  - Cucurbitacee
predecessori_da_evitare:
  - Liliacee/amaryllidaceae (cipolla, aglio, porro)
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
tags:
  - pianta
  - orticola
  - amaryllidaceae
  - bulbi
---

# 🧅 Cipolla

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Bulbo a strati di guaine carnose, base dell'aromatizzazione mediterranea. Tre approcci di coltivazione: **da seme** (ciclo lungo, massima scelta varietale), **da bulbillo** (più rapido e robusto, varietà più limitate), **da piantine**. Varietà classiche italiane: Tropea (rossa allungata, dolce), Borettana (piatta dorata), bianca di Maggio, ramata di Montoro, gialla di Parma, dorata di Vatolla. Cipolle primaverili (semina autunno-inverno, raccolta tarda primavera-estate) e autunnali (semina-bulbillo in estate, raccolta tardo-primavera).

## Semina e trapianto
- **Da seme**: gennaio-febbraio in semenzaio caldo, trapianto marzo-aprile. Settembre per autunnali
- **Da bulbillo**: febbraio-marzo o ottobre-novembre. Conficcare il bulbillo per metà nel terreno, punta in alto
- **Da piantina**: marzo-aprile o ottobre. Acquistate in fascette
- Distanze: 12-15 cm sulla fila, 25 cm tra le file
- Profondità: bulbillo per metà, piantina coletto a livello terreno

## Cura
- Esposizione: sole pieno
- Irrigazione: regolare nei primi due terzi del ciclo. **Sospendere irrigazione** 2-3 settimane prima della raccolta per favorire l'asciugatura del bulbo
- Pacciamatura organica utile, ma sottile (la cipolla ama il sole sul bulbo)
- Concimazione: compost in preparazione. Mai letame fresco (azoto eccessivo = chiome belle e bulbi piccoli)
- Sarchiature regolari: la cipolla non sopporta concorrenza erbacee
- **Quando le foglie si piegano** spontaneamente (segno di maturazione): non rialzarle, è il segnale che il bulbo si sta chiudendo

## Avversità tipiche
- **Mosca della cipolla** (Delia antiqua): larve scavano il bulbo, pianta avvizzisce. Reti antinsetto, consociazione con carota (la carota allontana la mosca della cipolla, la cipolla allontana la mosca della carota: storica e funzionante), trappole gialle
- **Tripidi**: macchie argentate sulle foglie. Sapone molle, predatori
- **Peronospora della cipolla**: foglie con macchie viola-grigie. Aerare il filare, rame se necessario
- **Marciume bianco** (Sclerotium cepivorum): patogeno del suolo persistente per anni, pianta avvizzisce con muffa bianca al colletto. Rotazione lunga 5+ anni
- **Bulbi piccoli**: troppo azoto, irrigazione eccessiva tarda, varietà sbagliata per il periodo

## Raccolta e conservazione
- Quando 2/3 delle foglie si sono piegate e ingiallite
- Estrarre con forca, lasciare in campo a essiccare 2-3 giorni in tempo asciutto, poi raccogliere
- **Curing**: 2-3 settimane in luogo arieggiato e ombreggiato per asciugatura completa delle tuniche esterne
- Tagliare foglie e radici quando completamente secche, conservare in trecce o cassette
- Conservazione: 6-9 mesi in cantina fresca e asciutta. Trasformazione: sott'aceto, marmellata, agrodolce

## Consociazioni e rotazioni
- **Compagne classiche**: carota (mutuo allontanamento parassiti, una delle migliori consociazioni dell'orto), bietola, lattuga, pomodoro, fragola
- **Da evitare**: legumi (le cipolle inibiscono i batteri azoto-fissatori), cavoli
- **Rotazione**: 4-5 anni per Amaryllidaceae (cipolla, aglio, porro, scalogno)

## Note clima costiero
La cipolla di Tropea è la dimostrazione che le Amaryllidaceae prosperano sulla costa centro-sud italiana. Il clima mite consente sia coltura primaverile sia autunnale (semina settembre, raccolta giugno: cipolle precoci e dolci). Tolleranza salsedine media-alta. L'unico rischio è l'umidità estiva nei giorni di raccolta: aspettare 3-4 giorni asciutti.

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
- [[primavera]] · [[estate]] · [[autunno]]

#pianta #orticola #amaryllidaceae #bulbi
