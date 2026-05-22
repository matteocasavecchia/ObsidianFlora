---
tipo: scheda_pianta
categoria: aromatica
nome_comune: Salvia
nome_scientifico: Salvia officinalis
famiglia: Lamiaceae
perenne: true
esposizione: sole pieno
resistenza_freddo: "Buona (-10°C, fino a -15°C per varietà rustiche)"
resistenza_siccita: ottima
altezza_max_cm: 80
usi:
  - cucina
  - infusi
  - medicinale tradizionale
  - ornamentale
raccolta_foglie: "Tutto l'anno (massimo aroma prima della fioritura)"
periodo_fioritura: "Maggio-Giugno"
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Microaspersione]]"
tags:
  - pianta
  - aromatica
  - lamiaceae
  - mediterraneo
---

# 🌿 Salvia

> Famiglia: `=this.famiglia` · Perenne: `=this.perenne` · Esposizione: `=this.esposizione`

## Caratteristiche
Arbusto perenne semilegnoso, foglie velutate grigio-verdi, aromatiche, fiori azzurro-violacei in spighe. Mediterranea, longeva (10-20 anni in condizioni adatte). Varietà classiche: **officinalis** (la tradizionale italiana, foglia stretta grigia), **purpurascens** (foglie giovani viola), **tricolor** (bianca, rosa, verde, decorativa ma meno rustica), **icterina** (foglie variegate gialle), **berggarten** (foglia larga e tondeggiante, profumo intenso). Esistono numerose altre specie di Salvia ornamentali (pratensis, nemorosa, sclarea) con usi diversi.

## Coltivazione
- Esposizione: sole pieno, fondamentale per aroma e portamento compatto
- Substrato: drenato, calcareo, anche povero. Detesta umidità persistente
- Resistenza freddo: buona (-10°C), le varietà tradizionali italiane più rustiche resistono fino a -15°C
- Resistenza siccità: ottima
- Altezza: 50-80 cm
- Propagazione: per **talea semilegnosa** (estate, settembre), per **divisione cespo** (primavera o autunno), per **seme** (più lento)

## Cura
- Irrigazione: solo i primi anni e in caso di siccità estrema
- Concimazione: minima, compost ogni 2-3 anni
- **Potatura**: dopo la fioritura (giugno-luglio), accorciare di un terzo per mantenere portamento compatto e ringiovanire. Mai sul legno vecchio (ricaccio difficile)
- **Pacciamatura organica** al piede in inverno per piante giovani in zone fredde
- Sostituire le piante ogni 5-7 anni quando lignificate eccessivamente

## Raccolta e uso
- Parti utili: **foglie**, raccolte tutto l'anno
- Massimo aroma: prima della fioritura primaverile
- Tecnica: foglie singole o rametti
- Fresca: cucina, infusi, frittate, burro alla salvia
- Essiccata: in mazzetti appesi all'ombra, conservazione in barattoli
- Usi: ricetta classica della salvia fritta in pastella, abbinamento con burro per pasta, ravioli, carni bianche; infuso digestivo; gargarismi (proprietà antinfiammatorie tradizionali)

## Funzione in giardino
- Pianta ornamentale di prima qualità (forma compatta, fioritura)
- **Attrae impollinatori** (api, bombi)
- **Repellente**: confonde alcuni parassiti dei cavoli. Consociata bene con [[Cavolo]], [[Carota]], [[Pomodoro]]
- Da **evitare con [[Cetriolo]]**: si dice abbia effetto allelopatico
- Ottima in aiuole miste mediterranee con [[Rosmarino]], [[Timo]], [[Lavanda]]

## Avversità tipiche
- **Marciumi radicali**: da ristagni. Drenaggio essenziale
- **Oidio**: in zone troppo umide o ombreggiate
- **Cicalina della salvia**: macchie biancastre sulle foglie. Sapone molle
- Pianta generalmente molto rustica

## Note clima costiero
**Ottimamente adatta** al clima centro-italiano costiero: tollera salsedine, vento marino, siccità, suoli poveri. Sopravvive senza cure particolari. Pianta storica della tradizione italiana, presente in ogni orto familiare mediterraneo. In estate la fioritura attira impollinatori utili per le orticole vicine.

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
- [[Semenzaio_Moltiplicazione]] · [[Consociazioni]]

#pianta #aromatica #lamiaceae #mediterraneo
