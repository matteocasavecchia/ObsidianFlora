---
tipo: scheda_pianta
categoria: aromatica
nome_comune: Lavanda
nome_scientifico: Lavandula angustifolia / L. × intermedia / L. stoechas
famiglia: Lamiaceae
perenne: true
esposizione: sole pieno
resistenza_freddo: "Eccellente (angustifolia -20°C; stoechas -10°C)"
resistenza_siccita: ottima
altezza_max_cm: 80
usi:
  - ornamentale
  - cosmetica (oli essenziali)
  - infusi
  - cucina (uso parsimonioso)
  - repellente naturale
raccolta_foglie: "Fiori in piena fioritura (Giugno-Luglio)"
periodo_fioritura: "Giugno-Luglio (angustifolia); Aprile-Maggio + rifioritura (stoechas)"
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Microaspersione]]"
tags:
  - pianta
  - aromatica
  - lamiaceae
  - mediterraneo
  - ornamentale
---

# 🌿 Lavanda

> Famiglia: `=this.famiglia` · Perenne: `=this.perenne` · Esposizione: `=this.esposizione`

## Caratteristiche
Arbusto perenne sempreverde, dal portamento globoso, fogliame grigio-argenteo, fioritura azzurro-viola intensa estiva. Tre specie principali coltivate: **Lavandula angustifolia** (lavanda vera o officinale, fiori azzurro chiaro, profumo dolce, la migliore per oli essenziali e cucina, rustica), **Lavandula × intermedia** (lavandino, ibrido naturale tra angustifolia e latifolia, più grande e produttivo, classico delle distese della Provenza), **Lavandula stoechas** (lavanda papillon, fiori a "stendardo" caratteristici, fioritura più precoce, meno rustica al freddo). Per costa centro-italiana: tutte e tre vanno bene, angustifolia la più sicura.

## Coltivazione
- Esposizione: sole pieno totale, fondamentale per fioritura e portamento compatto
- Substrato: drenato, calcareo, povero. Detesta umidità persistente e suoli grassi
- Resistenza freddo: eccellente per angustifolia (-20°C), buona per intermedia (-15°C), media per stoechas (-10°C)
- Resistenza siccità: ottima
- Altezza: 30-80 cm secondo varietà
- Propagazione: per **talea semilegnosa** (estate, settembre), molto facile e veloce. Per **seme** funziona ma è lento e variabile

## Cura
- Irrigazione: solo i primi 2 anni, poi praticamente nessuna
- Concimazione: nessuna o minima (un pugno di compost ogni 2 anni)
- **Potatura**: fondamentale, **due volte l'anno**:
  - **Dopo la fioritura** (luglio-agosto): tagliare gli steli sfioriti
  - **Fine inverno** (febbraio-marzo): riformare il cespuglio accorciando di un terzo o metà la parte verde, **mai sul legno vecchio** (non ricaccia). Questa potatura è quella che fa la differenza tra cespi compatti e produttivi e cespi sfilacciati e spogli al centro
- Sostituzione: ogni 8-10 anni, le piante invecchiate diventano lignificate al centro

## Raccolta e uso
- Parti utili: **fiori** (in spighe), raccolti **in piena fioritura** prima che inizino ad aprirsi tutti gli stelli
- Tecnica: tagliare l'intera spiga con stelo, raccolta al mattino fresco
- **Essiccazione**: in mazzetti appesi a testa in giù in luogo ombreggiato e arieggiato (mai sole diretto, deteriora profumo) per 2-3 settimane
- Usi: sacchetti profumati per armadi, oli essenziali (distillazione, alambicco), infusi rilassanti, cucina (parsimoniosa, in zucchero, biscotti, marmellate, abbinamento con miele), repellente naturale verso tarme

## Funzione in giardino
- **Pianta ornamentale di prima fascia** per giardini mediterranei e costieri
- **Attrae impollinatori** in massa (api, bombi, farfalle): fioritura abbondante e prolungata
- **Repellente** verso afidi e formiche
- Ottima in **bordure** miste con [[Rosmarino]], [[Salvia]], [[Timo]]
- Frangivento naturale a media altezza
- Buona compagna di [[Rosmarino]], rose (allontana afidi)

## Avversità tipiche
- **Marciumi radicali**: ristagni d'acqua, drenaggio essenziale
- **Cicalina della lavanda** (Hyalesthes obsoletus): vettore del fitoplasma dello stolbur, malattia grave. Difficile da controllare
- **Cocciniglia**: rara, olio bianco minerale in inverno
- Pianta generalmente molto rustica

## Note clima costiero
**Una delle piante più adatte alla costa centro-italiana**: tollera salsedine, vento marino, siccità, suoli poveri e calcarei. La fioritura supporta gli impollinatori per le orticole vicine. Pianta perfetta anche per giardini "low-maintenance" mediterranei: una volta affrancata, vive per anni senza interventi se non la potatura annuale. Particolarmente bella in massa lungo muretti a secco e pendii esposti sud.

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
- [[Gestione_Salsedine_Vento]] · [[Semenzaio_Moltiplicazione]] · [[Forme_Allevamento_Potatura]]

#pianta #aromatica #lamiaceae #mediterraneo #ornamentale
