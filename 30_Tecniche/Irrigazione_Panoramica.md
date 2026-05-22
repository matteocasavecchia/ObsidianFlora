---
tipo: tecnica
titolo: Irrigazione - panoramica e confronto metodi
area: acqua
difficolta: 1
tempo_richiesto: "Lettura e scelta del metodo: 20 minuti"
stagione: tutto l'anno (pianificazione), primavera-estate (uso)
materiali: []
strumenti: []
tags:
  - tecnica
  - acqua
  - irrigazione
  - moc
---

# 💧 Irrigazione - panoramica e confronto metodi

> Area: `=this.area` · Difficoltà: `=this.difficolta`/5 · Nota hub

## A cosa serve
Questa è la nota di riferimento per orientarsi tra i metodi di irrigazione. Non descrive una singola tecnica ma confronta le opzioni e rimanda alle schede dedicate. Sulla costa centro-italiana, con estati lunghe e secche, vento marino e acqua spesso calcarea o salmastra, la scelta del metodo incide molto su consumo idrico, salute delle piante e tempo di gestione.

## Confronto rapido dei metodi

| Metodo | Efficienza idrica | Foglie bagnate | Automatizzabile | Costo impianto | Adatto a |
|---|---|---|---|---|---|
| [[Irrigazione_a_Goccia]] | Molto alta (70-90%) | No | Sì | Medio | Orticole estive, alberi giovani, agrumi, vite |
| [[Subirrigazione]] | Massima (85-95%) | No | Sì | Medio-alto | Filari stabili, frutteto, colture pluriennali |
| [[Microaspersione]] | Media (60-75%) | Sì (parziale) | Sì | Medio | Sotto chioma alberi, semenzai, serra, aromatiche |
| [[Irrigazione_a_Pioggia]] | Media (60-75%) | Sì | Sì | Medio | Prati, semine fitte, cereali, attecchimento |
| [[Irrigazione_a_Conca_e_Solco]] | Bassa-media (40-60%) | No | No | Basso | Alberi isolati, orto tradizionale, zero corrente |
| [[Swale_Canali_Infiltrazione]] | Indiretta (raccolta) | No | No (passivo) | Basso-medio | Frutteto, siepi, recupero acqua piovana, terreni in pendenza |

L'efficienza idrica indica quanta dell'acqua erogata arriva realmente alle radici (il resto si perde per evaporazione, vento, percolazione o ruscellamento).

## Come scegliere
- **Orto familiare estivo**: goccia come standard, eventualmente subirrigazione su filari fissi.
- **Frutteto e agrumeto**: goccia ad anello o subirrigazione; conca per alberi isolati senza impianto.
- **Semenzai e talee**: microaspersione o aspersione a bassa portata (servono foglie e superficie umide).
- **Prato, tappeto erboso, semine fitte**: aspersione a pioggia.
- **Pendenza, recupero pioggia, riduzione siccità strutturale**: swale, da abbinare a goccia o conca.
- **Senza corrente né pressione**: conca, solco, swale; goccia a caduta da serbatoio rialzato.

## Accorgimenti per il clima costiero
Acqua calcarea (pozzi costieri) intasa gocciolatori e ugelli: filtri e manutenzione contano più del metodo. Acqua salmastra da intrusione salina: da evitare per goccia e aspersione sulle foglie, dannosa. Vento marino: l'aspersione perde molta acqua per deriva, meglio goccia/subirrigazione nelle ore senza vento. In generale, bagnare meno spesso ma in profondità rende le radici più resilienti alla siccità estiva.

## Schede collegate

Metodi di distribuzione:
- [[Irrigazione_a_Goccia]]
- [[Subirrigazione]]
- [[Microaspersione]]
- [[Irrigazione_a_Pioggia]]
- [[Irrigazione_a_Conca_e_Solco]]
- [[Swale_Canali_Infiltrazione]]

Gestione e approvvigionamento:
- [[Gestione_Idrica_Estiva]] (deficit irriguo, turni, riduzione perdite)
- [[Raccolta_Acqua_Piovana]] (cisterne e serbatoi)

## Tutte le tecniche idriche del vault
```dataview
TABLE area AS "Area", difficolta AS "Difficoltà", stagione AS "Stagione"
FROM "agricoltura/30_Tecniche"
WHERE tipo = "tecnica" AND area = "acqua"
SORT difficolta ASC, file.name ASC
```

## Riferimenti
- [[_MOC_Tecniche]]
- [[Pacciamatura]]
- [[Gestione_Salsedine_Vento]]

#tecnica #acqua #irrigazione
