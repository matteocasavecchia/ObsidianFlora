---
tipo: scheda_pianta
categoria: orticola
nome_comune: Melanzana
nome_scientifico: Solanum melongena
famiglia: Solanaceae
ciclo: annuale
periodo_semina: "Febbraio-Marzo (semenzaio caldo); Maggio (trapianto)"
periodo_raccolta: "Luglio-Ottobre"
distanza_pianta_cm: 60
distanza_fila_cm: 80
profondita_semina_cm: 0.5
esposizione: sole pieno
ph_min: 6.0
ph_max: 6.8
fabbisogno_idrico: alto e regolare
difficolta: 3
consociazioni_buone:
  - Fagiolo
  - Basilico
  - Tagete
  - Timo
  - Lattuga
consociazioni_da_evitare:
  - Altre solanacee (pomodoro, peperone, patata)
  - Finocchio
successioni_buone:
  - Legumi
  - Cereali
predecessori_da_evitare:
  - Solanacee
tags:
  - pianta
  - orticola
  - solanacee
---

# 🍆 Melanzana

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
La più termofila delle solanacee, adora il clima mediterraneo costiero. Pianta arbustiva che può raggiungere 1-1,2 metri. Varietà italiane classiche: violetta lunga, tonda romanesca, prosperosa, perlina (piccola e dolce), nera di Napoli, listada de Gandia (bianco-viola striata, dolcissima). Le bianche e le striate sono spesso più digeribili e meno amare.

## Semina e trapianto
- Germinazione lenta: serve calore costante 24-28°C, semenzaio scaldato da fine febbraio
- 8-10 settimane in semenzaio fino al trapianto
- Trapianto solo quando le minime stanno stabilmente sopra 14°C, sulla costa metà-fine maggio
- Distanze: 60 cm sulla fila, 80 cm tra le file
- Buca generosa con compost o letame maturo

## Cura
- Esposizione: sole pieno, ama il caldo intenso
- Irrigazione: regolare e abbondante a goccia, mai sulle foglie. La pianta soffre molto gli sbalzi idrici (fiori che cadono, frutti deformi)
- Pacciamatura organica fondamentale per umidità costante
- Concimazione: macerato di consolida o ortica in copertura ogni 3 settimane dalla fioritura
- Sostegno: tutore singolo per ogni pianta, le branche cariche di frutti si spezzano facilmente
- Cimatura: a 30-40 cm dal suolo si cima la cima centrale per favorire ramificazioni laterali. Si tengono 3-4 branche principali, si eliminano le altre

## Avversità tipiche
- **Dorifora** (coleottero della patata): adulti e larve striate gialle-nere divorano le foglie. Raccolta manuale precoce, Bacillus thuringiensis tenebrionis sulle larve giovani
- **Ragnetto rosso**: caldo secco favorisce. Nebulizzazioni d'acqua, predatori naturali (Phytoseiulus)
- **Oziorrinco**: rosure semicircolari sui bordi delle foglie. Trappole, nematodi entomopatogeni nel terreno per le larve
- **Cimici**: macerato di aglio, raccolta manuale
- **Verticilliosi e fusariosi**: funghi del suolo che persistono per anni, motivo per cui le solanacee non vanno mai rimesse nella stessa parcella per almeno 3-4 anni. Sintomi: avvizzimento, ingiallimento progressivo a partire dalle foglie basse
- **Oidio**: zolfo bagnabile
- **Marciume apicale**: come pomodoro, gestione idrica e calcio

## Raccolta e conservazione
- Quando il frutto ha colore pieno e lucido (la lucentezza è l'indice chiave: se diventa opaco, è troppo maturo, semi sviluppati e amaro)
- Pressione leggera con il pollice: deve cedere un po' e tornare elastico
- Si taglia con il picciolo, mai si strappa
- Conservazione: 4-7 giorni in fresco (non frigo, sotto i 10°C subiscono danni da freddo). Trasformazione: sott'olio, sott'aceto, parmigiana, caponata, essiccate
- La pianta produce in continuazione per 3-4 mesi se mantenuta in salute

## Consociazioni e rotazioni
- **Compagne**: fagiolo (azoto), basilico (aroma e parassiti), tagete (nematodi del terreno, importante per le solanacee), timo, lattuga (sfrutta lo spazio in primavera)
- **Da evitare**: altre solanacee (rotazione), finocchio
- **Rotazione**: minimo 3-4 anni prima di rimettere solanacee. Buona dopo cereali e legumi

## Note clima costiero
La coltura per eccellenza del clima costiero centro-meridionale: ama il caldo, tollera bene la salsedine, soffre solo il freddo (sotto i 12°C la fioritura si blocca). Il vento marino può ridurre l'impollinazione (i fiori vengono spazzolati): in zone molto ventose conviene un piccolo frangivento o impianto a ridosso di muretti. L'umidità notturna estiva favorisce oidio: ventilare il filare.

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
- [[primavera]] · [[estate]]

#pianta #orticola #solanacee
