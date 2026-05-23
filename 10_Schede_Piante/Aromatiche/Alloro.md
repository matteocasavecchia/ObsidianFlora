---
tipo: scheda_pianta
categoria: aromatica
nome_comune: Alloro
nome_scientifico: Laurus nobilis
famiglia: Lauraceae
perenne: true
esposizione: sole pieno o mezz'ombra
resistenza_freddo: "Buona (-10°C, defogliazioni temporanee a -8°C)"
resistenza_siccita: ottima
altezza_max_cm: 1000
usi:
  - cucina
  - infusi
  - siepi mediterranee
  - ornamentale (forme topiarie)
raccolta_foglie: "Tutto l'anno"
periodo_fioritura: "Marzo-Maggio"
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Microaspersione]]"
tags:
  - pianta
  - aromatica
  - lauraceae
  - mediterraneo
  - sempreverde
---

# 🌿 Alloro

> Famiglia: `=this.famiglia` · Perenne: `=this.perenne` · Esposizione: `=this.esposizione`

## Caratteristiche
Albero o grande arbusto sempreverde tipico mediterraneo, fino a 10 m in libertà ma facilmente controllabile con potature. Foglie coriacee lucide verde scuro, aromatiche tutto l'anno (l'aroma migliora con l'essiccazione). Pianta simbolica nella cultura greco-romana (corona di alloro). Dioica (piante maschili e femminili separate, le femminili producono bacche scure ornamentali). Varietà: laurus nobilis comune, **angustifolia** (foglie strette), **aurea** (foglie giovani gialle), **Aureomarginata** (variegata).

## Coltivazione
- Esposizione: sole pieno o mezz'ombra (anche ombra in piena estate costiera)
- Substrato: drenato, anche calcareo e povero. Adattabile a vari terreni
- Resistenza freddo: buona (-10°C); a -8°C può defogliare temporaneamente ma ricaccia
- Resistenza siccità: ottima
- Altezza: 2-10 m a seconda della potatura e libertà di crescita
- Propagazione: per **talea semilegnosa** (estate-autunno, lenta ma sicura), per **margotta**, per **seme** (germinazione lenta, mesi)

## Cura
- Irrigazione: solo nei primi 2 anni, poi praticamente inutile
- Concimazione: nessuna o minima (compost ogni 2-3 anni in vaso)
- **Potatura**: forma libera o controllata. Si può tenere a siepe (potature 2-3 volte l'anno), a forma globosa, a piramide, a colonna. Tagli sostenuti, ricaccia bene
- In vaso: ottima coltura, rinvaso ogni 2-3 anni. Una pianta storica in vaso può durare decenni
- Crescita: lenta nei primi anni, poi accelera

## Raccolta e uso
- Parti utili: **foglie**, raccolte tutto l'anno
- Tecnica: staccare foglie singole o piccoli rametti
- Fresche: aroma più delicato e fresco
- Essiccate: aroma più intenso e concentrato (parodoxo: si essiccano 2-3 settimane, raccolta dalle parti più alte e ben aerate)
- Usi: ragù, brodi, marinate, infusi digestivi, caratteristico nelle salamoie di [[Olivo|olive]]

## Funzione in giardino
- **Pianta da siepe mediterranea** di prima fascia (frangivento, schermatura)
- **Attrae impollinatori** in marzo-aprile (fiori discreti ma utili)
- **Ornamentale**: forme topiarie classiche (sfere, coni, spirali)
- Buona compagna per giardini xerofili mediterranei

## Avversità tipiche
- **Psilla dell'alloro** (Trioza alacris): rigonfiamenti sulle foglie, bordi accartocciati. Il sintomo principale di alloro in città. Eliminare foglie colpite, sapone molle
- **Cocciniglia**: scudetti sui rami, fumaggine. Olio bianco minerale in inverno, predatori
- **Marciumi radicali**: solo da ristagni
- Pianta generalmente molto rustica

## Note clima costiero
**Pianta perfetta per costa mediterranea**: salsedine, vento, siccità, suoli poveri, tutto tollerato benissimo. Pianta storica delle coste tirreniche e ioniche italiane. Coltura praticamente "imperdibile" sulla costa. Si può anche far crescere in macchia spontanea da seme.

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
- [[Gestione_Salsedine_Vento]] · [[Forme_Allevamento_Potatura]] · [[Semenzaio_Moltiplicazione]]

#pianta #aromatica #lauraceae #sempreverde #mediterraneo
