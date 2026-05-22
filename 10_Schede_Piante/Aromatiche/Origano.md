---
tipo: scheda_pianta
categoria: aromatica
nome_comune: Origano
nome_scientifico: Origanum vulgare
famiglia: Lamiaceae
perenne: true
esposizione: sole pieno
resistenza_freddo: "Buona (-15°C)"
resistenza_siccita: ottima
altezza_max_cm: 60
usi:
  - cucina
  - infusi
  - olio essenziale
raccolta_foglie: "Maggio-Settembre (massimo aroma in fioritura)"
periodo_fioritura: "Giugno-Agosto"
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Microaspersione]]"
tags:
  - pianta
  - aromatica
  - lamiaceae
  - mediterraneo
---

# 🌿 Origano

> Famiglia: `=this.famiglia` · Perenne: `=this.perenne` · Esposizione: `=this.esposizione`

## Caratteristiche
Pianta perenne erbacea (la base lignifica leggermente), aromatica intensa, simbolo della cucina mediterranea. Foglie ovali piccole, fiori bianco-rosa in pannocchia. Cresce spontaneo su pendii soleggiati di tutta Italia centro-meridionale. Varietà classiche: **vulgare** (comune europeo, aroma moderato), **vulgare ssp. hirtum** (origano greco, aroma intenso, il più ricercato in cucina), **vulgare Aureum** (foglie gialle, ornamentale), **vulgare Compactum** (cespuglio compatto). Confondibile con la **maggiorana** (Origanum majorana), che è specie affine ma con aroma più delicato e portamento meno rustico.

## Coltivazione
- Esposizione: sole pieno
- Substrato: drenato, leggero, calcareo, anche povero. Detesta ristagni
- Resistenza freddo: buona (-15°C)
- Resistenza siccità: ottima
- Altezza: 30-60 cm
- Propagazione: per **divisione cespo** (primavera o autunno), per **talea**, per **seme** (più lento ma fattibile)

## Cura
- Irrigazione: minima, solo nei primi mesi e in caso di siccità estrema
- Concimazione: praticamente nulla
- **Potatura**: dopo la fioritura tagliare a terra (o quasi) per stimolare nuova vegetazione. Cespi vanno divisi ogni 3-4 anni per evitare invecchiamento del centro
- In inverno la parte aerea può seccare in zone fredde, ricaccia da terra a primavera

## Raccolta e uso
- Parti utili: **rametti con foglie e fiori**, raccolti in piena fioritura per il massimo aroma
- Tecnica: tagliare interi rametti con forbice quando i primi fiori sono aperti
- **Essiccazione classica**: in mazzetti appesi a testa in giù in luogo ombreggiato e arieggiato per 2-3 settimane, poi sgranellare e conservare in barattoli ermetici
- Fresco: cucina pugliese, siciliana, greca (pizza, focacce, pomodori al forno)
- Essiccato: il più diffuso in cucina italiana, mantiene l'aroma per 1-2 anni

## Funzione in giardino
- **Tappezzante** in aiuole miste mediterranee
- **Attrae impollinatori** (lunga fioritura estiva)
- Ottimo compagno di [[Cavolo]], [[Pomodoro]], [[Peperone]] in consociazione
- Pianta ornamentale (fioritura abbondante e prolungata)
- Bordure aromatiche con [[Rosmarino]], [[Timo]], [[Salvia]]

## Avversità tipiche
- **Marciumi radicali**: ristagni d'acqua, drenaggio essenziale
- **Ruggine**: rara, in casi di umidità prolungata
- Pianta molto rustica, praticamente senza nemici

## Note clima costiero
**Perfetto per costa mediterranea centro-italiana**: clima naturale, salsedine tollerata, siccità preferita. L'origano selvatico si trova spesso sui sentieri costieri e di macchia. Coltura praticamente automatica: piantato una volta, si autosemina e si propaga da solo. Ideale anche in vaso su balconi e terrazze esposte.

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Microaspersione]]
- [[Consociazioni]] · [[Semenzaio_Moltiplicazione]]

#pianta #aromatica #lamiaceae #mediterraneo
