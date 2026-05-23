---
tipo: scheda_pianta
categoria: aromatica
nome_comune: Melissa
nome_scientifico: Melissa officinalis
famiglia: Lamiaceae
perenne: true
esposizione: mezz'ombra (sole pieno con suolo fresco)
resistenza_freddo: "Eccellente (-20°C)"
resistenza_siccita: bassa
altezza_max_cm: 80
usi:
  - infusi rilassanti
  - cucina (dolci, salse, abbinamenti al limone)
  - liquori
  - apicoltura (mellifera)
raccolta_foglie: "Maggio-Settembre (massimo aroma prima della fioritura)"
periodo_fioritura: "Giugno-Agosto"
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Microaspersione]]"
tags:
  - pianta
  - aromatica
  - lamiaceae
  - tisane
---

# 🌿 Melissa

> Famiglia: `=this.famiglia` · Perenne: `=this.perenne` · Esposizione: `=this.esposizione`

## Caratteristiche
Pianta erbacea perenne con foglie ovate dentate, profumo intenso di limone (da cui anche il nome "cedronella" o "limoncella"). Pianta tradizionale degli orti monastici italiani, ricca di proprietà calmanti e digestive nella medicina popolare. Il nome scientifico Melissa deriva dal greco "ape": le api ne vanno particolarmente ghiotte. Varietà: officinalis (la classica), **citronella** (verde brillante), **All Gold** (foglie dorate, decorativa).

## Coltivazione
- Esposizione: mezz'ombra preferita, sole pieno tollerato con suolo sempre fresco
- Substrato: fresco, ricco, ben drenato. Si adatta a vari tipi di suolo
- Resistenza freddo: eccellente. In inverno la parte aerea muore, ricaccia da rizoma a primavera
- Resistenza siccità: bassa. Soffre stress idrici (foglie cadenti, aroma ridotto)
- Altezza: 50-80 cm
- Propagazione: per **divisione cespo** (semplice, primavera o autunno), per **talea** (in acqua), per **seme** (semenzaio primaverile o **autosemina spontanea**, anche abbondante)

## ⚠️ Tendenza invasiva
La melissa si autosemina facilmente e può colonizzare spazi anche dove non era prevista. Non è invasiva come la [[Menta]] (no stoloni sotterranei), ma le semine spontanee abbondano. Eliminare i fiori prima della formazione dei semi se non si vuole espansione, oppure raccogliere e controllare.

## Cura
- Irrigazione: regolare, soprattutto in estate
- Pacciamatura organica utile in estate
- Concimazione: compost in primavera
- **Potatura**: tagliare i fiori per favorire foglie e ridurre autosemina. In autunno la parte aerea si può tagliare a 5-10 cm
- Divisione cespi ogni 3-4 anni per ringiovanire

## Raccolta e uso
- Parti utili: **foglie** (massimo aroma prima della fioritura), **fiori** (commestibili, decorativi)
- Tecnica: tagliare rametti o foglie singole
- Fresca: tisane, succhi, abbinamenti al limone, dolci (creme, gelati, marmellate)
- Essiccata: in mazzetti appesi all'ombra, conservazione in barattoli (aroma si attenua dopo 6 mesi)
- Usi: **tisane rilassanti** (digestive, calmanti), **acqua aromatizzata**, abbinamento al pesce, **liquore acqua di melissa** (tradizionale)

## Funzione in giardino
- **Pianta mellifera** eccellente: api a iosa in fioritura
- Ottima in angoli ombreggiati dove poche altre aromatiche prosperano
- Si presta a vasi grandi su terrazzi ombreggiati
- Compagna di rose (sembra allontanare afidi)

## Avversità tipiche
- **Marciumi del colletto**: in suoli pesanti e ristagni. Drenaggio importante
- **Oidio**: in zone troppo umide o densità eccessiva
- **Ruggine**: rara
- Pianta generalmente molto rustica, quasi indistruttibile

## Note clima costiero
Sulla costa centro-italiana cresce bene tutto l'anno con clima mite. **L'estate torrida è il momento critico**: senza irrigazione e in pieno sole le foglie si arrotolano e perdono aroma. Posizione ideale: angolo nord-est della casa, sotto alberi alti, o vaso ombreggiato. Salsedine ben tollerata. Le api del giardino la troveranno per prima cosa nelle giornate calde.

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Microaspersione]]
- [[Semenzaio_Moltiplicazione]] · [[Consociazioni]]

#pianta #aromatica #lamiaceae #tisane
