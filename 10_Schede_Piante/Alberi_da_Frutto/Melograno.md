---
tipo: scheda_pianta
categoria: albero_da_frutto
nome_comune: Melograno
nome_scientifico: Punica granatum
famiglia: Lythraceae
periodo_raccolta: "Settembre-Novembre"
periodo_potatura: "Febbraio-Marzo"
forma_allevamento: "Cespuglio o vaso aperto"
portainnesto_consigliato: "Da talea (no innesto)"
esposizione: sole pieno
resistenza_salsedine: alta
resistenza_freddo: "-12°C circa"
entrata_in_produzione_anni: 2
autofertile: true
impollinatori_richiesti: "Nessuno (produzione migliora con varietà diverse)"
sesto_impianto_m: "4 × 5"
tags:
  - albero
  - lythraceae
---

# 🍎 Melograno

> Famiglia: `=this.famiglia` · Raccolta: `=this.periodo_raccolta` · Potatura: `=this.periodo_potatura`

## Caratteristiche
Pianta cespugliosa o piccolo albero, originaria dell'Asia centrale, naturalizzata in tutto il Mediterraneo da millenni. Fiori rosso vivo (arancione, bianchi in alcune varietà) spettacolari, frutti rotondi a buccia coriacea con migliaia di "arilli" (granelli) succosi e zuccherini. Varietà classiche: **Wonderful** (americana, frutto grosso, sapore deciso), **Mollar de Elche** (spagnola, dolce, arilli teneri), **Dente di Cavallo** (italiana, arilli grossi), **Tunisian** (Acco), **Hicaz**. Pianta multifunzionale: frutti, fiori ornamentali, siepe ornamentale o difensiva (rami spinosi nelle varietà selvatiche).

## Impianto
- Esposizione: sole pieno
- Sesto: 4 × 5 m. Coltivabile anche come singolo o in gruppo
- Propagazione: per **talea** (autunno-inverno, semplice). Anche da seme ma con risultati incerti
- Periodo: novembre-marzo
- Buca: 50 × 50 × 50 cm
- Ammendanti: compost. Pianta poco esigente

## Cura annuale
- Concimazione: minima, compost a fine inverno
- Irrigazione: di soccorso in estate, soprattutto giovani esemplari. Pianta tollerante alla siccità una volta affrancata
- Pacciamatura utile
- Spollonatura: il melograno ricaccia molto dalla base, in coltura ad albero (vaso) si eliminano i polloni; in coltura a cespuglio si conservano

## Potatura
- Periodo: febbraio-marzo
- **Coltivazione a cespuglio**: si tagliano rami secchi, polloni vecchi (anni 4+), si rinnova la base. Forma più rustica e produttiva
- **Coltivazione ad albero**: vaso aperto, eliminazione polloni alla base, sfoltimento interno
- Tagli leggeri: il melograno fruttifica all'apice dei rami dell'anno precedente, tagli eccessivi riducono raccolto
- Eliminare rami fragili o storti

## Impollinazione e produzione
- Autofertile, ma la presenza di varietà diverse migliora produzione
- Fioritura: maggio-luglio (lunga e scalare)
- Entrata in produzione: 2-3 anni (rapido)
- Produzione adulta: 30-60 kg per pianta
- I frutti che si formano dai primi fiori sono i più grossi e dolci

## Avversità tipiche
- **Mosca del melograno** (Ceratitis capitata): larva nel frutto, fermentazione. Trappole proteiche, caolino, raccolta tempestiva
- **Afide del melograno** (Aphis punicae): colonie verdi sulle cime tenere. Sapone molle, predatori
- **Cocciniglia**: olio bianco minerale in inverno
- **Spaccatura dei frutti**: irregolarità irrigua a fine ciclo, soprattutto dopo periodo secco seguito da pioggia. Pacciamatura, irrigazione regolare
- **Marciume del frutto**: in autunno piovoso, frutti maturi che marciscono in pianta. Raccolta tempestiva
- Pianta generalmente molto rustica e poco soggetta a malattie serie

## Resistenza al contesto costiero
**Pianta perfetta per costa mediterranea**: tollera salsedine alta, vento, siccità, terreni poveri e calcarei. Resistenza al freddo buona (-12°C). Praticamente nessun limite serio per la costa centro-italiana. Anche bellissima come pianta ornamentale (siepi miste, esemplari isolati con fioritura rosso fuoco).

## Raccolta e conservazione
- Indici: buccia ben colorata (rossa, gialla con sfumature rosa secondo varietà), suono "metallico" a percussione. Spaccatura della buccia indica frutto pronto o leggermente troppo maturo
- Forbice
- **Eccellente conservabilità**: 2-3 mesi in cantina fresca e asciutta, fino a 6 mesi in frigo
- Trasformazione: succo (sgranare e premere senza spremere i semi che danno amaro), granatina (sciroppo zuccherato), salse (Medio Oriente), liquore, arilli congelati interi

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
- [[estate]] · [[autunno]] · [[inverno]]

#pianta #albero_da_frutto
