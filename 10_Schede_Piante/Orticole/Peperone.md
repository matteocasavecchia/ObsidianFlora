---
tipo: scheda_pianta
categoria: orticola
nome_comune: Peperone
nome_scientifico: Capsicum annuum
famiglia: Solanaceae
ciclo: annuale
periodo_semina: "Febbraio-Marzo (semenzaio caldo); Maggio (trapianto)"
periodo_raccolta: "Luglio-Ottobre"
distanza_pianta_cm: 40
distanza_fila_cm: 70
profondita_semina_cm: 0.5
esposizione: sole pieno (protetto da vento)
ph_min: 6.0
ph_max: 6.8
fabbisogno_idrico: medio-alto, regolare
difficolta: 3
consociazioni_buone:
  - Basilico
  - Carota
  - Cipolla
  - Tagete
  - Lattuga
consociazioni_da_evitare:
  - Altre solanacee
  - Finocchio
  - Fagiolo (controverso)
successioni_buone:
  - Legumi
  - Cucurbitacee (con rotazione)
predecessori_da_evitare:
  - Solanacee
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Subirrigazione]]"
tags:
  - pianta
  - orticola
  - solanacee
---

# 🌶️ Peperone

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Pianta più delicata e capricciosa delle altre solanacee, ma molto produttiva quando trova le sue condizioni. Esige caldo costante e protezione dai venti forti. Varietà classiche: corno di toro (rosso/giallo), quadrato d'Asti, friggitello, peperoncino di Senise, di Carmagnola. Esistono ibridi più robusti per chi parte con poca esperienza.

## Semina e trapianto
- Germinazione lenta e a temperatura alta (24-28°C), semenzaio caldo da fine febbraio
- Le piantine crescono adagio: 10-12 settimane fino al trapianto
- Trapianto solo con minime stabilmente sopra 14°C, sulla costa metà-fine maggio
- Distanze più strette delle altre solanacee: 40 cm sulla fila, 70 cm tra le file
- Buca con compost o letame maturo

## Cura
- Esposizione: sole pieno ma protetto dal vento forte (i rami sono fragili, si spezzano carichi)
- Irrigazione: regolare a goccia, mai sulle foglie. Stress idrico = caduta fiori e frutti
- Pacciamatura organica indispensabile
- Concimazione: macerato di ortica/consolida ogni 3 settimane in fioritura
- Tutore singolo per ogni pianta, robusto
- Cimatura: si tolgono i primi fiori (a "Y") per favorire sviluppo vegetativo, poi si lascia fruttificare. Sfemminellatura come pomodoro per varietà a frutto grande
- Pacciamatura riflettente (paglia chiara) aiuta a tenere fresche le radici nelle estati torride

## Avversità tipiche
- **Piralide (Ostrinia nubilalis)**: larva penetra nel frutto. Bacillus thuringiensis kurstaki sulle larve giovani, trappole feromoni per monitoraggio
- **Afidi**: vettori di virosi, sapone molle, macerato di ortica/aglio, predatori
- **Ragnetto rosso**: caldo secco, nebulizzazioni e predatori
- **Marciume apicale**: come pomodoro, irrigazione regolare e calcio
- **Scottature solari sui frutti**: paradossalmente troppo sole su pianta defogliata può bruciare la buccia. Mantenere copertura fogliare
- **Oidio, alternaria, virosi**: prevenzione con rotazioni, eliminazione piante malate
- **Crollo della pianta da Phytophthora capsici**: tipico con ristagni. Drenaggio buono e mai eccedere con l'acqua

## Raccolta e conservazione
- Si può raccogliere verde (più sodo, meno dolce, più conservabile) o a colore pieno (rosso, giallo, arancione: massimo della dolcezza e vitamine)
- Tempo dal fiore al frutto verde: 30-40 giorni; al frutto colorato: altri 20-30 giorni
- Tagliare con forbice lasciando 2-3 cm di picciolo
- Conservazione: 1 settimana in frigo. Trasformazione: sott'aceto, sott'olio, peperonata, essiccati (peperone crusco), arrostiti e congelati

## Consociazioni e rotazioni
- **Compagne**: basilico (parassiti), carota e cipolla (livelli diversi del suolo), tagete (nematodi), lattuga (sfrutta lo spazio fresco di primavera)
- **Da evitare**: altre solanacee, finocchio. Sul fagiolo le opinioni sono divise (alcuni dicono ok, altri sostengono competizione)
- **Rotazione**: minimo 3-4 anni come per pomodoro e melanzana

## Note clima costiero
Coltura ideale per costa mediterranea **a patto che ci sia riparo dal vento**: i rami sono fragili e le folate marine spaccano la pianta. Frangivento, muretti, siepi o consociazione con piante più alte (mais, girasole come barriera) aiutano. Salsedine ben tollerata. Per le estati centro-italiane molto calde e secche, evitare esposizione a sud senza ombreggiamento parziale nelle ore centrali, altrimenti si rischiano scottature dei frutti.

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Subirrigazione]]
- [[primavera]] · [[estate]]

#pianta #orticola #solanacee
