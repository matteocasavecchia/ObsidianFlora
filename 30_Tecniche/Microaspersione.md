---
tipo: tecnica
titolo: Microaspersione e nebulizzazione
area: acqua
difficolta: 2
tempo_richiesto: "Installazione: mezza giornata; manutenzione: 1 ora/mese"
stagione: primavera-estate
materiali:
  - Tubo principale PE 16-20 mm
  - Microirrigatori a spillo (statici o rotanti, 20-120 L/h)
  - Nebulizzatori/foggers per serra e semenzaio
  - Microtubi 4-6 mm e raccordi rapidi
  - Filtro a Y (a maglia fine)
  - Riduttore di pressione
  - Programmatore irrigazione (timer)
strumenti:
  - Punzonatrice per spillare i microtubi
  - Forbici per tubi
tags:
  - tecnica
  - acqua
  - irrigazione
---

# 💧 Microaspersione e nebulizzazione

> Area: `=this.area` · Difficoltà: `=this.difficolta`/5 · Tempo: `=this.tempo_richiesto`

## A cosa serve
Distribuire l'acqua con piccoli spruzzatori a bassa portata che bagnano un cerchio di terreno di raggio limitato (da pochi decimetri a 2-3 metri). Sta a metà tra goccia e aspersione: copre una superficie più ampia del singolo gocciolatore, ma con consumi e pressioni contenuti. È la scelta tipica sotto la chioma degli alberi, in serra, nei semenzai e per le aiuole di aromatiche, dove serve umidità diffusa ma non un getto potente. La nebulizzazione (foggers) crea micro-gocce per alzare l'umidità dell'aria in serra e su talee.

## Quando farla
- Installazione: primavera, prima del caldo
- Funzionamento: ore fresche del mattino; in serra anche brevi cicli diurni per la nebulizzazione
- Nebulizzazione su talee/semenzai: cicli brevi e frequenti per mantenere umido l'apparato fogliare
- Manutenzione: pulizia mensile di filtro e ugelli (la maglia fine si intasa facilmente)

## Materiali e strumenti
- **Tubo principale** PE 16-20 mm
- **Microirrigatori a spillo**: statici (cerchio fisso) o rotanti (raggio maggiore), portata 20-120 L/h secondo modello; si infilano su microtubo e picchetto
- **Nebulizzatori / foggers**: ugelli a micro-goccia per serra, richiedono buona pressione e acqua molto pulita
- **Filtro a Y a maglia fine**: indispensabile, gli ugelli microscopici si intasano subito
- **Riduttore di pressione** e **programmatore**
- **Microtubi 4-6 mm** e raccordi rapidi per le derivazioni

## Procedimento
1. **Disegno**: posizionare un microirrigatore per ogni pianta/area, calcolando il raggio bagnato e la sovrapposizione
2. **Linea principale**: rubinetto > filtro maglia fine > riduttore pressione > programmatore > tubo PE
3. **Derivazioni**: spillare il tubo con la punzonatrice, inserire microtubo + raccordo + microirrigatore su picchetto, all'altezza voluta
4. **Sotto chioma**: posizionare lo spruzzatore in modo che il getto non colpisca il tronco e copra l'area delle radici
5. **Programmazione**: cicli al mattino per l'irrigazione; cicli brevi e ripetuti per la nebulizzazione su talee
6. **Test**: verificare che ogni ugello apra correttamente e che nessuno sia intasato

## Accorgimenti per il clima costiero
Gli ugelli a micro-portata sono i primi a intasarsi con acqua calcarea: filtro a maglia fine e pulizia frequente sono d'obbligo. Il vento marino disperde la micro-goccia ancora più dell'aspersione classica: usare la microaspersione in posizioni riparate (sotto chioma, serra, dietro frangivento) e nelle ore di calma. Non usare acqua salmastra. La nebulizzazione in serra costiera aiuta nelle giornate di scirocco caldo e secco.

## Errori comuni
- Filtro assente o a maglia larga: ugelli intasati in pochi giorni
- Microaspersione in pieno vento: acqua dispersa, copertura irregolare
- Getto che bagna il tronco degli alberi: favorisce marciumi del colletto
- Nebulizzazione con acqua dura: depositi di calcare sulle foglie e ugelli ostruiti
- Cicli troppo lunghi: ristagno superficiale invece di bagnatura uniforme

## Piante / situazioni in cui si applica
- Sotto chioma di alberi da frutto e agrumi
- Semenzai e propagazione per talea (nebulizzazione)
- Serra e tunnel (umidità e irrigazione)
- Aiuole di aromatiche perenni e fioriture
- Ortaggi a foglia in posizione riparata

### Schede pianta collegate
```dataview
LIST
FROM "agricoltura/10_Schede_Piante"
WHERE contains(tecniche_irrigazione, this.file.link)
SORT file.name ASC
```

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
- [[Irrigazione_a_Pioggia]]
- [[Irrigazione_a_Goccia]]
- [[Semenzaio_Moltiplicazione]]

#tecnica #acqua #irrigazione
