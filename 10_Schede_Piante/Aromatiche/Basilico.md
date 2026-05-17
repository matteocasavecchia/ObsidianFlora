---
tipo: scheda_pianta
categoria: aromatica
nome_comune: Basilico
nome_scientifico: Ocimum basilicum
famiglia: Lamiaceae
perenne: false
esposizione: sole pieno (mezz'ombra ore centrali estive)
resistenza_freddo: "Bassa, soffre sotto 10°C, muore sotto 5°C"
resistenza_siccita: bassa
altezza_max_cm: 60
usi:
  - cucina
  - repellente naturale
raccolta_foglie: "Giugno-Ottobre"
periodo_fioritura: "Luglio-Settembre (da impedire per produzione foglie)"
tags:
  - pianta
  - aromatica
  - lamiaceae
---

# 🌿 Basilico

> Famiglia: `=this.famiglia` · Perenne: `=this.perenne` · Esposizione: `=this.esposizione`

## Caratteristiche
Aromatica annuale principe dell'estate mediterranea. Originaria dell'India, in Italia naturalizzata e tradizionale, soprattutto in Liguria (genovese DOP). Varietà classiche: **genovese** (foglia liscia, profumo intenso, classica del pesto), **napoletano** (foglia grande bollosa, sapore robusto), **greco a piccola foglia** (cespuglio compatto), **rosso** (foglia viola, decorativo), **al limone**, **thai** (anice e liquirizia). Esistono varietà perenni nei climi tropicali, ma in Italia è sempre coltivato come annuale.

## Coltivazione
- Esposizione: sole pieno; in piena estate costiera mezz'ombra nelle ore centrali aiuta
- Substrato: ricco, ben drenato, leggermente umido
- Resistenza freddo: pessima (foglie nere già sotto 10°C, pianta morta sotto 5°C)
- Resistenza siccità: bassa (foglie cedevoli al minimo stress idrico)
- Altezza: 30-60 cm
- Propagazione: **da seme** (la più comune, semina aprile-giugno) o **da talea** in acqua (sorprendentemente facile, le radici escono in 7-10 giorni)
- Semina diretta: terreno sopra 18°C (maggio sulla costa) oppure in semenzaio caldo da marzo
- Trapianto: a 4-6 foglie, distanze 25-30 cm

## Cura
- Irrigazione: regolare, al piede. Mai sulle foglie (marciumi)
- **Pinzatura**: pizzicare le cime appena emergono i primi fiori. Stimola ramificazioni laterali, prolunga produzione, mantiene aroma. È l'operazione chiave per non perdere il basilico dopo poche settimane
- Concimazione: compost in trapianto, niente di più
- Pacciamatura organica utile in estate
- Pianta facile da tenere in vaso (vaso largo, 25-30 cm, drenato)

## Raccolta e uso
- Parti utili: **foglie** (mai gli steli vecchi e legnosi)
- Periodo: `=this.raccolta_foglie`
- Tecnica: pizzicare con le dita o forbice piccola, sempre raccogliendo le cime con 2-3 foglie per stimolare la ricrescita. Non strappare la pianta intera
- Mai conservare in frigo (annerisce): conservazione fresca in vaso d'acqua o in olio
- Per pesto e conserve: raccolta abbondante al mattino fresco, prima della fioritura
- Trasformazione classica: **pesto alla genovese**, salse, olio aromatizzato, congelato a cubetti (in olio o nel ghiaccio), essiccazione (perde molto aroma)

## Funzione in giardino
- **Compagno classico** di [[Pomodoro]] (storica consociazione, sembra migliorare aroma e respingere alcuni parassiti)
- Attrae impollinatori (fiori in fine ciclo)
- Repellente naturale verso mosche e zanzare (utile in vaso vicino a porte e finestre, anche se l'effetto è modesto)
- In consociazione con [[Melanzana]], [[Peperone]], [[Zucchina]] funziona bene

## Avversità tipiche
- **Marciume del colletto**: ristagni e suolo zuppo. Drenaggio buono, mai sulle foglie
- **Peronospora del basilico** (Peronospora belbahrii): muffa grigia sotto le foglie, sopra ingialliscono. Aerare, eliminare foglie infette, varietà resistenti (es. Eleonora)
- **Afidi**: rari, sapone molle
- **Lumache** sulle piantine giovani

## Note clima costiero
Il basilico ama il clima mediterraneo costiero, ma soffre la siccità estiva: pacciamatura e irrigazione regolare al piede sono essenziali. In agosto torrido, ombreggiatura parziale nelle ore centrali mantiene la pianta verde e produttiva. La salsedine in aerosol è ben tollerata. **Da settembre la pianta declina rapidamente** con il calo delle temperature notturne: raccogliere abbondante alla fine di agosto per conserve.

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

#pianta #aromatica #lamiaceae
