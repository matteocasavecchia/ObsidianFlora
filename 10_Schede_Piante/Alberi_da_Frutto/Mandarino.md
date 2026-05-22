---
tipo: scheda_pianta
categoria: albero_da_frutto
nome_comune: Mandarino
nome_scientifico: Citrus reticulata
famiglia: Rutaceae
periodo_raccolta: "Novembre-Febbraio"
periodo_potatura: "Marzo (post-raccolta)"
forma_allevamento: "Vaso globoso"
portainnesto_consigliato: "Arancio amaro o citrange"
esposizione: sole pieno (riparato da venti freddi)
resistenza_salsedine: alta
resistenza_freddo: "-5°C / -7°C secondo cultivar (più del limone, intermedio)"
entrata_in_produzione_anni: 3
autofertile: true
impollinatori_richiesti: "Nessuno (alcune varietà con semi richiedono impollinazione incrociata)"
sesto_impianto_m: "4 × 4"
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

# 🍊 Mandarino

> Famiglia: `=this.famiglia` · Raccolta: `=this.periodo_raccolta` · Potatura: `=this.periodo_potatura`

## Caratteristiche
Sempreverde più piccolo dell'arancio, frutti a buccia sottile facilmente sbucciabile. Categoria che include diverse specie e ibridi: **mandarino comune** (con semi, profumatissimo), **clementina** (Citrus × clementina, senza semi, frutti più piccoli, varietà popolari Comune, Tardivo, Avana, Hernandina), **tangerino** (mandarino × arancio, Citrus tangerina), **satsuma** (giapponese, senza semi, molto resistente al freddo, raccolta ottobre-novembre). Per la costa centro-italiana le scelte più adatte sono **clementina comune** e **satsuma**, più robuste e con minor esigenza di calore.

## Impianto
- Esposizione: sole pieno, riparato dai venti freddi
- Sesto: 4 × 4 m
- Portainnesto: arancio amaro o citrange
- Periodo: primavera o autunno
- Buca: 60 × 60 × 60 cm, drenaggio essenziale
- Ammendanti: compost, cornunghia
- Tutore i primi 2-3 anni

## Cura annuale
- Concimazione: come gli altri agrumi
- Irrigazione: regolare. Il mandarino è leggermente più resistente alla siccità di limone e arancio, ma comunque non sopporta stress
- Pacciamatura
- Spollonatura del portainnesto

## Potatura
- Come per limone e arancio: marzo, sfoltimenti moderati
- Il mandarino tende a "caricare" molto: si possono diradare i frutti in eccesso per evitare l'alternanza di produzione (un anno carico, uno scarico)

## Impollinazione e produzione
- Autofertile per la maggior parte delle varietà
- Le clementine senza semi sono **partenocarpiche** (non hanno bisogno di impollinazione)
- Fioritura: aprile-maggio
- Tempo dalla fioritura al frutto: 7-9 mesi
- Entrata in produzione: 3-4 anni
- Produzione adulta: 50-150 kg per pianta

## Avversità tipiche
- Le stesse degli altri agrumi: cocciniglie, minatrice serpentina, afidi, mosca della frutta, gommosi, clorosi ferrica
- **Ragnetto rosso degli agrumi** (Panonychus citri): più frequente sul mandarino. Predatori (Phytoseiulus), olio bianco
- **Tripidi**: macchie argentate
- **Frutti spaccati**: stress idrici, comune dopo siccità + pioggia abbondante

## Resistenza al contesto costiero
Salsedine ben tollerata. **Resistenza al freddo intermedia**: clementina -5°C, satsuma fino a -8°C (la più resistente degli agrumi commerciali). Per costa centro-italiana il mandarino satsuma è la **scelta più sicura** se si vuole un agrume produttivo. Cresce bene anche nelle zone più settentrionali della costa adriatica.

## Raccolta e conservazione
- A colore pieno della varietà. Diversamente dall'arancio, il mandarino **non si conserva sull'albero** oltre la maturazione: tende a deteriorare la qualità interna (frutti "vuoti", buccia separata dalla polpa)
- Raccolta tempestiva, forbice
- Conservazione: 1-2 settimane in fresco, 3-4 settimane in frigo
- Trasformazione: marmellata, mandarinetto, scorze candite, succhi

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
