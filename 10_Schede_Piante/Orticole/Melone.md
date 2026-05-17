---
tipo: scheda_pianta
categoria: orticola
nome_comune: Melone
nome_scientifico: Cucumis melo
famiglia: Cucurbitaceae
ciclo: annuale
periodo_semina: "Aprile (semenzaio caldo); Maggio (diretta)"
periodo_raccolta: "Luglio-Settembre"
distanza_pianta_cm: 80
distanza_fila_cm: 150
profondita_semina_cm: 2
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.0
fabbisogno_idrico: medio-alto (basso a fine ciclo)
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
tags:
  - pianta
  - orticola
  - cucurbitacee
---

# 🍈 Melone

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Cucurbitacea strisciante o rampicante con frutti rotondi/ovali profumatissimi. Tipi principali: **retato** (cantalupo) a polpa arancione (classico in Italia: melone di Cavaillon, retato della costa), **liscio** giallo a polpa bianca (melone d'inverno, melone gialletto), melone "verde" o "noce". Esigenze simili all'anguria, ma con frutti più piccoli e maturazione più rapida.

## Semina e trapianto
- Semenzaio caldo da metà aprile in vasetti grandi
- Diretta da maggio sulla costa
- Profondità: 2 cm
- Distanze: 80-100 cm sulla fila, 150 cm tra le file
- Buca con compost o letame maturo
- A postarella 2-3 semi diradati

## Cura
- Esposizione: sole pieno
- Irrigazione: regolare in crescita e fioritura. **Ridurre 2-3 settimane prima della raccolta** per concentrare zuccheri. Mai sulle foglie
- Pacciamatura organica indispensabile
- Concimazione: macerato di consolida in fioritura
- **Cimatura**: si cima la pianta sopra la 4ª-5ª foglia per favorire ramificazioni laterali (porteranno i fiori femminili). Sui rami secondari, cimare dopo il frutto + 2-3 foglie. Tecnica facoltativa, aumenta resa e dimensione frutti
- Sotto i frutti: tavoletta o pacciame asciutto

## Avversità tipiche
- **Oidio**: il principale problema, soprattutto in agosto. Zolfo, bicarbonato, equiseto
- **Peronospora**: rame
- **Afide del melone** (Aphis gossypii): sapone molle
- **Tripidi**: tappezzeria gialla sulle foglie
- **Fusariosi**: avvizzimento, rotazione lunga
- **Frutti senza sapore**: stress idrico in maturazione, sole insufficiente, varietà sbagliata

## Raccolta e conservazione
- Indici di maturazione:
  1. **Profumo intenso** dal lato del peduncolo
  2. **Distacco spontaneo** o quasi: spinge leggermente con il dito al peduncolo, deve cedere
  3. **Reticolatura** ben pronunciata e dorata (retati)
  4. **Punta del fiore** morbida al tatto
- Tagliare con peduncolo
- Conservazione: 1 settimana in cantina fresca. Se raccolto leggermente acerbo, matura in 2-3 giorni a temperatura ambiente
- Trasformazione: gelato, sorbetto, ma in genere consumo immediato

## Consociazioni e rotazioni
- Come anguria: mais, fagiolo, tagete, ravanello
- **Da evitare**: altre cucurbitacee, patata
- **Rotazione**: 3-4 anni per cucurbitacee

## Note clima costiero
Coltura **ottima per costa centro-italiana**: il melone vuole calore e luce intensa. Salsedine tollerata. I meloni della tradizione costiera (mantovano, cantalupo, retato delle marche) sono nati in zone collinari interne ma producono benissimo anche in pianura litoranea. Importante drenaggio (i meloni in terreni argillosi compatti rendono male).

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

#pianta #orticola #cucurbitacee
