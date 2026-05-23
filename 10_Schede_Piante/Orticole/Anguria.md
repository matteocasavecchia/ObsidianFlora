---
tipo: scheda_pianta
categoria: orticola
nome_comune: Anguria (Cocomero)
nome_scientifico: Citrullus lanatus
famiglia: Cucurbitaceae
ciclo: annuale
periodo_semina: "Aprile (semenzaio caldo); Maggio (diretta)"
periodo_raccolta: "Luglio-Settembre"
distanza_pianta_cm: 100
distanza_fila_cm: 200
profondita_semina_cm: 3
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.0
fabbisogno_idrico: alto e regolare (basso a fine ciclo)
difficolta: 3
consociazioni_buone:
  - Mais
  - Fagiolo
  - Tagete
  - Ravanello
consociazioni_da_evitare:
  - Altre cucurbitacee
  - Patata
successioni_buone:
  - Legumi
  - Insalate
predecessori_da_evitare:
  - Cucurbitacee
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Subirrigazione]]"
tags:
  - pianta
  - orticola
  - cucurbitacee
---

# 🍉 Anguria

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Cucurbitacea strisciante con frutti tondi o ovali, polpa rossa (o gialla, arancione in varietà particolari), profumata e zuccherina. Varietà: crimson sweet (rotonda, polpa rossa, classica), sugar baby (piccola, precoce), Charleston Grey (allungata), gialla del mare (polpa gialla), Black Diamond. Coltura **molto vorace di spazio**: una pianta occupa 2-4 m². Per piccoli orti esistono varietà nane o compatte.

## Semina e trapianto
- Semenzaio caldo (22-26°C) da metà aprile, vasetti grandi
- Semina diretta da maggio sulla costa (terreno sopra 18°C)
- Profondità: 3 cm
- Distanze: 100 cm sulla fila, 200 cm tra le file. A postarella 2-3 semi diradati a una pianta
- Buca generosa con compost o letame maturo

## Cura
- Esposizione: sole pieno totale, l'anguria è la più termofila delle cucurbitacee
- Irrigazione: abbondante e regolare durante crescita e formazione frutti. **Ridurre drasticamente** quando i frutti sono quasi maturi (2-3 settimane prima della raccolta): aumenta zuccheri. Bagnare al piede a goccia, mai sulle foglie
- Pacciamatura organica spessa, mantiene umidità e tiene i frutti puliti
- Concimazione: macerato di consolida in fioritura
- **Sotto i frutti**: tavoletta, pacciame asciutto o teglia per evitare marciumi a contatto con il terreno

## Avversità tipiche
- **Oidio**: zolfo, bicarbonato, equiseto
- **Peronospora**: rame
- **Afide del melone**: sapone molle, predatori
- **Mal bianco delle cucurbitacee**: aerare il filare
- **Marciume del frutto** (Botrytis, Phytophthora): sollevare i frutti, ridurre umidità
- **Cracking**: irrigazione irregolare

## Raccolta e conservazione
- Indici di maturazione (la parte più difficile dell'anguria):
  1. **Viticcio** vicino al peduncolo del frutto: secco e marrone = pronto
  2. **Macchia gialla** dove il frutto poggia a terra: ben gialla = maturo
  3. **Suono "vuoto"** battendo con le nocche
  4. **Buccia opaca**, non più lucida
- Tagliare con coltello, 5 cm di peduncolo
- Conservazione: 1-2 settimane in cantina fresca, 1 settimana in frigo dopo taglio
- Trasformazione: marmellata di buccia (parte bianca), succo, sorbetto

## Consociazioni e rotazioni
- **Compagne**: mais (ombra parziale, sostegno per le foglie), fagiolo (azoto), tagete, ravanello
- **Da evitare**: altre cucurbitacee, patata
- **Rotazione**: 3-4 anni per cucurbitacee

## Note clima costiero
Coltura **ideale per costa centro-italiana**: estate calda e secca = anguria perfetta. Tolleranza salsedine media. Esige spazio (planning attento nel piccolo orto). I venti forti possono spezzare le foglie grandi: in zone esposte conviene un frangivento o impianto a ridosso di una rete-mais.

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Subirrigazione]]
- [[primavera]] · [[estate]]

#pianta #orticola #cucurbitacee
