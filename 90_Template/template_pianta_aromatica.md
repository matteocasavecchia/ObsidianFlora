---
tipo: scheda_pianta
categoria: aromatica
nome_comune: <% tp.file.title %>
nome_scientifico: 
famiglia: 
perenne: true
esposizione: sole pieno
resistenza_freddo: 
resistenza_siccita: alta
altezza_max_cm: 
usi:
  - cucina
raccolta_foglie: 
periodo_fioritura: 
tags:
  - pianta
  - aromatica
---

# 🌿 <% tp.file.title %>

> Famiglia: `=this.famiglia` · Perenne: `=this.perenne` · Esposizione: `=this.esposizione`

## Caratteristiche
_(descrizione, varietà locali, profilo aromatico, eventuali sinonimi)_

## Coltivazione
- Esposizione: `=this.esposizione`
- Substrato preferito: _(drenato, calcareo, sabbioso...)_
- Resistenza freddo: `=this.resistenza_freddo`
- Resistenza siccità: `=this.resistenza_siccita`
- Altezza massima: `=this.altezza_max_cm` cm
- Propagazione: _(seme, talea, divisione cespi)_

## Raccolta e uso
- Parti utili: _(foglie, fiori, semi)_
- Periodo raccolta foglie: `=this.raccolta_foglie`
- Periodo fioritura: `=this.periodo_fioritura`
- Conservazione: _(fresca, essiccata all'ombra, in olio, in sale)_
- Usi: `=this.usi`

## Funzione in giardino
- Attira impollinatori: _(sì/no, quali)_
- Repellente naturale: _(quali parassiti)_
- Consociazioni utili: _(con quali ortaggi)_

## Note clima costiero
_(tolleranza salsedine, vento, esposizione marina)_

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

## Riferimenti
- [[_MOC_Piante]]

#pianta #aromatica
