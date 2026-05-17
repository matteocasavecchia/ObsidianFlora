---
tipo: scheda_pianta
categoria: aromatica
nome_comune: Erba cipollina
nome_scientifico: Allium schoenoprasum
famiglia: Amaryllidaceae
perenne: true
esposizione: sole pieno o mezz'ombra
resistenza_freddo: "Eccellente (-20°C, riposo invernale completo)"
resistenza_siccita: media
altezza_max_cm: 30
usi:
  - cucina
  - ornamentale (fiori rosa commestibili)
  - repellente naturale
raccolta_foglie: "Marzo-Novembre"
periodo_fioritura: "Maggio-Luglio"
tags:
  - pianta
  - aromatica
  - amaryllidaceae
  - bulbi
---

# 🌿 Erba cipollina

> Famiglia: `=this.famiglia` · Perenne: `=this.perenne` · Esposizione: `=this.esposizione`

## Caratteristiche
Piccola allium perenne a cespo, foglie cilindriche cave erbacee verdi-azzurre dal sapore delicato di [[Cipolla|cipolla]]. In primavera produce graziosi pomponcini rosa-lilla, commestibili e ornamentali. Pianta familiare di tradizione, sotto-utilizzata. Sotto-specie e varietà: schoenoprasum (comune), garlic chive (Allium tuberosum, foglia piatta, aroma di aglio).

## Coltivazione
- Esposizione: sole pieno o mezz'ombra
- Substrato: ricco, fresco, drenato. Tollera vari tipi di terreno
- Resistenza freddo: eccellente. In inverno la parte aerea muore, il cespo (rizoma) ricaccia a primavera
- Resistenza siccità: media (meno delle altre allium)
- Altezza: 20-30 cm
- Propagazione: per **divisione cespo** (semplice, primavera o autunno), per **seme** (in semenzaio primaverile)

## Cura
- Irrigazione: regolare, ama il fresco
- Concimazione: compost in primavera, minimo
- **Divisione cespi** ogni 2-3 anni per ringiovanire e moltiplicare
- **Tagliare i fiori** prima della formazione semi se non si vogliono semi (foglie più tenere); lasciarli se si vuole autosemina o godere dei fiori commestibili
- Eliminare foglie ingiallite in autunno

## Raccolta e uso
- Parti utili: **foglie** (tagliate con forbice 2 cm dal suolo, ricacciano), **fiori** (raccolti freschi, decorativi)
- Periodo: marzo-novembre nella costa
- Fresca: tritata su insalate, uova, salse, formaggi freschi
- I **fiori** spezzettati: insalate, decorazione su piatti
- Conservazione: 3-4 giorni in frigo. Congelata: tagliata e congelata in vasetti o cubetti d'olio. Essiccata: perde quasi tutto l'aroma

## Funzione in giardino
- **Attrae impollinatori** (api, bombi sui pomponcini rosa)
- **Repellente** verso afidi e alcuni parassiti (come tutte le allium)
- Ottima consociata con [[Carota]] (sembra confondere la mosca della carota, come la [[Cipolla]] adulta)
- Bordura ornamentale aromatica
- Ottima in vaso

## Avversità tipiche
- **Ruggine delle allium**: rara, pustole arancioni sulle foglie
- **Mosca della cipolla**: rara su erba cipollina
- Pianta molto robusta

## Note clima costiero
Sulla costa centro-italiana si comporta benissimo: clima mite, mezz'ombra estiva la mantiene produttiva tutto l'anno. Salsedine ben tollerata. In estate torrida le foglie possono soffrire se in pieno sole senza acqua: posizione semi-ombreggiata o irrigazione regolare. Pianta longeva (cespi che vivono 5-10 anni con divisioni).

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

#pianta #aromatica #amaryllidaceae
