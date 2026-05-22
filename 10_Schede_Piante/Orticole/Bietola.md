---
tipo: scheda_pianta
categoria: orticola
nome_comune: Bietola
nome_scientifico: Beta vulgaris var. cicla / var. conditiva
famiglia: Amaranthaceae
ciclo: biennale (coltivata come annuale)
periodo_semina: "Marzo-Settembre (scalare)"
periodo_raccolta: "Tutto l'anno con scalari"
distanza_pianta_cm: 25
distanza_fila_cm: 50
profondita_semina_cm: 2
esposizione: sole pieno o mezz'ombra
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: medio
difficolta: 1
consociazioni_buone:
  - Cavolo
  - Lattuga
  - Cipolla
  - Fagiolo nano
consociazioni_da_evitare:
  - Spinacio (stessa famiglia)
  - Mais
successioni_buone:
  - Legumi
  - Solanacee
predecessori_da_evitare:
  - Bietola / barbabietola / spinacio
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - foglia
  - radici
---

# 🥬 Bietola

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Una stessa specie con due forme principali: **bietola da costa** (Beta vulgaris var. cicla, coltivata per le foglie e le coste grosse e bianche o colorate) e **barbabietola da orto** (var. conditiva, coltivata per la radice tonda). Esistono anche varianti a coste rosse, gialle, rainbow (multicolore) molto decorative. Pianta facile, robusta, tollera bene terreni difficili e salinità.

## Semina e trapianto
- Semina diretta o in semenzaio. Il "seme" è in realtà un glomerulo con 2-4 semini: emergono più piantine, vanno diradate
- Diretta da marzo a settembre, ogni 30-40 giorni per raccolta scalare
- Profondità: 2 cm
- Distanze: 25-30 cm sulla fila, 50 cm tra le file
- Diradamento a 8-10 cm tra le piantine, conservando le più vigorose

## Cura
- Esposizione: sole pieno, ma tollera bene mezz'ombra (utile sotto pomodori o mais)
- Irrigazione: regolare, ama l'umidità ma tollera periodi secchi una volta affrancata
- Pacciamatura organica utile in estate
- Concimazione: compost in fase di preparazione. La bietola non è molto esigente
- Coste e foglie: si raccolgono progressivamente dalla più esterna alla più interna, la pianta continua a produrre per mesi
- Per la barbabietola da radice: stessa coltivazione, ma niente raccolta progressiva, si aspetta che la radice raggiunga 6-10 cm di diametro

## Avversità tipiche
- **Cercospora**: macchie circolari grigie con bordo rossastro sulle foglie. Aerare, eliminare foglie infette, rame se necessario
- **Oziorrinco**: rosure semicircolari sui bordi delle foglie. Trappole, nematodi
- **Afide nero della fava**: colonie nere sotto le foglie giovani. Sapone molle, coccinelle
- **Andata a seme**: stress idrico o termico, pianta sale a fiore e foglie diventano coriacee
- Generalmente coltura molto tollerante alle avversità

## Raccolta e conservazione
- **Bietola da costa**: foglia per foglia, partendo dalle esterne, la pianta dura 6+ mesi
- **Barbabietola da orto**: 80-100 giorni dalla semina, quando la radice è 6-10 cm
- Conservazione foglie: 3-5 giorni in frigo. Sbianchite e congelate ottime
- Conservazione barbabietole: in sabbia umida in cantina fresca, durano mesi. Sottaceti, lattofermentate (kvass)

## Consociazioni e rotazioni
- **Compagne**: cavolo (sfrutta lo spazio sotto), lattuga, cipolla, fagiolo nano (azoto)
- **Da evitare**: spinacio (stessa famiglia, stessi parassiti), mais (competizione idrica)
- **Rotazione**: 3 anni prima di tornare con bietola, barbabietola o spinacio

## Note clima costiero
Una delle colture **più tolleranti alla salinità** in assoluto (la barbabietola da zucchero discende da Beta maritima, che vive sulle spiagge): la bietola da costa è una scelta naturale per orto costiero. Cresce praticamente tutto l'anno sulla costa centro-italiana, anche in pieno inverno mite. Estremamente robusta a vento, salsedine, umidità marina.

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
- [[primavera]] · [[estate]] · [[autunno]] · [[inverno]]

#pianta #orticola #foglia
