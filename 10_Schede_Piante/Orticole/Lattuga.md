---
tipo: scheda_pianta
categoria: orticola
nome_comune: Lattuga
nome_scientifico: Lactuca sativa
famiglia: Asteraceae
ciclo: annuale
periodo_semina: "Tutto l'anno (scalare ogni 20 giorni)"
periodo_raccolta: "30-70 giorni dopo la semina secondo varietà"
distanza_pianta_cm: 25
distanza_fila_cm: 30
profondita_semina_cm: 0.5
esposizione: sole pieno (mezz'ombra in estate)
ph_min: 6.0
ph_max: 7.0
fabbisogno_idrico: medio-alto, costante
difficolta: 1
consociazioni_buone:
  - Carota
  - Cipolla
  - Ravanello
  - Fragola
  - Cetriolo
  - Cavolo
consociazioni_da_evitare:
  - Sedano
  - Prezzemolo
  - Girasole
successioni_buone:
  - Legumi
  - Solanacee
predecessori_da_evitare:
  - Asteracee (radicchio, scarola, indivia)
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - asteracee
  - foglia
---

# 🥬 Lattuga

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
La regina dell'insalata. Esistono molte tipologie con cicli e usi diversi: **cappuccio** (testa tonda, foglie tenere, es. trocadero, regina di maggio), **romana** (testa allungata, croccante, es. romana bionda), **lollo** (riccia, rossa o verde), **iceberg** (cuore compatto e croccante), **da taglio** (foglie giovani raccolte ripetutamente). Conoscere la tipologia è essenziale perché ognuna ha esigenze diverse di temperatura e tempo di coltivazione.

## Semina e trapianto
- Semina possibile praticamente tutto l'anno sulla costa centro-italiana, variando varietà secondo stagione
- Diretta o in semenzaio (più comune): 4-5 settimane dalla semina al trapianto
- Profondità minima: il seme germina meglio con poca terra sopra
- Distanze: 25-30 cm sulla fila, 30 cm tra le file. Per le da taglio più stretto (15 × 20)
- Semine scalari ogni 20 giorni per non avere mai "buchi" di insalata

## Cura
- Esposizione: sole pieno in autunno-inverno-primavera. In piena estate **ombreggiamento parziale** o consociazione sotto piante alte (pomodoro, mais), altrimenti monta a seme
- Irrigazione: regolare e abbondante. La lattuga è composta al 95% di acqua: bagna spesso a goccia
- Pacciamatura organica fondamentale per umidità
- Concimazione: compost in preparazione, eventualmente macerato di ortica leggero in copertura
- **Andata a seme** (montata): pianta sale a fiore (uno stelo centrale fiorisce), foglie diventano amare. Cause: caldo eccessivo, sbalzi termici, varietà tardive piantate fuori stagione

## Avversità tipiche
- **Lumache e limacce**: il problema numero uno in primavera. Cenere intorno alla pianta, gusci d'uovo, trappole di birra, ferofermoni, raccolta serale, anatre se possibile
- **Afidi**: colonie verdi sotto le foglie. Sapone molle, ortica, predatori
- **Marciumi del colletto**: ristagni d'acqua e troppa umidità. Pacciamatura asciutta sotto il cespo
- **Sclerotinia**: marciume gelatinoso, eliminare piante colpite e ruotare
- **Peronospora della lattuga** (Bremia lactucae): macchie giallastre angolari sopra, muffetta sotto. Arieggiare, rame in casi gravi
- **Tip-burn**: bordi foglie bruniti, sbalzo idrico o carenza calcio

## Raccolta e conservazione
- **Lattughe a cespo**: si taglia al colletto quando il cespo è pieno e ben formato
- **Lattughe da taglio**: si raccolgono le foglie esterne progressivamente, la pianta ricaccia per 4-6 settimane (taglio-e-ricresce)
- Mai raccogliere durante le ore calde: foglie appassite
- Conservazione: 3-5 giorni in frigo, intera in busta forata o con base del cespo in acqua

## Consociazioni e rotazioni
- **Compagne**: carota (sfrutta diversi strati di terreno), cipolla, ravanello, fragola (sotto), cetriolo, cavolo (sopra). In generale ottima riempitiva
- **Da evitare**: sedano, prezzemolo (stessa famiglia di amici), girasole (allelopatia)
- **Rotazione**: 3 anni per le asteracee (lattuga, radicchio, indivia)

## Note clima costiero
Sulla costa centro-italiana la lattuga si coltiva 12 mesi su 12 con la giusta varietà: invernali (canasta, brune, regina d'inverno) per dicembre-marzo, primaverili (regina di maggio, trocadero) per aprile-giugno, estive resistenti alla montata (romana estate, batavia) sotto ombreggiatura, autunnali per ottobre-novembre. Salinità ben tollerata.

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
- [[primavera]] · [[estate]] · [[autunno]] · [[inverno]]

#pianta #orticola #asteracee #foglia
