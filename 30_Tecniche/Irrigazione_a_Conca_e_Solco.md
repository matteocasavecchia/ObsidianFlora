---
tipo: tecnica
titolo: Irrigazione a conca e a solco (scorrimento)
area: acqua
difficolta: 1
tempo_richiesto: "Realizzazione: 1-2 ore; manutenzione: rifare conche/solchi a stagione"
stagione: primavera-estate
materiali:
  - Acqua a caduta (rubinetto, serbatoio, pozzo)
  - Eventuale tubo o canaletta di adduzione
  - Pacciamatura per la conca
strumenti:
  - Zappa e rastrello
  - Vanga per i solchi
tags:
  - tecnica
  - acqua
  - irrigazione
---

# 💧 Irrigazione a conca e a solco (scorrimento)

> Area: `=this.area` · Difficoltà: `=this.difficolta`/5 · Tempo: `=this.tempo_richiesto`

## A cosa serve
Sono i metodi tradizionali a gravità, senza impianto in pressione. La **conca** è una vasca di terra ricavata attorno al fusto dell'albero, che si riempie d'acqua e la lascia infiltrare lentamente in profondità. Il **solco** è un canaletto scavato tra le file degli ortaggi, in cui l'acqua scorre e si infiltra lateralmente verso le radici. Sono utili dove non c'è corrente né pressione, per pochi alberi isolati, o come integrazione di una bagnatura profonda occasionale. L'efficienza è più bassa (40-60%) per evaporazione e percolazione, ma il costo è quasi nullo.

## Quando farla
- Realizzazione: a inizio stagione calda, o al trapianto degli alberi
- Funzionamento: bagnature abbondanti e distanziate (la conca riempita una volta equivale a molta acqua in profondità)
- Rifare le conche/solchi dopo piogge intense o lavorazioni che li spianano
- Nelle ore fresche, per limitare l'evaporazione dalla superficie libera dell'acqua

## Materiali e strumenti
- **Acqua a caduta**: rubinetto, serbatoio rialzato, canaletta o tubo che porti l'acqua al punto
- **Zappa e rastrello** per modellare conche e arginelli
- **Vanga** per aprire i solchi tra le file
- **Pacciamatura** da stendere nella conca dopo la bagnatura, per rallentare l'evaporazione

## Procedimento
1. **Conca attorno all'albero**: formare un arginello circolare di terra alla proiezione della chioma (dove stanno le radici assorbenti), non a ridosso del tronco
2. **Riempimento**: riempire la conca d'acqua e lasciarla infiltrare; ripetere se serve una bagnatura profonda
3. **Solco tra le file**: scavare un canaletto poco profondo lungo la fila, leggermente in pendenza per far scorrere l'acqua
4. **Adduzione**: far entrare l'acqua a monte del solco e lasciarla scorrere fino a fine fila
5. **Dopo la bagnatura**: pacciamare conca e solco per trattenere l'umidità e ridurre la crosta superficiale
6. **Controllo**: scavare per verificare che l'acqua sia arrivata in profondità e non solo in superficie

## Accorgimenti per il clima costiero
A vantaggio: nessun ugello da intasare, quindi l'acqua calcarea non crea problemi di impianto. La bagnatura profonda e distanziata è ideale per spingere le radici degli alberi giù, lontano dalla salsedine superficiale e dal secco estivo. Limiti: la superficie libera dell'acqua evapora molto sotto sole e vento marino, quindi conviene bagnare presto al mattino e pacciamare subito. Su terreni sabbiosi costieri l'acqua percola in fretta: conche più piccole e ripetute meglio di una grande.

## Errori comuni
- Conca a ridosso del tronco: favorisce marciumi del colletto; va fatta alla proiezione della chioma
- Bagnature superficiali e frequenti: radici pigre in superficie, pianta fragile in estate
- Niente pacciamatura dopo: crosta dura e forte evaporazione
- Solchi senza pendenza: l'acqua ristagna a monte e non arriva a fine fila
- Su terreno sabbioso conche troppo grandi: l'acqua percola oltre le radici

## Piante / situazioni in cui si applica
- Alberi da frutto e agrumi isolati, soprattutto giovani
- Olivo e piante rustiche da bagnatura occasionale
- Orto tradizionale senza impianto in pressione
- Situazioni di emergenza o integrazione (riempire le conche con acqua di recupero)

### Schede pianta collegate
```dataview
LIST
FROM "agricoltura/10_Schede_Piante"
WHERE contains(tecniche_irrigazione, this.file.link)
SORT file.name ASC
```

## Diario di campo collegato
```dataview
TABLE file.name AS "Nota", meteo AS "Meteo"
FROM "agricoltura/40_Diario"
WHERE contains(interventi, this.file.link) OR contains(file.outlinks, this.file.link)
SORT file.name DESC
LIMIT 10
```

## Riferimenti
- [[Irrigazione_Panoramica]]
- [[_MOC_Tecniche]]
- [[Pacciamatura]]
- [[Swale_Canali_Infiltrazione]]

#tecnica #acqua #irrigazione
