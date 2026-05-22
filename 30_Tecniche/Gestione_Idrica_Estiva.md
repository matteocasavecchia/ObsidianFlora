---
tipo: tecnica
titolo: Gestione idrica estiva (deficit irriguo)
area: acqua
difficolta: 2
tempo_richiesto: "Pianificazione: 1 ora; gestione: continua in stagione"
stagione: estate
materiali:
  - Pacciamatura organica o telo
  - Eventuale sensore di umidità del suolo
  - Programmatore irrigazione (timer)
strumenti:
  - Vanga o sondino per controllare l'umidità in profondità
  - Pluviometro / contatore acqua (facoltativo)
tags:
  - tecnica
  - acqua
  - irrigazione
---

# 💧 Gestione idrica estiva (deficit irriguo)

> Area: `=this.area` · Difficoltà: `=this.difficolta`/5 · Tempo: `=this.tempo_richiesto`

## A cosa serve
Non è un metodo di distribuzione ma una strategia di gestione: come usare al meglio l'acqua disponibile durante l'estate, quando l'evapotraspirazione è massima e l'acqua è scarsa. Si basa su tre idee: bagnare in profondità e di rado (per spingere le radici giù), ridurre le perdite (pacciamatura, ore fresche, niente foglie bagnate) e applicare il deficit irriguo controllato, cioè dare alle piante un po' meno acqua del loro massimo teorico nelle fasi in cui tollerano lo stress, risparmiando senza penalizzare resa e qualità. Sulla costa centro-italiana, con estati lunghe e secche e acqua spesso limitata, è la differenza tra un orto che regge e uno che collassa a luglio.

## Quando farla
- Pianificazione: maggio, prima del picco di caldo
- Applicazione: giugno-settembre, il periodo di massima richiesta idrica
- Bagnatura nelle ore fresche (alba), mai a mezzogiorno
- Adeguare i turni alle ondate di calore e al vento (lo scirocco aumenta molto l'evapotraspirazione)

## Concetti chiave
- **Evapotraspirazione (ET)**: somma di evaporazione dal suolo e traspirazione delle piante. In estate sulla costa può superare 5-7 mm/giorno; è l'acqua che va reintegrata.
- **Bagnatura profonda e distanziata**: meglio molta acqua ogni 3-4 giorni che poca tutti i giorni. Le radici scendono e la pianta diventa resiliente.
- **Deficit irriguo controllato**: ridurre l'apporto del 20-40% nelle fasi tolleranti (es. dopo l'allegagione su olivo e vite, in accrescimento vegetativo non critico). Da evitare nelle fasi sensibili (fioritura, allegagione, ingrossamento frutti negli ortaggi).
- **Capacità di campo e punto di appassimento**: bagnare per riportare il suolo verso la capacità di campo, intervenire prima di arrivare allo stress visibile.

## Procedimento
1. **Stimare il fabbisogno**: per ogni coltura, partire dal `fabbisogno_idrico` indicato nelle schede pianta e dalla fase fenologica
2. **Ridurre le perdite**: pacciamare tutto il pacciamabile, irrigare all'alba, usare goccia o subirrigazione invece dell'aspersione
3. **Stabilire i turni**: turni profondi e radi; verificare scavando a 15-20 cm se il suolo è ancora umido prima di ribagnare
4. **Applicare il deficit dove possibile**: nelle fasi tolleranti ridurre volume o allungare il turno, osservando le piante
5. **Monitorare**: controllare umidità del suolo (a mano o con sensore) e segni di stress (foglie afflosciate nelle ore calde che si riprendono la sera = normale; afflosciamento mattutino = stress vero)
6. **Adeguarsi al meteo**: aumentare in ondata di calore/scirocco, sospendere dopo pioggia significativa

## Accorgimenti per il clima costiero
Il vento marino e lo scirocco alzano molto l'evapotraspirazione: nelle giornate ventose il fabbisogno può raddoppiare. La pacciamatura e i frangivento riducono entrambi le perdite. Attenzione all'acqua di pozzo costiero: se diventa salmastra in estate (la falda si abbassa e risale il cuneo salino), sospenderne l'uso, perché il sale si concentra nel suolo proprio quando si bagna meno e non si dilava. Su suoli sabbioni costieri la riserva idrica è bassa: turni un po' più frequenti ma sempre con pacciamatura.

## Errori comuni
- Bagnature brevi e quotidiane: radici superficiali, piante che soffrono alla prima ondata di calore
- Irrigare a mezzogiorno o di sera: evaporazione massima al mattino, malattie fungine alla sera
- Niente pacciamatura: gran parte dell'acqua evapora prima di essere usata
- Deficit irriguo nelle fasi sbagliate (fioritura, ingrossamento frutti): cascola, frutti piccoli, marciume apicale
- Ignorare il meteo: stessi turni in settimana fresca e in ondata di calore

## Piante / situazioni in cui si applica
- Tutte le orticole estive nei mesi di picco
- Frutteto e oliveto (deficit dopo allegagione)
- Vite (il deficit moderato migliora la concentrazione)
- Aromatiche mediterranee (tollerano bene la riduzione)
- Da abbinare sempre a [[Pacciamatura]] e a un metodo efficiente come [[Irrigazione_a_Goccia]] o [[Subirrigazione]]

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
- [[Gestione_Salsedine_Vento]]
- [[Raccolta_Acqua_Piovana]]

#tecnica #acqua #irrigazione
