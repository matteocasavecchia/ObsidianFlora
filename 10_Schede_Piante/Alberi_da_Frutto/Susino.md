---
tipo: scheda_pianta
categoria: albero_da_frutto
nome_comune: Susino
nome_scientifico: Prunus domestica (europeo) / Prunus salicina (cino-giapponese)
famiglia: Rosaceae
periodo_raccolta: "Giugno-Settembre (secondo varietà)"
periodo_potatura: "Gennaio-Febbraio (secca); Estate (verde post-raccolta)"
forma_allevamento: "Vaso o palmetta"
portainnesto_consigliato: "Mirabolano (rustico, generale); GF8-1 (per vigoria controllata)"
esposizione: sole pieno
resistenza_salsedine: media
resistenza_freddo: "-15°C pianta; gelate primaverili rischiose per fiori"
entrata_in_produzione_anni: 4
autofertile: parziale
impollinatori_richiesti: "Variabile (europei spesso autofertili, giapponesi quasi sempre richiedono impollinatore)"
sesto_impianto_m: "4 × 5"
tags:
  - albero
  - drupacee
  - rosaceae
---

# 🟣 Susino

> Famiglia: `=this.famiglia` · Raccolta: `=this.periodo_raccolta` · Potatura: `=this.periodo_potatura`

## Caratteristiche
Due grandi gruppi: **susini europei** (Prunus domestica), polpa soda, ricchi di zuccheri, buoni anche da essiccare in prugne secche. Varietà classiche: Stanley (blu allungato, classico), Regina Claudia (verde, dolcissimo), Goccia d'Oro (gialla), Sangue di Drago (rosso interno ed esterno). **Susini cino-giapponesi** (Prunus salicina), frutto più tondo, polpa succosa, maturazione precoce. Varietà: Shiro, Methley, Santa Rosa, Black Diamond. I cino-giapponesi maturano da giugno, gli europei da luglio a settembre.

## Impianto
- Esposizione: sole pieno
- Sesto: 4 × 5 m (vaso); 3 × 4 m (palmetta)
- Portainnesto: mirabolano (Prunus cerasifera) è il classico, rustico e adatto a vari terreni
- Periodo: novembre-marzo a radice nuda
- Buca: 60 × 60 × 60 cm
- Ammendanti: compost maturo, cornunghia. No letame fresco

## Cura annuale
- Concimazione: ottobre-novembre con compost al piede + cornunghia
- Irrigazione: di soccorso in estate, soprattutto giovani esemplari e in formazione frutti. Stress idrico = caduta frutti
- Pacciamatura organica al piede
- Spollonatura: il susino ricaccia molto dalla base (anche dal portainnesto, mirabolano)
- **Diradamento frutti**: se carico, diradare a frutto nocciolo formato (1 frutto ogni 5-7 cm) per migliorare calibro

## Potatura
- **Asciutta** (gennaio-febbraio): formazione e mantenimento vaso. Eliminare rami secchi, succhioni, rami incrociati
- **Verde estiva** (post-raccolta, luglio-agosto): si tagliano rami in eccesso, succhioni, si "apre" la chioma. Questa potatura limita la gommosi (taglio in fase di vegetazione attiva, ferite asciutte)
- Il susino fruttifica su rami di 1-3 anni e su brindilli; mantenere ricambio
- **Importante**: mai potare sotto la pioggia o con tempo umido (gommosi), preferibilmente in giornate asciutte e soleggiate

## Impollinazione e produzione
- **Susini europei**: molti autofertili (Stanley, Regina Claudia), ma rendono di più con impollinatore
- **Cino-giapponesi**: quasi sempre richiedono impollinatore di stessa fioritura
- Verificare con vivaio le combinazioni compatibili
- Fioritura: marzo-aprile (cino-giapponesi prima, europei dopo)
- Entrata in produzione: 3-4 anni
- Produzione adulta: 30-80 kg per pianta

## Avversità tipiche
- **Monilia** (Monilinia fructicola, M. laxa): la più seria, marciume bruno dei frutti, disseccamento dei rami fioriferi. Rame in poltiglia bordolese a fine inverno e dopo le fioriture, eliminare frutti mummificati (focolaio di infezione)
- **Vaiolatura** (Plum Pox Virus, sharka): virus serio, foglie maculate, frutti deformati. Pianta da eliminare se confermato. Lavorare con materiale certificato
- **Cidia del susino** (Cydia funebrana): larve nei frutti. Trappole feromoni, Bacillus thuringiensis
- **Afide cenerino**: foglie accartocciate. Sapone molle, predatori
- **Gommosi**: essudazione di gomma da ferite. Evitare tagli in periodo umido, disinfettare attrezzi

## Resistenza al contesto costiero
Salsedine tolleranza media. Resistenza al freddo alta (pianta), ma la **fioritura precoce di marzo** è esposta alle gelate tardive. Sulla costa centro-italiana gli inverni miti rendono il rischio gelate tardive minore: pianta adatta. Il vento marino non è particolarmente dannoso. Suolo ben drenato (i susini soffrono ristagni).

## Raccolta e conservazione
- A piena maturazione (colore pieno, leggero distacco al tocco). Maturare in pianta dà la massima qualità
- Forbice o stacco a mano con leggera torsione
- Conservazione: 1-2 settimane in frigo (susini europei migliori conservatori). 5-7 giorni a temperatura ambiente
- Trasformazione: marmellata, prugne secche (essiccazione in forno o essiccatore), sotto spirito, sciroppo, slivovica

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
- [[primavera]] · [[estate]] · [[inverno]]

#pianta #albero_da_frutto #drupacee
