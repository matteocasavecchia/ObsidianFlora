---
tipo: scheda_pianta
categoria: aromatica
nome_comune: Timo
nome_scientifico: Thymus vulgaris
famiglia: Lamiaceae
perenne: true
esposizione: sole pieno
resistenza_freddo: "Eccellente (-15°C)"
resistenza_siccita: ottima
altezza_max_cm: 30
usi:
  - cucina
  - infusi
  - medicinale tradizionale
  - ornamentale (tappezzante)
raccolta_foglie: "Tutto l'anno"
periodo_fioritura: "Maggio-Luglio"
tags:
  - pianta
  - aromatica
  - lamiaceae
  - mediterraneo
---

# 🌿 Timo

> Famiglia: `=this.famiglia` · Perenne: `=this.perenne` · Esposizione: `=this.esposizione`

## Caratteristiche
Piccolo arbusto perenne semilegnoso, fogliame fine aromatico, fiori piccoli rosa-lilla in estate. Pianta della macchia mediterranea, robusta come poche. Varietà classiche: **vulgaris** (timo comune, il più aromatico per uso culinario), **citriodorus** (al limone, foglie verde-gialle, profumo agrumato), **serpyllum** (timo serpillo, tappezzante, ottimo per rocciai e bordure pestabili), **mastichina** (timo greco, aroma resinoso), **vulgaris Compactus** (palla compatta). Il timo selvatico (Thymus pulegioides) cresce spontaneo su sentieri costieri.

## Coltivazione
- Esposizione: sole pieno
- Substrato: drenato, calcareo, anche poverissimo. Detesta umidità
- Resistenza freddo: eccellente (-15°C e oltre)
- Resistenza siccità: ottima
- Altezza: 15-30 cm
- Propagazione: per **talea** (semplice, primavera-estate), **divisione cespo**, **seme** (lento)

## Cura
- Irrigazione: solo i primi mesi, poi praticamente nessuna
- Concimazione: niente
- **Potatura**: dopo la fioritura, accorciare di un terzo. Aiuta a mantenere portamento compatto e ringiovanire il cespo
- Pianta longeva ma tende a lignificare: rinnovo ogni 4-5 anni per cespi giovani

## Raccolta e uso
- Parti utili: **rametti con foglie**, tutto l'anno
- Aroma massimo: in fioritura
- Tecnica: tagliare rametti apicali con forbice
- Fresco: cucina (carni, marinate, ragù, brodi)
- Essiccato: ottimo conservante dell'aroma, in mazzetti appesi all'ombra
- Usi: timo serpillo per liquori e infusi digestivi, timo al limone per pesce e dolci

## Funzione in giardino
- **Tappezzante** (varietà serpyllum): copre il suolo, controlla erbacce, sopporta calpestio leggero
- **Attrae impollinatori** (api, sirfidi)
- Consociato bene con [[Cavolo]] (confonde la cavolaia)
- Ottimo nelle aiuole mediterranee miste con [[Rosmarino]], [[Salvia]], [[Lavanda]]
- Bellissimo in rocciai, muretti a secco, bordure aromatiche

## Avversità tipiche
- **Marciumi**: ristagni d'acqua, drenaggio essenziale
- **Oidio**: in casi rari di umidità eccessiva
- Pianta straordinariamente rustica, quasi senza nemici

## Note clima costiero
**Pianta perfetta per costa mediterranea**: tollera salsedine, vento, siccità, suoli più poveri immaginabili. Cresce spontaneo su sentieri e scogliere costieri. Le varietà tappezzanti sono ottime per ricoprire pendii sassosi senza acqua. Resistenza assoluta una volta affrancata.

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
- [[Gestione_Salsedine_Vento]] · [[Semenzaio_Moltiplicazione]]

#pianta #aromatica #lamiaceae #mediterraneo
