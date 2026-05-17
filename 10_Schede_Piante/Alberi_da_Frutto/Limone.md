---
tipo: scheda_pianta
categoria: albero_da_frutto
nome_comune: Limone
nome_scientifico: Citrus limon
famiglia: Rutaceae
periodo_raccolta: "Tutto l'anno (varietà rifiorenti)"
periodo_potatura: "Marzo-Aprile (post-raccolta principale)"
forma_allevamento: "Vaso globoso"
portainnesto_consigliato: "Arancio amaro (più rustico, resistente a freddo e calcare); citrange (alternativa)"
esposizione: sole pieno (riparato da venti freddi)
resistenza_salsedine: alta
resistenza_freddo: "-3°C (massimo); danni gravi sotto 0°C prolungato"
entrata_in_produzione_anni: 3
autofertile: true
impollinatori_richiesti: "Nessuno"
sesto_impianto_m: "4 × 4"
tags:
  - albero
  - sempreverde
  - rutaceae
  - agrumi
---

# 🍋 Limone

> Famiglia: `=this.famiglia` · Raccolta: `=this.periodo_raccolta` · Potatura: `=this.periodo_potatura`

## Caratteristiche
Sempreverde rifiorente (fa fiori e frutti in più momenti dell'anno), tipico delle coste mediterranee meridionali e centrali. Varietà classiche italiane: **Femminello comune** (la più diffusa, rifiorente, frutti tutto l'anno), **Femminello Siracusano** IGP, **Sorrentino** IGP, **Costa d'Amalfi** IGP, **Interdonato** (precoce, bella forma), **Eureka** (varietà moderna molto produttiva). I frutti raccolti in periodi diversi hanno nomi tradizionali: **primofiore** (raccolto ottobre-aprile), **bianchetto** (aprile-giugno, da seconda fioritura), **verdello** (luglio-settembre, frutto rifiorito che resta verde per il caldo).

## Impianto
- Esposizione: sole pieno, **riparato da venti freddi del nord**. Esposizione sud o sud-est ideale
- Sesto: 4 × 4 m in pieno campo; in vaso minimo 40 litri per pianta giovane
- Portainnesto: **arancio amaro** classico (rustico, tollera calcare e freddo), citrange per terreni molto calcarei
- Periodo: primavera (marzo-aprile) o autunno (ottobre); evitare luglio-agosto
- Buca: 60 × 60 × 60 cm, drenaggio essenziale (gli agrumi temono ristagni)
- Ammendanti: terriccio + compost maturo + sabbia se argilloso. Aggiungere lupini macinati o cornunghia per nutrizione lenta
- Tutore i primi 2-3 anni

## Cura annuale
- Concimazione: 3 distribuzioni l'anno (febbraio, maggio, settembre) con concime per agrumi o compost + cornunghia/sangue di bue. Carenza tipica: ferro (clorosi ferrica = foglie gialle con nervature verdi), si corregge con chelati di ferro o terriccio acido al piede
- Irrigazione: regolare in primavera-estate. Mai stress idrici (caduta foglie e fiori). Mai sulle foglie. Pacciamatura organica al piede
- Spollonatura: eliminare i polloni dal portainnesto (foglie diverse, spesso più scure e con tre foglioline)
- In vaso: rinvaso ogni 2-3 anni a marzo, sostituzione strato superficiale annuale

## Potatura
- Periodo: marzo-aprile, dopo la raccolta principale
- Tipo: vaso globoso aperto al centro, **mai potature drastiche** (l'agrume mal tollera grossi tagli)
- Tagli: succhioni verticali, rami secchi, rami che si incrociano, sfoltimento dell'interno per arieggiare
- **Mai cimare** i rami portanti (riducono produzione)
- Possibile potatura di pulizia leggera anche a settembre-ottobre

## Impollinazione e produzione
- Autofertile, non servono impollinatori
- Fioritura principale: marzo-aprile + rifioriture (giugno e settembre)
- Tempo dalla fioritura al frutto maturo: 6-9 mesi (verdelli più rapidi, 4 mesi)
- Entrata in produzione: 3-4 anni
- Produzione adulta: 100-300 kg per pianta

## Avversità tipiche
- **Cocciniglia bianca dell'agrumeto** (Aspidiotus nerii) e **cotonosa**: scudetti bianchi sulle foglie e rami. Olio bianco minerale in inverno, sapone molle, predatori (coccinelle Cryptolaemus, Rodolia cardinalis per la cocciniglia cotonosa)
- **Minatrice serpentina** (Phyllocnistis citrella): gallerie chiare sulle foglie giovani. Trappole feromoni, Bacillus thuringiensis
- **Mosca della frutta** (Ceratitis capitata): trappole proteiche, caolino
- **Afidi**: sapone molle
- **Gommosi** (Phytophthora): essudazione gomma al colletto. Innesti alti, evitare ristagni e bagnatura del colletto
- **Marciume radicale**: drenaggio essenziale
- **Clorosi ferrica**: comune su terreni calcarei, foglie gialle. Chelati di ferro, ammendare con torba acida
- **Frutti spaccati**: stress idrici

## Resistenza al contesto costiero
Salsedine tollerata molto bene. **Il vero limite è il freddo**: il limone resiste solo a -3°C (-4°C breve), oltre subisce danni gravi (caduta foglie, mortalità rami, frutti rovinati). La costa centro-italiana è zona di confine: in zone protette (vicino mare, esposte sud, riparate da vento freddo del nord) cresce bene; in pianura interna o esposta tramontana richiede coperture invernali (tessuto non tessuto) o coltura in vaso da svernare in serra o in casa. La tradizione storica dei "giardini di limoni" della costa amalfitana, sorrentina, ligure è una indicazione di dove la coltura è più sicura.

## Raccolta e conservazione
- Si raccoglie a maturazione visiva (colore giallo pieno), ma in genere il limone si "stocca sull'albero" e si raccoglie alla bisogna
- Forbice, mai strappare (rovina la pianta)
- Conservazione: 2-3 settimane in fresco, freschi in frigo 1 mese. La buccia sottile è la più aromatica
- Trasformazione: limoncello (alcol e zucchero, buccia), marmellata, limoni sotto sale (cucina marocchina), succo congelato in cubetti

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
- [[primavera]] · [[autunno]] · [[inverno]]

#pianta #albero_da_frutto #sempreverde #agrumi
