---
tipo: scheda_pianta
categoria: orticola
nome_comune: Pomodoro
nome_scientifico: Solanum lycopersicum
famiglia: Solanaceae
ciclo: annuale
periodo_semina: "Febbraio-Marzo (semenzaio); Aprile-Maggio (trapianto)"
periodo_raccolta: "Luglio-Ottobre"
distanza_pianta_cm: 50
distanza_fila_cm: 90
profondita_semina_cm: 0.5
esposizione: sole pieno
ph_min: 6.0
ph_max: 6.8
fabbisogno_idrico: alto (ma evitare ristagni)
difficolta: 3
consociazioni_buone:
  - Basilico
  - Carota
  - Sedano
  - Prezzemolo
  - Cipolla
  - Aglio
  - Tagete
consociazioni_da_evitare:
  - Cavoli
  - Finocchio
  - Patata
  - Mais
successioni_buone:
  - Legumi (fagiolo, fava)
  - Cereali
predecessori_da_evitare:
  - Solanacee (melanzana, peperone, patata)
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Subirrigazione]]"
tags:
  - pianta
  - orticola
  - solanacee
---

# 🥬 Pomodoro

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Ortaggio principe dell'estate mediterranea. Pianta a portamento determinato (cespuglioso, autolimitante) o indeterminato (continua a crescere, va legato e cimato). Per costa centro Italia le varietà locali da provare sono ottime: cuore di bue, San Marzano, costoluto fiorentino, riccio di Parma, principe borghese (da serbo). Le determinate sono comode in pieno campo (zero sostegni), le indeterminate rendono di più nello spazio ma vogliono palo o spago verticale.

## Semina e trapianto
- Semenzaio caldo (18-24°C) tra fine febbraio e marzo, in vasetti da 8 cm
- Trapianto in pieno campo quando le minime stanno sopra 10-12°C, di solito metà aprile a maggio sulla costa
- Profondità di trapianto: interrare fino alle prime foglie, le radici nuove escono dal fusto e rafforzano la pianta
- Distanze: 50 cm sulla fila per le determinate, 60-70 cm per le indeterminate, 90-100 cm tra le file

## Cura
- Esposizione: sole pieno; sulla costa attenzione ai venti forti, conviene un frangivento o palificazione robusta
- Irrigazione: a goccia al piede, mai sulle foglie (la peronospora ringrazia). Più frequente in attecchimento, poi profonda e distanziata (anche ogni 3-4 giorni) per indurre radici fonde
- Pacciamatura organica (paglia, sfalci) da subito dopo il trapianto: trattiene umidità, riduce schizzi di terra (vettore di malattie), tiene erba a bada
- Concimazione: letame maturo o compost nella buca di trapianto; macerato di consolida o ortica in copertura a inizio fioritura
- Cimatura femminelle (i getti tra fusto e ramo) per le indeterminate; cima centrale a 5-7 palchi a metà agosto per spingere maturazione
- Defogliazione bassa al primo grappolo che sta cambiando colore: arieggia e accelera maturazione

## Avversità tipiche
- **Peronospora** (Phytophthora infestans): il rischio numero uno con umidità marina e rugiada. Prevenire con pacciamatura, irrigazione al piede, sesti larghi, defogliazione bassa. Rame in poltiglia bordolese a calendario o ai primi segnali (massimo 4 kg/ha/anno in biologico)
- **Tuta absoluta** (tignola): mine fogliari serpentine e fori sui frutti. Trappole a feromone, Bacillus thuringiensis aizawai, eliminazione foglie infestate
- **Oidio**: patina bianca sulle foglie. Zolfo bagnabile a temperature sotto 28°C
- **Alternaria**: macchie scure concentriche. Rame
- **Marciume apicale** (fisiopatia): macchia nera sul culo del frutto, è carenza di calcio dovuta a irrigazione irregolare. Si previene mantenendo umidità costante e pacciamando
- **Cracking** (spaccature): irrigazione irregolare dopo periodo secco. Vale la stessa cura
- **Afidi, ragnetto rosso, cimice asiatica**: macerati di ortica e aglio, sapone molle, predatori naturali

## Raccolta e conservazione
- Periodo: `=this.periodo_raccolta`
- Indici: colore pieno della varietà, leggera cedevolezza al tatto. Per il sugo si raccoglie a piena maturazione; per insalata anche un filo prima
- Conservazione: fresco 3-5 giorni a temperatura ambiente (mai in frigo, perde sapore). Trasformazione: pelati, passata, conserva, essiccato al sole o al forno, sott'olio
- Da serbo: varietà come il principe borghese si conservano appesi in mazzi fino all'inverno

## Consociazioni e rotazioni
- **Compagne buone**: basilico (storica, sembra migliorare aroma e respinge alcuni parassiti), cipolla e aglio (effetto antifungino), carota e sedano (sfruttano strati diversi del suolo), tagete (nematodi)
- **Da evitare**: cavoli (competizione e malattie comuni), finocchio (allelopatico), altre solanacee
- **Rotazione**: minimo 3 anni prima di rimettere solanacee sulla stessa parcella; ottimo predecessore per legumi, ottimo successore di legumi e cereali

## Note clima costiero
La salsedine in sé è tollerata dal pomodoro, ma il vento forte spezza i palchi: serve palificazione solida o frangivento (canne, rete frangivento, siepe). L'umidità notturna marina favorisce peronospora: arieggiare il filare, sfoltire la vegetazione bassa, evitare bagnature serali. L'irraggiamento intenso da giugno in poi può scottare i frutti se la pianta è troppo spogliata in basso: mantenere copertura fogliare laterale dalle ore più calde.

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Subirrigazione]]
- [[primavera]] · [[estate]]

#pianta #orticola #solanacee
