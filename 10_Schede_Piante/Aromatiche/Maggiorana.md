---
tipo: scheda_pianta
categoria: aromatica
nome_comune: Maggiorana
nome_scientifico: Origanum majorana
famiglia: Lamiaceae
perenne: true
esposizione: sole pieno
resistenza_freddo: "Bassa (-5°C); al Nord coltivata come annuale"
resistenza_siccita: buona
altezza_max_cm: 50
usi:
  - cucina
  - infusi
  - oli essenziali
raccolta_foglie: "Maggio-Settembre (massimo aroma in fioritura)"
periodo_fioritura: "Giugno-Agosto"
tags:
  - pianta
  - aromatica
  - lamiaceae
---

# 🌿 Maggiorana

> Famiglia: `=this.famiglia` · Perenne: `=this.perenne` · Esposizione: `=this.esposizione`

## Caratteristiche
Cugina dolce e gentile dell'[[Origano]]. Pianta perenne nelle zone calde, annuale al Nord per via del freddo invernale. Foglie piccole, oblunghe, leggermente velutate. Aroma più delicato, dolce e raffinato dell'origano, con note balsamiche. Coltura tradizionale dell'Italia mediterranea. Spesso confusa con l'origano: la differenza si sente subito al naso e in cucina.

## Coltivazione
- Esposizione: sole pieno
- Substrato: drenato, leggero, calcareo. Detesta ristagni
- Resistenza freddo: bassa (-5°C). Al Nord Italia è coltivata come annuale o protetta in inverno
- Resistenza siccità: buona, ma meno tollerante dell'origano
- Altezza: 30-50 cm
- Propagazione: per **seme** (semenzaio aprile-maggio, 18-22°C), per **talea**, per **divisione cespo**

## Cura
- Irrigazione: moderata, leggermente più della maggior parte delle aromatiche mediterranee
- Concimazione: minima, compost in semina
- **Potatura**: dopo la fioritura tagliare a metà cespo per stimolare ricaccio
- In vaso: si comporta benissimo, ottima per balconi

## Raccolta e uso
- Parti utili: **rametti con foglie e fiori**, in piena fioritura per aroma migliore
- Tecnica: tagliare rametti apicali con forbice
- Fresca: ottima su pesce, salumi, salse, pizze
- Essiccata: in mazzetti appesi all'ombra, conservazione in barattoli ermetici
- Usi: tradizione ligure (cima ripiena), pugliese (pesce e patate), francese (herbes de Provence)

## Funzione in giardino
- **Attrae impollinatori** (api, sirfidi)
- Ottima compagna di [[Cavolo]] (confonde la cavolaia)
- Buona in aiuole miste con [[Rosmarino]], [[Salvia]], [[Timo]], [[Origano]]
- Ottima in vaso per cucina di balcone

## Avversità tipiche
- **Marciumi radicali**: ristagni d'acqua. Drenaggio essenziale
- Pianta generalmente rustica

## Note clima costiero
Sulla costa centro-italiana cresce bene tutto l'anno, gli inverni miti la lasciano in vegetazione e perenne. Salsedine tollerata. Buon compromesso tra robustezza mediterranea e finezza aromatica. Si autosemina facilmente se lasciata fiorire e andare a seme.

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
- [[Semenzaio_Moltiplicazione]] · [[Consociazioni]]

#pianta #aromatica #lamiaceae
