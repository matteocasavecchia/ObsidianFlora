---
tipo: tecnica
titolo: Compostaggio
area: suolo
difficolta: 2
tempo_richiesto: "Avvio: 2-3 ore; gestione: 30 min/settimana"
stagione: tutto l'anno
materiali:
  - Scarti verdi (sfalci, foglie, ortaggi)
  - Scarti bruni (rami sminuzzati, paglia, cartone, foglie secche)
  - Letame maturo o compost vecchio (starter)
strumenti:
  - Composter (o cumulo libero, bins di pallet, casse fai-da-te)
  - Forca
  - Trinciasarmenti o cesoie
tags:
  - tecnica
  - suolo
  - compost
---

# 🍂 Compostaggio

> Area: `=this.area` · Difficoltà: `=this.difficolta`/5 · Tempo: `=this.tempo_richiesto`

## A cosa serve
Trasformare gli scarti organici dell'orto e della cucina in ammendante naturale. Il compost maturo è il pilastro della fertilità in agricoltura biologica: nutre le piante lentamente, struttura il terreno, alimenta la vita microbica del suolo, riduce l'uso di concimi esterni e i rifiuti domestici. Una compostiera attiva produce 100-300 kg di compost l'anno, sufficienti per un orto familiare.

## Quando farla
- Stagione: tutto l'anno
- Avvio della compostiera: idealmente primavera o autunno (clima mite favorisce la partenza dell'attività microbica)
- Rivolta del cumulo: ogni 4-6 settimane in stagione attiva (primavera-autunno), una volta a stagione in inverno
- Compost pronto: 4-12 mesi a seconda di gestione e clima (più caldo = più veloce)

## Materiali e strumenti
- **Verdi** (azoto): erba sfalciata, scarti freschi di cucina (bucce, torsoli, gusci di uova frantumati), foglie verdi, residui di potature verdi, [[Pollaio_e_Orto|pollina e lettiera usata del pollaio]] (potente attivatore azotato, da bilanciare con molti bruni)
- **Bruni** (carbonio): foglie secche, paglia, cartone non patinato in piccoli pezzi, rami sminuzzati, segatura di legno non trattato
- **Da evitare**: carne, pesce, latticini, oli (attirano ratti e fermentano male), erbe infestanti a seme maturo, piante malate, agrumi in grande quantità (acidificano)
- Strumenti: composter chiuso (in plastica o legno) o cumulo libero, forca per rivoltare, trinciatutto se molto verde sfalciato

## Procedimento
1. **Posizione**: angolo dell'orto in mezz'ombra, su terra (no cemento), facilmente accessibile
2. **Base drenante**: primo strato di rametti sminuzzati o paglia (10 cm) per arieggiare il fondo
3. **Alternanza strati**: aggiungere materiale verde e bruno alternati, in proporzione **1 parte verde : 2-3 parti bruno** (in volume)
4. **Umidità**: il cumulo deve essere come una spugna strizzata. Troppo secco rallenta, troppo umido marcisce (puzza di ammoniaca)
5. **Aerazione**: rivoltare ogni 4-6 settimane con la forca. Senza ossigeno il processo è anaerobico (lento e maleodorante)
6. **Starter**: una manciata di terra dell'orto o di compost vecchio velocizza l'avvio dei microorganismi
7. **Maturazione**: il compost è pronto quando ha consistenza terrosa, colore marrone scuro, odore di sottobosco, temperatura uguale all'ambiente

## Accorgimenti per il clima costiero
Le estati torride della costa centro-italiana asciugano il cumulo rapidamente: nei mesi caldi può essere necessario bagnare la compostiera 1-2 volte a settimana e tenerla coperta (tappo del composter o telo). L'umidità marina e le piogge autunnali aiutano molto la decomposizione: l'autunno è il momento più produttivo del compostaggio costiero. Salsedine: se si compostano alghe spiaggiate, sciacquarle prima per togliere il sale.

## Errori comuni
- Solo verde (sfalci d'erba): marcisce e puzza. Equilibrare sempre con bruni
- Materiale a pezzi grossi: rallenta enormemente. Sminuzzare cartone, rametti, scarti di cucina
- Compostiera in pieno sole: secca troppo, blocca il processo
- Cumulo troppo piccolo (<1 m³): non raggiunge le temperature necessarie alla fase termofila
- Aggiungere agrumi in massa: rallenta e acidifica
- Non rivoltare mai: si forma una "torta" anaerobica

## Piante / situazioni in cui si applica
- Tutte le colture orticole (compost in buca al trapianto)
- Pacciamatura nutritiva (strato fine in superficie)
- Concimazione autunnale di alberi da frutto
- Preparazione semenzai (compost setacciato, mescolato a terriccio)

## Diario di campo collegato
```dataview
TABLE file.name AS "Nota", meteo AS "Meteo"
FROM "agricoltura/40_Diario"
WHERE contains(interventi, this.file.link) OR contains(file.outlinks, this.file.link)
SORT file.name DESC
LIMIT 10
```

## Riferimenti
- [[_MOC_Tecniche]]
- [[Pacciamatura]]
- [[Sovesci]]
- [[Pollaio_e_Orto]] (uso della pollina)

#tecnica #suolo #compost
