---
tipo: scheda_pianta
categoria: orticola
nome_comune: Cetriolo
nome_scientifico: Cucumis sativus
famiglia: Cucurbitaceae
ciclo: annuale
periodo_semina: "Aprile-Giugno"
periodo_raccolta: "Giugno-Settembre"
distanza_pianta_cm: 40
distanza_fila_cm: 100
profondita_semina_cm: 2
esposizione: sole pieno (mezz'ombra estiva tollerata)
ph_min: 6.0
ph_max: 7.0
fabbisogno_idrico: alto e costante
difficolta: 2
consociazioni_buone:
  - Mais
  - Fagiolo rampicante
  - Lattuga
  - Aneto
  - Ravanello
consociazioni_da_evitare:
  - Patata
  - Salvia
  - Altre cucurbitacee
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

# 🥒 Cetriolo

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Pianta rampicante (o strisciante a terra) generosa, dal ciclo rapido. Varietà classiche italiane: cetriolo lungo verde, mezzo lungo bianco, cetriolino da sottaceto (gherkin), marketmore, parigino. Esistono varietà partenocarpiche (non hanno bisogno di impollinazione, niente semi, frutti più digeribili) molto comode in piccolo orto.

## Semina e trapianto
- Semina diretta da fine aprile sulla costa, in postarella 2-3 semi a buca a 2 cm di profondità
- Possibile semenzaio in vasetto da inizio aprile per anticipare, ma il cetriolo soffre il trapianto: meglio vasetti di torba/cocco da interrare con tutto
- Distanze: 40 cm sulla fila a parete (verticale), 80-100 cm tra le file. A terra, 100 × 150 cm
- Letame o compost maturo nella postarella

## Cura
- Esposizione: sole pieno; sulla costa centro-italiana, ombra parziale nelle ore centrali estive aiuta (i frutti escono dritti e meno amari)
- Irrigazione: abbondantissima e costante. Sbalzi idrici = frutti amari e curvi. Goccia al piede, mai sulle foglie
- Pacciamatura organica spessa, indispensabile per umidità costante
- Allevamento verticale fortemente consigliato: palo, rete, spago. Frutti puliti, dritti, raccolta facile, foglie più asciutte (meno malattie)
- Concimazione: una ricarica di compost dopo i primi raccolti
- Per varietà non partenocarpiche, presenza di api per impollinazione

## Avversità tipiche
- **Oidio**: praticamente garantito da metà estate. Stessi rimedi della zucchina (zolfo, bicarbonato, equiseto)
- **Peronospora (Pseudoperonospora cubensis)**: macchie giallo-marroni angolari sulle foglie. Rame
- **Afidi**: vettori di mosaico, sapone molle e predatori
- **Ragnetto rosso**: nebulizzazioni d'acqua, ambiente umido per la pianta
- **Mosaico del cetriolo (CMV)**: pianta deformata, frutti rugosi. Eliminare piante colpite, controllare afidi vettori
- **Frutti amari**: causa principale stress idrico o calore eccessivo, raramente fattore genetico. Si previene con irrigazione regolare

## Raccolta e conservazione
- Si raccoglie giovane (15-20 cm per i comuni, 5-8 cm per i sottaceto), prima che ingiallisca
- Frequenza: ogni 2-3 giorni in piena produzione, altrimenti la pianta smette di produrre nuovi frutti
- Forbice, mai strappare
- Conservazione: 1 settimana in frigo. Trasformazione classica: sottaceti, sotto sale, tzatziki
- Frutti maturati eccessivamente si possono usare per ricavare semi per l'anno dopo

## Consociazioni e rotazioni
- **Compagne**: mais (sostegno naturale e ombra parziale), fagiolo (azoto), lattuga (sfrutta spazio fresco prima che il cetriolo si espanda), aneto (attira impollinatori e predatori), ravanello (allontana piralide del cetriolo)
- **Da evitare**: patata (competizione idrica forte), salvia (allelopatica), altre cucurbitacee (malattie comuni)
- **Rotazione**: minimo 3 anni prima di tornare con cucurbitacee

## Note clima costiero
Il cetriolo apprezza l'umidità atmosferica costiera, soffre invece le ondate di calore secco con vento. In luglio-agosto può essere utile un'ombreggiatura parziale (telo da 30-40%) nelle ore centrali per evitare blocco vegetativo e frutti amari. Sulla costa centro-italiana spesso conviene fare due semine scalari (aprile e giugno) per avere produzione fresca anche in autunno.

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
