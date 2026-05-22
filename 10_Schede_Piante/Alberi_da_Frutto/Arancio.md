---
tipo: scheda_pianta
categoria: albero_da_frutto
nome_comune: Arancio
nome_scientifico: Citrus sinensis (arancio dolce) / Citrus aurantium (arancio amaro)
famiglia: Rutaceae
periodo_raccolta: "Novembre-Aprile (secondo varietà)"
periodo_potatura: "Marzo (post-raccolta)"
forma_allevamento: "Vaso globoso"
portainnesto_consigliato: "Arancio amaro (rustico) o citrange"
esposizione: sole pieno (riparato da venti freddi)
resistenza_salsedine: alta
resistenza_freddo: "-5°C (-6°C alcune varietà); danni sotto -7°C"
entrata_in_produzione_anni: 4
autofertile: true
impollinatori_richiesti: "Nessuno"
sesto_impianto_m: "5 × 5"
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Conca_e_Solco]]"
  - "[[Subirrigazione]]"
tags:
  - albero
  - sempreverde
  - rutaceae
  - agrumi
---

# 🍊 Arancio

> Famiglia: `=this.famiglia` · Raccolta: `=this.periodo_raccolta` · Potatura: `=this.periodo_potatura`

## Caratteristiche
Sempreverde a chioma globosa, fiori bianchi profumatissimi (zagara). Più resistente al freddo del limone, ma meno del mandarino. Tre categorie principali per maturazione: **bionde precoci** (Navelina, Washington Navel, Navel Late, raccolta novembre-marzo), **bionde tardive** (Valencia Late, fino a maggio), **pigmentate / rosse** (Sanguinello, Moro, Tarocco, tipiche di Sicilia, raccolta dicembre-aprile, polpa rosso scuro per pigmenti antocianici che si sviluppano con sbalzi termici notte/giorno). Esiste anche l'**arancio amaro** (C. aurantium), usato principalmente come portainnesto e per marmellate.

## Impianto
- Esposizione: sole pieno, riparato dai venti freddi del nord
- Sesto: 5 × 5 m
- Portainnesto: arancio amaro o citrange
- Periodo: primavera o autunno, mai estate piena
- Buca: 60 × 60 × 60 cm, drenaggio essenziale
- Ammendanti: compost maturo, cornunghia
- Tutore i primi anni

## Cura annuale
- Concimazione: come limone, 3 distribuzioni (febbraio, maggio, settembre). Carenze tipiche di ferro e magnesio in terreni calcarei
- Irrigazione: regolare in primavera-estate. Stress idrico = caduta frutti
- Pacciamatura al piede
- Spollonatura del portainnesto

## Potatura
- Periodo: marzo, dopo la raccolta
- Tipo: come limone, vaso globoso aperto. Tagli moderati di sfoltimento, eliminazione succhioni, rami secchi
- Mai potature drastiche

## Impollinazione e produzione
- Autofertile, non servono impollinatori
- Fioritura: aprile-maggio (zagara, bellissima e profumatissima)
- Tempo dalla fioritura al frutto maturo: 8-12 mesi
- Entrata in produzione: 4-5 anni
- Produzione adulta: 50-200 kg per pianta

## Avversità tipiche
- Le stesse del limone: cocciniglie, minatrice serpentina, mosca della frutta, afidi, gommosi
- **Tristezza degli agrumi** (CTV, virus): più frequente su arancio. Lavorare con materiale certificato virus-esente. Vettori afidi
- **Clorosi ferrica**: tipico su terreni calcarei. Chelati di ferro
- **Maculatura nera** in autunno (fungina): poltiglia bordolese

## Resistenza al contesto costiero
Salsedine ben tollerata. Resistenza al freddo intermedia tra limone e mandarino: tollera -5°C breve, danni sotto -7°C. La costa centro-italiana è zona di confine settentrionale per l'arancio: produce bene in zone protette (esposizione sud, vicino al mare, riparo dai venti freddi). Le zone storicamente "garantite" sono quelle del Sud + costa amalfitana, sorrentina, gargano. Sulle coste marchigiana, abruzzese, romagnola conviene impianti in zone protette o coltura in vaso. La varietà Washington Navel è tra le più tollerantii al freddo.

## Raccolta e conservazione
- A maturazione visiva (colore arancio pieno) e gustativa (assaggiare). Gli aranci non maturano dopo la raccolta come banane o meloni: vanno staccati maturi
- **Si possono lasciare sull'albero per mesi**: ottima riserva fresca in pianta
- Forbice, mai strappare
- Conservazione: 2-3 settimane in fresco, 1 mese in frigo
- Trasformazione: spremuta (consumo immediato per vitamine), marmellata, scorze candite, liquori (arancello)

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Irrigazione_a_Conca_e_Solco]] · [[Subirrigazione]]
- [[primavera]] · [[autunno]] · [[inverno]]

#pianta #albero_da_frutto #sempreverde #agrumi
