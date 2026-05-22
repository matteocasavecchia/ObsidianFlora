---
tipo: scheda_pianta
categoria: orticola
nome_comune: Pisello
nome_scientifico: Pisum sativum
famiglia: Fabaceae
ciclo: annuale
periodo_semina: "Ottobre-Marzo (costa)"
periodo_raccolta: "Marzo-Giugno"
distanza_pianta_cm: 5
distanza_fila_cm: 50
profondita_semina_cm: 3
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: medio
difficolta: 2
consociazioni_buone:
  - Carota
  - Ravanello
  - Lattuga
  - Cetriolo
  - Mais
consociazioni_da_evitare:
  - Cipolla
  - Aglio
  - Scalogno
  - Porro
successioni_buone:
  - Solanacee
  - Cucurbitacee
  - Cavoli (apportano azoto)
predecessori_da_evitare:
  - Fabacee (fagiolo, fava, cece)
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - fabacee
  - legumi
---

# 🟢 Pisello

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Legume rampicante (varietà alte) o cespuglioso (varietà nane). Tipologie: **pisello da sgranare** (semi tondi, baccelli da scartare), **mangiatutto** (taccola, baccelli teneri commestibili interi), **mezzo mangiatutto** (snap pea, mix). Varietà italiane: telefono nano, lincoln, taccola gigante, Carouby de Mausanne. Pianta che **fissa azoto atmosferico** grazie ai noduli radicali con Rhizobium, lascia il terreno arricchito per la coltura successiva.

## Semina e trapianto
- Solo semina diretta (radici fragili, no trapianto)
- **Costa centro-italiana**: si semina da ottobre a marzo. La semina autunnale resiste agli inverni miti e produce in marzo-aprile, anticipando di un mese le primaverili
- Profondità: 3-4 cm
- Distanze: 5-6 cm sulla fila, 50 cm tra le file (varietà rampicanti vogliono 70-80 cm tra file)
- Nessun concime azotato! Il pisello si fa l'azoto da solo

## Cura
- Esposizione: sole pieno in inverno-primavera. In zone troppo calde mezz'ombra
- Irrigazione: moderata, evitare ristagni (marciumi radicali)
- **Sostegno per le varietà rampicanti**: rete, frasche di nocciolo, palificazione. Le varietà nane stanno in piedi da sole
- Pacciamatura organica
- Concimazione: compost in preparazione, mai letame
- Sarchiature leggere senza danneggiare le radici

## Avversità tipiche
- **Tonchio del pisello** (Bruchus pisorum): coleottero che depone uova sui fiori, larve dentro i semi. Difficile da gestire in biologico, raccolta tempestiva e immediato consumo o congelamento
- **Oidio**: foglie con patina bianca, soprattutto a fine ciclo. Zolfo bagnabile, decotto equiseto in prevenzione
- **Afidi**: vettori di virosi, sapone molle e predatori
- **Marciume radicale** da Fusarium o Pythium: ristagni d'acqua, rotazione

## Raccolta e conservazione
- **Da sgranare**: quando i baccelli sono ben pieni ma ancora verdi e lucidi, prima che ingialliscano. Sgranare appena raccolti
- **Mangiatutto**: quando i baccelli sono ancora piatti, semi appena visibili
- Frequenza: ogni 2-3 giorni in piena produzione, stimola nuova fioritura
- Conservazione: 1 settimana in frigo nei baccelli. Sgranati e congelati ottimi. Essiccati in baccello per zuppe invernali

## Consociazioni e rotazioni
- **Compagne**: carota (sfrutta strati diversi), ravanello (ciclo rapido sotto), lattuga, cetriolo (sale insieme), mais (sistema "tre sorelle" con zucca)
- **Da evitare**: Amaryllidaceae (cipolla, aglio, scalogno, porro): le Amaryllidaceae inibiscono i batteri azoto-fissatori del pisello
- **Rotazione**: 3-4 anni per fabacee (pisello, fagiolo, fava, cece, lupino). Il pisello è un **ottimo predecessore** di tutte le verdure azotofile (cavoli, solanacee, mais)

## Note clima costiero
La costa centro-italiana è ideale per piselli **autunno-vernini**: si semina a ottobre-novembre, la pianta cresce con gli inverni miti, fiorisce a febbraio-marzo e produce ad aprile. Si evita così sia il freddo intenso (che danneggia i fiori) sia il caldo precoce (che blocca la produzione). Pisello e fava sono i due legumi tipici dell'orto invernale-primaverile della costa centro-meridionale.

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
- [[autunno]] · [[inverno]] · [[primavera]]

#pianta #orticola #fabacee #legumi
