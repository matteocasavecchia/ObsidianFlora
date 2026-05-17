---
tipo: scheda_pianta
categoria: orticola
nome_comune: Fava
nome_scientifico: Vicia faba
famiglia: Fabaceae
ciclo: annuale
periodo_semina: "Ottobre-Dicembre (costa); Febbraio (al Nord)"
periodo_raccolta: "Aprile-Giugno"
distanza_pianta_cm: 15
distanza_fila_cm: 60
profondita_semina_cm: 5
esposizione: sole pieno
ph_min: 6.5
ph_max: 8.0
fabbisogno_idrico: medio
difficolta: 1
consociazioni_buone:
  - Mais
  - Patata
  - Bietola
  - Spinacio
  - Carciofo
consociazioni_da_evitare:
  - Cipolla
  - Aglio
  - Porro
successioni_buone:
  - Solanacee
  - Cucurbitacee
  - Cavoli
predecessori_da_evitare:
  - Fabacee
tags:
  - pianta
  - orticola
  - fabacee
  - legumi
---

# 🫘 Fava

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Legume tradizionale dell'orto mediterraneo, coltivato dall'antichità. Pianta robusta a portamento eretto (60-150 cm), con baccelli grossi e carnosi contenenti grossi semi piatti. Varietà: aguadulce supersimonia (grande, classica), fava di Leonforte, fava cottoia di Modica (siciliane, baccelli enormi), fava nera (varietà rustica). Anche varietà nane (60 cm) e a baccelli più piccoli. Fissa azoto e arricchisce il terreno: ottima precoltura per esigenti.

## Semina e trapianto
- Solo semina diretta
- **Costa centro-italiana**: ottobre-dicembre (la fava ama il freddo moderato). Resiste fino a -5°C, gli inverni miti della costa la favoriscono
- Profondità: 5 cm (seme grosso)
- Distanze: 15-20 cm sulla fila, 60 cm tra le file. A postarella si possono mettere 2 semi per buca
- Buca senza letame, solo compost

## Cura
- Esposizione: sole pieno
- Irrigazione: pochissima, vive di pioggia. In primavera secca, qualche bagnatura
- **Cimatura della cima vegetativa** quando compaiono i primi baccelli: si tagliano i 10 cm più alti. Tre effetti: stimola produzione baccelli inferiori, riduce attacco afide nero (che predilige le cime tenere), evita allettamento. Le cime cimate sono ottime in cucina (saltate in padella)
- Pacciamatura organica utile
- Concimazione: compost in preparazione, niente più
- Sostegni leggeri se necessario per piante alte: corda perimetrale all'altezza di metà pianta

## Avversità tipiche
- **Afide nero della fava** (Aphis fabae): colonia massiccia sulle cime tenere. La cimatura è la migliore prevenzione. Sapone molle, coccinelle
- **Tonchio della fava** (Bruchus rufimanus): coleottero che depone uova sui baccelli, larve nei semi. Raccolta tempestiva, conservazione in congelatore 48 ore prima di rimettere a granella
- **Ruggine** (Uromyces viciae-fabae): pustole arancioni sulle foglie a fine ciclo. Rame in casi gravi, ma di solito tollerabile
- **Cioccolato** (Botrytis fabae): macchie marroni sulle foglie. Aerare, evitare densità eccessiva

## Raccolta e conservazione
- **Fave fresche** (da sgranare verdi): quando i baccelli sono ben pieni ma il seme ancora tenero, "occhio bianco" non ancora nero
- **Fave secche** (granella): aspettare che baccelli e piante secchino in campo, raccogliere intere piante, sgranare in seconda battuta
- Le **piante secche** sono ottimo materiale per pacciamatura o compost (ricche di azoto fissato)
- Conservazione fresche: 1 settimana in frigo. Conservazione secca: barattoli ermetici, 2+ anni

## Consociazioni e rotazioni
- **Compagne**: mais (sale insieme), patata, bietola, spinacio, carciofo
- **Da evitare**: Amaryllidaceae (cipolla, aglio, scalogno, porro: inibiscono noduli azotofissatori)
- **Rotazione**: 4 anni per fabacee. Ottimo predecessore per cavoli, solanacee, mais, cereali

## Note clima costiero
La fava è **la** coltura tradizionale dell'inverno mediterraneo costiero italiano. Si semina a novembre, supera gli inverni miti senza problemi, produce a marzo-aprile in concomitanza con il pecorino fresco (primo maggio: fave e pecorino). Tollera bene salsedine. Le piante lasciate seccare a giugno sono un'ottima copertura del suolo + arricchimento azoto + materiale per pacciamatura estiva.

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
- [[autunno]] · [[inverno]] · [[primavera]]

#pianta #orticola #fabacee #legumi
