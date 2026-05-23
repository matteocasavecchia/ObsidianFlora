---
tipo: scheda_pianta
categoria: orticola
nome_comune: Cavolo
nome_scientifico: Brassica oleracea
famiglia: Brassicaceae
ciclo: annuale (biennale a seme)
periodo_semina: "Aprile-Luglio (semenzaio); Giugno-Agosto (trapianto)"
periodo_raccolta: "Ottobre-Marzo"
distanza_pianta_cm: 50
distanza_fila_cm: 70
profondita_semina_cm: 1
esposizione: sole pieno
ph_min: 6.5
ph_max: 7.5
fabbisogno_idrico: medio-alto
difficolta: 2
consociazioni_buone:
  - Lattuga
  - Sedano
  - Aglio
  - Cipolla
  - Aneto
  - Camomilla
consociazioni_da_evitare:
  - Altre brassicacee
  - Fragola
  - Pomodoro
successioni_buone:
  - Legumi
  - Solanacee (dopo riposo)
predecessori_da_evitare:
  - Brassicacee
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - brassicacee
---

# 🥬 Cavolo

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Sotto "cavolo" si raggruppano molte varietà di Brassica oleracea: cappuccio (verde o rosso, testa compatta), verza (foglie bollose), cavolo nero toscano (foglie lunghe e bollose, ottimo per la ribollita), cavolo riccio (kale). Tutti danno il meglio nei mesi freschi, ideali per la costa centro-italiana con inverni miti.

## Semina e trapianto
- Semenzaio da aprile a luglio per produzione autunno-invernale
- Le piantine in semenzaio sono pronte al trapianto a 4-6 foglie vere, 5-6 settimane dalla semina
- Trapianto da giugno ad agosto, possibilmente in giornata coperta o di sera
- Distanze: 50 cm sulla fila, 70 cm tra le file. Cavolo nero anche più stretto (40 × 60)
- Buca con compost o letame maturo, le brassicacee sono ingorde di azoto

## Cura
- Esposizione: sole pieno
- Irrigazione: regolare, soprattutto al trapianto e in fase di formazione della testa. Mai sulle foglie
- Pacciamatura organica per umidità e contro le erbacce
- Rincalzo a 2-3 settimane dal trapianto, stabilizza la pianta
- Concimazione: macerato di ortica in copertura ogni 3 settimane
- Eliminare foglie basse ingiallite per arieggiare e ridurre afidi

## Avversità tipiche
- **Cavolaia** (Pieris brassicae e P. rapae): farfalla bianca le cui larve verdi divorano le foglie. Reti antinsetto fini sopra il filare, Bacillus thuringiensis kurstaki sulle larve giovani, raccolta manuale uova (gialle sotto le foglie)
- **Nottue**: stessa strategia, Bt e raccolta serale
- **Afidi cinerini** (Brevicoryne brassicae): colonie biancastre sulle foglie. Sapone molle, macerato di aglio, predatori (coccinelle, sirfidi)
- **Mosca del cavolo** (Delia radicum): larve nelle radici, pianta avvizzisce. Reti antinsetto a terra, dischetti di cartone alla base della pianta
- **Ernia delle crucifere** (Plasmodiophora brassicae): tumori sulle radici. Patogeno del suolo che persiste decenni: rotazione lunga (5+ anni), pH non acido, evitare ristagni
- **Altica**: piccoli fori tondi sulle foglie giovani, soprattutto a primavera. Pacciamatura, irrigazione (l'altica ama il secco)

## Raccolta e conservazione
- Cappuccio: si raccoglie quando la testa è ben soda alla pressione. Tagliare al colletto lasciando 2-3 foglie esterne
- Verza, cavolo nero, kale: a foglie alterne, dalla più esterna alla più interna. La pianta continua a produrre per mesi
- Conservazione: testa intera 1-2 mesi in cantina fresca. Trasformazione: crauti (fermentazione), sott'aceto, sbianchiti e congelati
- Cavolo nero e verza migliorano dopo le prime gelate (gli amidi si trasformano in zuccheri)

## Consociazioni e rotazioni
- **Compagne**: lattuga e sedano (sfruttano spazio e tempi diversi), aglio e cipolla (effetto antifungino), aneto e camomilla (attirano sirfidi predatori degli afidi)
- **Da evitare**: altre brassicacee (concentrano patogeni), fragola, pomodoro (a discussione)
- **Rotazione**: 4-5 anni prima di rimettere brassicacee. Le crucifere non amano succedere a se stesse né alle barbabietole

## Note clima costiero
Il cavolo nelle sue varianti è la coltura più adatta all'inverno della costa centro-italiana: cresce nei mesi freschi, tollera bene la salsedine, le minime miti non lo bloccano. Le estati torride invece lo fanno andare a seme: per questo i cicli sono pensati per produrre da ottobre in poi. Il cavolo nero in particolare resiste a venti e umidità marina meglio del cappuccio.

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Irrigazione_a_Pioggia]]
- [[autunno]] · [[inverno]]

#pianta #orticola #brassicacee
