---
tipo: scheda_pianta
categoria: orticola
nome_comune: Finocchio
nome_scientifico: Foeniculum vulgare var. dulce
famiglia: Apiaceae
ciclo: annuale
periodo_semina: "Giugno-Agosto"
periodo_raccolta: "Ottobre-Febbraio"
distanza_pianta_cm: 25
distanza_fila_cm: 50
profondita_semina_cm: 1
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: medio
difficolta: 3
consociazioni_buone:
  - Praticamente nessuna (allelopatico)
consociazioni_da_evitare:
  - Pomodoro
  - Fagiolo
  - Cavoli
  - Aneto
  - Coriandolo
  - Quasi tutto l'orto
successioni_buone:
  - Legumi
predecessori_da_evitare:
  - Apiacee (carota, sedano, prezzemolo)
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - apiacee
---

# 🌿 Finocchio

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Pianta dal sapore anice-dolce caratteristico, coltivata per il **grumolo** (la base ingrossata, in realtà guaine fogliari sovrapposte). Varietà classiche: gigante di Napoli, romanesco, mantovano, Finocchio di Tarquinia. Da non confondere con il finocchio selvatico (Foeniculum vulgare var. azoricum o var. vulgare), che è perenne e si raccoglie per foglie e semi.

## Particolarità: allelopatia
Il finocchio rilascia nel suolo sostanze che inibiscono la germinazione e la crescita di molte altre piante. È praticamente l'unica coltura allelopatica importante dell'orto: **va isolato**, in un angolo o in una fila a sé. Anche dopo la raccolta, il terreno resta "marcato" per qualche mese.

## Semina e trapianto
- Semina diretta o in semenzaio da giugno ad agosto, in funzione della varietà
- Trapianto a 4-5 foglie vere
- Distanze: 25 cm sulla fila, 50 cm tra le file
- Terreno fertile, sciolto, ben drenato

## Cura
- Esposizione: sole pieno
- Irrigazione: regolare, mai stressare la pianta o monta a seme
- Pacciamatura organica
- **Rincalzo**: quando il grumolo comincia a ingrossare (5-6 cm), si rincalza per imbiancarlo e renderlo più tenero
- Concimazione: una ricarica di compost a metà ciclo

## Avversità tipiche
- **Nottue, afidi**: rimedi classici (macerati, sapone molle)
- **Ruggine**: macchie giallo-arancio sulle foglie. Aerare il filare, rame se necessario
- **Andata a seme prematura** (montata): se la pianta vive uno stress (caldo eccessivo, freddo, siccità improvvisa), abbandona la formazione del grumolo e fa fiori e semi. Coltivazione autunnale per la costa è la più sicura
- **Lumache** sui grumoli giovani: trappole

## Raccolta e conservazione
- Quando il grumolo è ben formato (10-15 cm di diametro), prima che si apra o monti a seme
- Tagliare al colletto, eliminare le foglie esterne più dure
- Le **foglie verdi** (barba) sono ottime per profumare brodi e insalate
- I **semi** (raccolti da piante lasciate a seme) hanno mille usi: digestivi, infusi, profumare salumi, dolci sardi
- Conservazione: 1-2 settimane in frigo. Tagliato a fette si essicca al sole per usi invernali

## Consociazioni e rotazioni
- **Praticamente da isolare**. Soffre vicino a quasi tutto e fa soffrire i vicini, in particolare pomodoro, fagiolo, cavolo, aneto, coriandolo
- **Rotazione**: come tutte le apiacee, non rimettere apiacee per 3-4 anni nella stessa parcella

## Note clima costiero
Ottima coltura autunno-invernale per costa centro-italiana. L'andata a seme estiva è il principale problema: per questo si predilige la semina di giugno-agosto. Tollera bene salsedine. Le minime sotto i 5°C possono danneggiare il grumolo: in caso di gelata annunciata, pacciamare abbondante o coprire con tessuto non tessuto.

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
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Irrigazione_a_Pioggia]]
- [[autunno]] · [[inverno]]

#pianta #orticola #apiacee
