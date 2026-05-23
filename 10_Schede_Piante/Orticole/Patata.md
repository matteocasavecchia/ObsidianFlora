---
tipo: scheda_pianta
categoria: orticola
nome_comune: Patata
nome_scientifico: Solanum tuberosum
famiglia: Solanaceae
ciclo: annuale
periodo_semina: "Febbraio-Marzo (messa a dimora tuberi); secondo raccolto Luglio-Agosto"
periodo_raccolta: "Maggio-Luglio (primaticce); Settembre-Ottobre (tardive e di secondo raccolto)"
distanza_pianta_cm: 30
distanza_fila_cm: 70
profondita_semina_cm: 10
esposizione: sole pieno
ph_min: 5.0
ph_max: 6.5
fabbisogno_idrico: medio-alto (regolare durante la tuberizzazione)
difficolta: 2
consociazioni_buone:
  - Fagiolo
  - Cavolo
  - Mais
  - Spinacio
  - Aglio
  - Tagete
consociazioni_da_evitare:
  - Pomodoro
  - Melanzana
  - Peperone
  - Zucca
  - Cetriolo
  - Girasole
successioni_buone:
  - Legumi
  - Cereali
  - Cucurbitacee
predecessori_da_evitare:
  - Solanacee (pomodoro, melanzana, peperone)
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - solanacee
---

# 🥔 Patata

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Tubero base dell'alimentazione, si moltiplica per **tuberi-seme** e non per seme botanico. La parte commestibile è il tubero (fusto modificato ipogeo); le bacche aeree e le parti verdi sono tossiche (solanina). Varietà per pasta soda (a buccia gialla, da insalata e padella: Spunta, Sieglinde, Kennebec) e farinose (da purè e gnocchi: Désirée, Majestic). Distinzione utile per ciclo: **primaticce** (ciclo breve, raccolta primaverile-estiva) e **tardive/da serbo** (raccolta autunnale, buona conservazione). Per la costa centro-italiana funzionano bene le primaticce, che chiudono il ciclo prima del caldo torrido.

## Semina e trapianto
- Periodo: `=this.periodo_semina`
- Profondità: tuberi a `=this.profondita_semina_cm` cm di profondità
- Distanze: `=this.distanza_pianta_cm` cm sulla fila, `=this.distanza_fila_cm` cm tra le file
- Modalità: si interrano tuberi-seme interi (calibro noce) o tagliati a pezzi con almeno 2 gemme ("occhi"), lasciati cicatrizzare 1-2 giorni. Pregermogliazione alla luce (2-4 settimane) anticipa e rinforza la partenza. Disporre con i germogli verso l'alto in solco

## Cura
- Esposizione: sole pieno
- Irrigazione: regolare soprattutto dalla formazione dei tuberi (dopo la fioritura). Stress idrico riduce la resa e favorisce la rugginosità; eccessi e ristagni causano marciumi. Sospendere prima della raccolta per far maturare la buccia
- Concimazione: terreno fertile e soffice; letame ben maturo (mai fresco, favorisce la scabbia), compost, ceneri (potassio). Evitare eccessi di azoto (molta foglia, pochi tuberi)
- **Rincalzo**: operazione chiave. Quando le piante raggiungono 20-25 cm si rincalza la terra al piede formando un colmo: stimola nuovi tuberi e li protegge dalla luce (i tuberi esposti inverdiscono e diventano tossici)
- Pacciamatura alternativa al rincalzo in orto familiare

## Avversità tipiche
- **Peronospora** (Phytophthora infestans): la malattia storica della patata, macchie brune su foglie e marciume dei tuberi, favorita da umidità. Rame preventivo, sesti arieggiati, varietà resistenti, raccolta tempestiva
- **Dorifora** (Leptinotarsa decemlineata): coleottero a strisce gialle e nere, le larve defogliano rapidamente. Raccolta manuale di adulti, uova e larve; Bacillus thuringiensis tenebrionis; spinosad
- **Tignola della patata** (Phthorimaea): gallerie nei tuberi, soprattutto in conservazione. Rincalzo curato, raccolta tempestiva, conservazione al buio e al fresco
- **Scabbia comune**: croste sulla buccia (estetiche), favorita da terreni alcalini e letame fresco. Mantenere pH sotto 6 e umidità costante in tuberizzazione
- **Elateridi (ferretti)** e **nematodi**: gallerie nei tuberi; rotazione e sovesci
- Note clima costiero: l'umidità marina favorisce la peronospora; puntare su cicli primaticci e trattamenti rameici preventivi nei periodi umidi

## Raccolta e conservazione
- Periodo: `=this.periodo_raccolta`
- Indici: per le novelle si raccoglie a pianta ancora verde (buccia sottile, da consumare subito); per la conservazione si attende il **disseccamento della parte aerea**, segno di buccia matura e resistente
- Raccolta con forca, in giornata asciutta; lasciare asciugare i tuberi qualche ora in campo, poi al riparo
- Conservazione: al **buio**, fresco (4-8 °C) e ventilato, mai in frigo domestico (sotto 4 °C gli amidi diventano zuccheri). Eliminare i tuberi feriti o verdi. Le varietà da serbo durano diversi mesi
- Trasformazione: gnocchi, purè, sott'olio (lessate), congelate (precotte)

## Consociazioni e rotazioni
- **Compagne buone**: `=this.consociazioni_buone`
- **Da evitare**: `=this.consociazioni_da_evitare`
- **Buoni predecessori**: `=this.successioni_buone`
- **Da non far seguire a**: `=this.predecessori_da_evitare`
- **Rotazione**: minimo 3-4 anni prima di rimettere solanacee; ottima dopo i legumi, che lasciano azoto

## Note clima costiero
Conviene anticipare il ciclo: messa a dimora di febbraio-marzo e raccolta primaverile-estiva prima del gran caldo, che blocca la tuberizzazione (sopra i 30 °C la pianta soffre). Possibile un secondo raccolto estivo (semina luglio-agosto) per patate novelle d'autunno, sfruttando il clima mite. L'umidità notturna marina impone vigilanza sulla peronospora. La salsedine è tollerata moderatamente: utile un frangivento se il sito è molto esposto.

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

#pianta #orticola #solanacee
