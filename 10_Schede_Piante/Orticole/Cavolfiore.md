---
tipo: scheda_pianta
categoria: orticola
nome_comune: Cavolfiore
nome_scientifico: Brassica oleracea var. botrytis
famiglia: Brassicaceae
ciclo: annuale
periodo_semina: "Giugno-Agosto (semenzaio); Agosto-Settembre (trapianto)"
periodo_raccolta: "Novembre-Marzo"
distanza_pianta_cm: 60
distanza_fila_cm: 70
profondita_semina_cm: 1
esposizione: sole pieno
ph_min: 6.5
ph_max: 7.5
fabbisogno_idrico: medio-alto
difficolta: 3
consociazioni_buone:
  - Lattuga
  - Sedano
  - Aneto
  - Aglio
consociazioni_da_evitare:
  - Altre brassicacee
  - Fragola
successioni_buone:
  - Legumi
predecessori_da_evitare:
  - Brassicacee
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Pioggia]]"
tags:
  - pianta
  - orticola
  - brassicacee
---

# 🥦 Cavolfiore

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Più esigente del cavolo classico: vuole terreno fertile, umidità costante e temperature fresche per formare il corimbo (la "testa" bianca). Varietà classiche: gigante di Napoli, primaticcio di Jesi, romanesco (verde, a torre frattale), violetto siciliano. Il romanesco e il violetto sono spesso più rustici e produttivi nel clima mite costiero.

## Semina e trapianto
- Semenzaio da fine giugno a agosto, secondo la varietà (precoce, medio, tardivo)
- Trapianto agosto-settembre, quando la piantina ha 4-5 foglie
- Distanze: 60 cm sulla fila, 70 cm tra le file
- Buca generosa con compost o letame maturo, l'apparato fogliare deve sviluppare bene prima di mettere il corimbo

## Cura
- Esposizione: sole pieno
- Irrigazione: regolare, mai stressare la pianta (un blocco di crescita = corimbo piccolo o "riccioluto")
- Pacciamatura organica
- Concimazione: macerato di ortica/consolida ogni 3 settimane
- **Imbianchimento del corimbo**: nelle varietà bianche, quando il corimbo è grande come un'arancia, ripiegare 2-3 foglie esterne sopra di esso (legare con rafia) per proteggerlo dal sole, che lo ingiallirebbe e renderebbe granuloso. Per i violetti e romaneschi non serve

## Avversità tipiche
- Stesse del cavolo: cavolaia, nottue, afidi cinerini, mosca del cavolo, ernia delle crucifere, altica
- **Carenza di boro**: cuore cavo e amaro. Si previene con compost maturo e rotazione
- **Mancata formazione del corimbo**: cause comuni stress idrico, sbalzi termici, concimazione azotata eccessiva tardiva

## Raccolta e conservazione
- Quando il corimbo è compatto e della dimensione tipica della varietà
- Se la formazione comincia a "spaccarsi" (granuli visibili), raccogliere subito altrimenti perde qualità rapidamente
- Tagliare al colletto con coltello robusto, lasciando alcune foglie attorno per proteggere
- Conservazione: 1 settimana in frigo. Trasformazione: sottaceti, gratinati, vellutate, sbianchito e congelato

## Consociazioni e rotazioni
- Come per il cavolo: ottime lattuga, sedano, aneto, aglio. Da evitare altre brassicacee e fragola
- **Rotazione**: minimo 4 anni prima di rimettere brassicacee

## Note clima costiero
Sulla costa centro-italiana la coltivazione invernale è perfetta: temperature miti che permettono la lenta formazione del corimbo senza gelate distruttive. Attenzione alle ondate di scirocco caldo in autunno, che possono mandare la pianta a seme precocemente.

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
- [[autunno]] · [[inverno]]

#pianta #orticola #brassicacee
