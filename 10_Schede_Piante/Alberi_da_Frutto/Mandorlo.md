---
tipo: scheda_pianta
categoria: albero_da_frutto
nome_comune: Mandorlo
nome_scientifico: Prunus dulcis
famiglia: Rosaceae
periodo_raccolta: "Agosto-Settembre"
periodo_potatura: "Gennaio-Febbraio (secca); verde estiva leggera"
forma_allevamento: "Vaso"
portainnesto_consigliato: "Franco (da seme di mandorlo amaro); GF677 (per terreni difficili)"
esposizione: sole pieno
resistenza_salsedine: alta
resistenza_freddo: "-15°C pianta; fioritura febbraio molto a rischio gelate"
entrata_in_produzione_anni: 4
autofertile: parziale
impollinatori_richiesti: "Quasi sempre richiesto (eccezione: Tuono, Genco autofertili)"
sesto_impianto_m: "5 × 6"
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Conca_e_Solco]]"
  - "[[Swale_Canali_Infiltrazione]]"
tags:
  - albero
  - drupacee
  - rosaceae
  - frutta_secca
---

# 🌰 Mandorlo

> Famiglia: `=this.famiglia` · Raccolta: `=this.periodo_raccolta` · Potatura: `=this.periodo_potatura`

## Caratteristiche
Tra le prime piante a fiorire (gennaio-febbraio sulla costa), il mandorlo è un classico mediterraneo. Frutto: la "mandorla" è il seme contenuto nel nocciolo. La polpa esterna (mesocarpo, "mallo") è coriacea, non commestibile, si distacca a maturità. Varietà classiche italiane: **Tuono** (autofertile, pugliese, varietà di riferimento moderna), **Genco** (autofertile), **Filippo Cea**, **Pizzuta d'Avola** (siciliana, tradizionale, richiede impollinatore), **Don Carlo**, **Texas** (americana, autofertile). Mandorle "dolci" da consumo vs "amare" (per estrazione olio o liquori, tossiche in quantità per amigdalina).

## Impianto
- Esposizione: sole pieno
- Sesto: 5 × 6 m (vaso); 4 × 5 m (intensivo moderno)
- Portainnesto: franco da mandorlo amaro (classico, rustico), GF677 (mandorlo × pesco, per terreni difficili)
- Periodo: novembre-febbraio a radice nuda
- Buca: 60 × 60 × 60 cm, drenaggio essenziale
- Ammendanti: compost, cornunghia
- Pianta sviluppa rapidamente apparato radicale fittonante: tutore solo i primi 2 anni

## Cura annuale
- Concimazione: ottobre-novembre, compost al piede
- Irrigazione: il mandorlo tollera bene la siccità. Irrigazione di soccorso utile per giovani esemplari e in fase di formazione frutti, ma non indispensabile per piante adulte
- Pacciamatura organica utile
- Spollonatura

## Potatura
- Asciutta (gennaio-febbraio): formazione e mantenimento vaso. **Mai potature drastiche** sul mandorlo (sensibile a gommosi)
- Verde estiva leggera: eliminazione succhioni
- Forma: vaso aperto, 3-4 branche principali
- Il mandorlo fruttifica su rami misti e mazzetti di maggio: mantenere ricambio annuale
- Le piante adulte producono di più se lasciate sviluppare in libertà che con potatura aggressiva

## Impollinazione e produzione
- **Maggior parte delle varietà tradizionali**: auto-incompatibili, richiedono impollinatore (almeno 2 varietà compatibili in impianto)
- **Varietà autofertili moderne** (Tuono, Genco): possono stare anche sole, ma rendono di più in impianto misto
- Impollinazione entomofila (api): importanza dei pronubi
- Fioritura: gennaio-febbraio (molto precoce). **Principale rischio: gelate tardive sui fiori**
- Entrata in produzione: 4-5 anni
- Produzione adulta: 15-30 kg di mandorle in guscio per pianta

## Avversità tipiche
- **Corineo** (Stigmina carpophila): macchie con fori sulle foglie, cancri rameali, marciumi sui frutti. Rame autunnale e a fine inverno (poltiglia bordolese)
- **Monilia**: marciumi su fiori e frutti. Rame
- **Capnodio** (Ceratocystis fimbriata): cancro tracheomicotico, dissecca la pianta dal basso. Evitare ferite agli arti basali (tagliaerba, rincalzo)
- **Cocciniglia di San José**: scudetti rossastri sui rami. Olio bianco minerale in inverno
- **Eulia, tignola del mandorlo**: larve nelle mandorle. Trappole feromoni, raccolta tempestiva
- **Tarlo** (rodilegno giallo, Zeuzera pyrina): larva nel legno, dissecca rami. Inserire filo metallico nei fori e fenocco

## Resistenza al contesto costiero
Pianta straordinariamente adatta alla costa mediterranea: tollera salsedine, siccità, vento, suoli poveri e calcarei. Una pianta perfetta per chi vuole frutta secca senza grande impegno irriguo. L'unico problema serio è la **fioritura precocissima** (gennaio-febbraio): i fiori sono distrutti a -2°C. Sulla costa centro-italiana questo problema è ridotto rispetto all'entroterra, ma in caso di gelate tardive si rischia di perdere il raccolto annuale.

## Raccolta e conservazione
- Quando il **mallo esterno si screpola** spontaneamente e cade, o si può staccare a mano facilmente (agosto-settembre)
- Si scuote la pianta con telo a terra, oppure si raccoglie a mano
- Pulizia: rimuovere il mallo (se non già caduto), essiccare il guscio per 1-2 settimane al sole o in luogo ventilato
- **Conservazione mandorle in guscio**: 1-2 anni in luogo asciutto. **Sgusciate**: 6 mesi (irrancidiscono per ossidazione)
- Trasformazione: pasta di mandorle, latte di mandorla (orzata), amaretti, pasta reale, granella

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Irrigazione_a_Conca_e_Solco]] · [[Swale_Canali_Infiltrazione]]
- [[inverno]] · [[primavera]] · [[estate]]

#pianta #albero_da_frutto #drupacee #frutta_secca
