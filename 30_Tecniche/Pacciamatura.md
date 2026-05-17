---
tipo: tecnica
titolo: Pacciamatura
area: suolo
difficolta: 1
tempo_richiesto: "Annuale: 1-2 ore per parcella; ricarica: 30 min ogni 2 mesi"
stagione: "Primavera (organica al trapianto); Autunno (per inverno)"
materiali:
  - Paglia
  - Sfalci d'erba secchi
  - Foglie sminuzzate
  - Trinciato di rami
  - Cartone non patinato
  - Tessuto non tessuto biodegradabile
strumenti:
  - Forca
  - Carriola
  - Forbici / cesoie
tags:
  - tecnica
  - suolo
  - pacciamatura
---

# 🌾 Pacciamatura

> Area: `=this.area` · Difficoltà: `=this.difficolta`/5 · Tempo: `=this.tempo_richiesto`

## A cosa serve
Coprire il suolo nudo con uno strato di materiale (organico o inerte) per imitare la "lettiera" naturale del bosco. Benefici cumulati: riduce evaporazione (chiave per estati costiere), mantiene la terra fresca e umida, abbatte la nascita di erbacce, protegge la fauna del suolo dagli sbalzi termici, restituisce sostanza organica (se organica), riduce le bagnature, evita la formazione di crosta in superficie. In clima mediterraneo costiero la pacciamatura non è opzionale: è la differenza tra orto in salute e orto sofferente.

## Quando farla
- Stagione: primavera al trapianto per estive (pomodoro, melanzana, peperone, cucurbitacee); autunno per proteggere il suolo invernale e nutrire microfauna
- Spessore: 5-10 cm per pacciamatura organica fine, 15-20 cm con cartone sottostante per copertura più aggressiva
- Ricarica: ogni 1-2 mesi nelle parcelle più "vorace" (zucchine, anguria), al bisogno per le altre

## Materiali e strumenti
- **Paglia**: la più classica, ottima per pomodori e cucurbitacee
- **Sfalci d'erba secchi** (lasciati appassire 2-3 giorni prima di stenderli, mai freschi: marciscono): comodi e gratis
- **Foglie sminuzzate** in autunno: ottime per perenni e alberi da frutto
- **Trinciato di rami**: ottimo intorno agli alberi da frutto, durata 2-3 anni
- **Cartone non patinato** come strato base: blocca erbacce, si decompone in 6-12 mesi
- **No** pacciame chimico (telo plastica nero) per orto biologico: utile in alcuni casi ma non sostenibile
- **Alghe spiaggiate**: sulla costa una risorsa preziosa, sciacquare dal sale, lasciar asciugare, usare in strati sottili

## Procedimento
1. **Preparazione**: terreno sarchiato e umido (la pacciamatura "blocca" lo stato in cui trovi il terreno: se è secco, lo lascia secco)
2. **Cartone (opzionale)**: stendere un singolo strato sovrapposto sui bordi, bagnare bene
3. **Materiale organico**: distribuire uniformemente 5-10 cm sopra il cartone (o direttamente a terra)
4. **Distanze**: lasciare 5 cm di terra nuda attorno al colletto delle piante (evita marciumi del colletto)
5. **Ricarica**: man mano che il materiale si decompone, aggiungerne altro in superficie

## Accorgimenti per il clima costiero
Sulla costa centro-italiana la pacciamatura **è essenziale in estate**: senza, le piante soffrono evaporazione massiva. Una pacciamatura di paglia da 10 cm può ridurre del 50-70% il fabbisogno irriguo estivo. Attenzione al vento marino: pacciami leggeri (paglia secca, foglie) volano. Soluzioni: bagnare bene il pacciame appena steso, mettere sopra qualche tralcio o rete leggera, scegliere materiali più pesanti (trinciato di rami) in zone esposte. Salsedine sui materiali da spiaggia: sciacquare prima di usare.

## Errori comuni
- Pacciame troppo sottile (<3 cm): inutile contro erbacce ed evaporazione
- Sfalci freschi e umidi: marciscono e puzzano, attirano patogeni
- Pacciame addossato al colletto della pianta: causa marciume del colletto
- Pacciamare su terreno secco: si mantiene secco
- Cartone con scritte colorate, plastificato, lucido: contiene inchiostri e plastiche
- Solo cartone senza copertura: si secca e si solleva al vento

## Piante / situazioni in cui si applica
- **Quasi tutte le colture orticole**: tutte le solanacee, cucurbitacee, brassicacee, foglia
- Alberi da frutto: trinciato di rami al piede, durata 2-3 anni
- Aiuole di aromatiche perenni
- Vigneto: pacciamatura tra i ceppi per controllare erbacce
- Aiuole ornamentali

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
- [[Compostaggio]]
- [[Irrigazione_a_Goccia]]

#tecnica #suolo #pacciamatura
