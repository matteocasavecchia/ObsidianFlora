---
tipo: scheda_pianta
categoria: orticola
nome_comune: Aglio
nome_scientifico: Allium sativum
famiglia: Amaryllidaceae
ciclo: annuale
periodo_semina: "Ottobre-Dicembre (principale); Febbraio-Marzo"
periodo_raccolta: "Giugno-Luglio"
distanza_pianta_cm: 12
distanza_fila_cm: 25
profondita_semina_cm: 3
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: basso-medio
difficolta: 1
consociazioni_buone:
  - Pomodoro
  - Cetriolo
  - Lattuga
  - Carota
  - Fragola
  - Rosa
consociazioni_da_evitare:
  - Legumi (pisello, fagiolo, fava)
  - Cavolo
successioni_buone:
  - Solanacee
  - Cucurbitacee
predecessori_da_evitare:
  - Amaryllidaceae
tags:
  - pianta
  - orticola
  - amaryllidaceae
  - bulbi
---

# 🧄 Aglio

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Bulbo composto da spicchi (bulbilli) attorno a un asse centrale. Coltivato sempre per propagazione vegetativa (mai da seme). Due tipologie principali: **aglio a coltura autunnale** (piantato in autunno, raccolta giugno-luglio: rese maggiori, conservazione migliore) e **aglio primaverile** (piantato gennaio-marzo, raccolta più precoce ma rese inferiori). Varietà italiane: aglio rosso di Sulmona, di Nubia (rosso siciliano), bianco di Vessalico, bianco piacentino. L'aglio nostrale conservato per la semina è sempre migliore di quello da supermercato (spesso trattato per non germogliare).

## Semina e trapianto
- Selezionare gli **spicchi più grossi ed esterni**, scartare quelli centrali piccoli
- Piantare con la punta in alto, a 3-4 cm di profondità
- Distanze: 12-15 cm sulla fila, 25 cm tra le file
- **Periodo costa centro-italiana**: ottobre-dicembre per autunnale (la migliore), febbraio per primaverile

## Cura
- Esposizione: sole pieno
- Irrigazione: praticamente nessuna se piantato in autunno (basta la pioggia). Solo in caso di primavera molto secca, qualche bagnatura. Mai bagnare a fine ciclo (= bulbi marci)
- Pacciamatura sottile organica utile
- Concimazione: compost in preparazione, niente di più
- Sarchiature regolari, l'aglio detesta erbacce
- **Scapo florale** (asticella centrale che alcune varietà producono): si elimina (scapando) per non sprecare energia. Gli scapi sono commestibili e gustosi

## Avversità tipiche
- **Marciume bianco** (Sclerotium cepivorum): come per cipolla, persistente nel suolo. Rotazione lunga
- **Ruggine** (Puccinia allii): pustole arancioni sulle foglie. Aerare il filare, rame in casi gravi
- **Mosca dell'aglio**: rara, simile alla mosca della cipolla
- **Cipollino** (acaro): foglie deformate. Eliminare piante colpite
- Generalmente coltura molto robusta, tra le più facili dell'orto

## Raccolta e conservazione
- Quando le foglie sono ingiallite per metà-due terzi (giugno-luglio per autunnale)
- Estrarre con forca, lasciare in campo o all'ombra 2-3 giorni
- **Curing**: 2-3 settimane in luogo arieggiato e ombreggiato, mai al sole diretto (cuoce il bulbo)
- Tagliare radici e foglie quando ben asciutto, oppure intrecciare le foglie e appendere
- Conservazione: 8-12 mesi in luogo fresco e asciutto. Trasformazione: aglio nero (fermentazione lunga), sott'olio, in polvere

## Consociazioni e rotazioni
- **Compagne**: pomodoro (effetto antifungino tradizionale), cetriolo, lattuga, carota, fragola. **Rosa** (l'aglio è il classico compagno della rosa, allontana afidi e malattie)
- **Da evitare**: legumi, cavoli
- **Rotazione**: 4-5 anni per Amaryllidaceae

## Note clima costiero
Coltura perfetta per costa centro-italiana. Sopporta benissimo gli inverni miti, ama l'estate calda e secca per asciugare i bulbi. Tolleranza salsedine alta. Conviene piantare in autunno (ottobre-novembre): le radici si sviluppano durante l'inverno mite, in primavera la pianta parte già robusta. La raccolta a fine giugno coincide con il caldo asciutto che facilita curing.

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
- [[autunno]] · [[inverno]] · [[estate]]

#pianta #orticola #amaryllidaceae #bulbi
