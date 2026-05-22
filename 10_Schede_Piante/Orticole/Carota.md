---
tipo: scheda_pianta
categoria: orticola
nome_comune: Carota
nome_scientifico: Daucus carota subsp. sativus
famiglia: Apiaceae
ciclo: biennale (coltivata come annuale)
periodo_semina: "Febbraio-Luglio (scalare)"
periodo_raccolta: "Maggio-Dicembre"
distanza_pianta_cm: 4
distanza_fila_cm: 30
profondita_semina_cm: 1
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.0
fabbisogno_idrico: medio-alto, costante
difficolta: 2
consociazioni_buone:
  - Cipolla
  - Porro
  - Aglio (allontanano la mosca della carota)
  - Pomodoro
  - Lattuga
  - Ravanello
consociazioni_da_evitare:
  - Aneto
  - Sedano
  - Altre apiacee
successioni_buone:
  - Legumi
  - Cucurbitacee
predecessori_da_evitare:
  - Apiacee (finocchio, prezzemolo, sedano)
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - apiacee
  - radici
---

# 🥕 Carota

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Radice a fittone, coltivata per la fonda parte sotterranea. Varietà classiche italiane: nantese (mezzo lunga), Chantenay (corta e larga), Berlikum (lunga), San Valery, viola di Sicilia (varietà tradizionale a polpa viola-arancione). Per terreni difficili meglio le varietà corte.

## Semina e trapianto
- **Solo semina diretta**: il fittone non tollera il trapianto, si deforma
- Seme piccolissimo: mescolare con sabbia per distribuirlo meglio, oppure usare seme nastrato
- Profondità: 0.5-1 cm, terreno ben drenato e fine
- Distanze: 4-5 cm sulla fila dopo diradamento, 30 cm tra le file
- **Diradamento**: dopo emergenza, lasciare una piantina ogni 4-5 cm. È un'operazione fondamentale, altrimenti carote piccole e contorte
- Semine scalari da febbraio a luglio per avere raccolto continuo

## Cura
- Esposizione: sole pieno
- Terreno: **profondo, sciolto, senza sassi** (i sassi deviano il fittone), **mai concimato di fresco** (letame fresco = carote forcate, biforcate)
- Irrigazione: regolare, evita la spaccatura dei fittoni che subisce dopo siccità + pioggia abbondante
- Pacciamatura sottile dopo diradamento
- Sarchiature leggere, evitando di danneggiare le radici

## Avversità tipiche
- **Mosca della carota** (Psila rosae): la nemica numero uno. Larve scavano gallerie nel fittone, rendendolo amaro e marcio. Difese: reti antinsetto a maglia fine sopra il filare, **consociazione con cipolla** (è il rimedio classico, l'odore confonde la mosca), evitare diradamenti tardivi (rilasciano odore di carota che attira la mosca), pacciamatura
- **Nematodi**: deformazioni, rotazioni lunghe, tagete come precoltura
- **Afidi**: rimedi classici
- **Alternaria, sclerotinia**: arieggiare, ruotare
- **Carote spaccate**: irregolarità irrigua, prevenire con bagnature regolari

## Raccolta e conservazione
- Quando il fittone raggiunge le dimensioni della varietà, di solito 70-100 giorni dopo la semina
- Si tira a mano (terreno sciolto) o si scalza con forchettone
- Conservazione: 1-2 settimane in frigo con foglie tagliate. In sabbia umida in cantina fresca, intere e con un cm di colletto: durano 4-6 mesi
- Trasformazione: sott'aceto, essiccate, sotto sale, marmellata di carote, carote in lattofermentazione

## Consociazioni e rotazioni
- **Compagne d'oro**: cipolla, porro, aglio (allontanano la mosca della carota), pomodoro (la carota arieggia il terreno del pomodoro), lattuga, ravanello (segnatore di fila perché germina prima)
- **Da evitare**: aneto, sedano, altre apiacee (stesse malattie)
- **Rotazione**: 3 anni per le apiacee

## Note clima costiero
Sulla costa centro-italiana si può seminare praticamente tutto l'anno. Le carote autunno-invernali sono più dolci (il freddo concentra gli zuccheri). Estate molto secca rallenta la germinazione: pre-bagnare il solco, coprire con tessuto non tessuto leggero fino all'emergenza. Terreni costieri sabbiosi sono perfetti per carote dritte e lunghe, basta che siano ben concimati con compost maturo (no letame fresco).

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Irrigazione_a_Pioggia]]
- [[primavera]] · [[estate]] · [[autunno]]

#pianta #orticola #apiacee #radici
