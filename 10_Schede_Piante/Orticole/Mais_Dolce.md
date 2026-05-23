---
tipo: scheda_pianta
categoria: orticola
nome_comune: Mais dolce
nome_scientifico: Zea mays var. saccharata
famiglia: Poaceae
ciclo: annuale
periodo_semina: "Aprile-Giugno"
periodo_raccolta: "Luglio-Settembre"
distanza_pianta_cm: 25
distanza_fila_cm: 70
profondita_semina_cm: 4
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.0
fabbisogno_idrico: alto
difficolta: 2
consociazioni_buone:
  - Fagiolo rampicante
  - Zucca
  - Cetriolo
  - Tagete
  - Lattuga (sotto)
consociazioni_da_evitare:
  - Pomodoro (stessa famiglia di parassiti)
  - Sedano
successioni_buone:
  - Legumi
  - Cucurbitacee
predecessori_da_evitare:
  - Cereali (mais, frumento)
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - poaceae
  - cereali
---

# 🌽 Mais dolce

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Mais selezionato per il consumo fresco delle pannocchie tenere, ricco di zuccheri. Diverso dal mais "duro" da farina/polenta o da insilato. Varietà classiche: golden bantam (vecchia varietà a chicco giallo), butter & sugar (chicchi gialli + bianchi), sweetcorn ibridi. Pianta a impollinazione anemofila (vento): per buona allegagione va piantato in **blocchi quadrati di almeno 4 × 4 piante**, mai in singola fila.

## Semina e trapianto
- Solo semina diretta, su terreno sopra i 12°C
- Aprile-giugno, scalare ogni 20 giorni per produzione continua
- Profondità: 4-5 cm
- Distanze: 25-30 cm sulla fila, 70 cm tra le file
- **Disposizione a blocchi quadrati** non a singola fila (impollinazione)
- Compost o letame maturo nella buca

## Cura
- Esposizione: sole pieno
- Irrigazione: regolare durante crescita, **fondamentale in fioritura e formazione pannocchia**. Goccia al piede, mai sulle foglie
- Pacciamatura organica spessa
- Concimazione: il mais è ingordo di azoto. Macerato di ortica in copertura ogni 3 settimane (anche se in consociazione con fagiolo si riduce)
- **Rincalzo** alla base della pianta a 30-40 cm di altezza: protegge da vento e favorisce radici avventizie
- Eliminare polloni laterali se compaiono

## Avversità tipiche
- **Piralide del mais** (Ostrinia nubilalis): la nemica numero uno. Larve nelle pannocchie. Bacillus thuringiensis kurstaki appena visibili larve giovani, trappole feromoni per monitoraggio
- **Diabrotica del mais**: larve nelle radici. Rotazione lunga
- **Afidi del mais**: sapone molle, predatori
- **Carbone del mais** (Ustilago maydis): galle nere sulle pannocchie. Eliminare piante colpite (in Messico è considerato un fungo prelibato, "huitlacoche")
- **Allettamento da vento**: rincalzo alla base + blocco quadrato (le piante si supportano a vicenda)

## Raccolta e conservazione
- Quando i **stigmi** ("seta" alla cima della pannocchia) sono **secchi e bruni**, pannocchia ben formata e gonfia
- Test del chicco: bucare un chicco con l'unghia, deve uscire liquido **lattiginoso** (non chiaro = ancora acerbo, non pastoso = già passato)
- Raccolta a mano, torcere e tirare
- **Consumo immediato** (entro 24-48 ore): gli zuccheri si trasformano rapidamente in amidi dopo la raccolta. Stessa tradizione del mais sweetcorn americano: dalla pianta alla pentola velocemente
- Conservazione: 1-2 giorni in frigo. Sbianchito e congelato (chicchi sgranati) ottimo

## Consociazioni e rotazioni
- **Tre sorelle**: mais + fagiolo rampicante (sale sul mais, fornisce azoto) + zucca (copre il suolo). Sistema antico ed efficace
- **Compagne**: cetriolo (sotto), tagete, lattuga di primavera prima che il mais chiuda l'ombra
- **Da evitare**: pomodoro (entrambi attaccati dalla piralide), sedano
- **Rotazione**: 3-4 anni per cereali nella stessa parcella

## Note clima costiero
Coltura ben adatta alla costa centro-italiana, calda e con buona pioggia primaverile. Tolleranza salsedine media. **Il vento marino può essere problema serio**: piante alte 2 m, fragili, si abbattono. Rincalzo, blocco quadrato e impianto a ridosso di frangivento sono le difese. Salinità del suolo (in zone molto vicine al mare) può ridurre resa: il mais non è tra le piante più tolleranti.

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
- [[primavera]] · [[estate]]

#pianta #orticola #cereali
