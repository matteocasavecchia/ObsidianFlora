---
tipo: tecnica
titolo: Raccolta acqua piovana (cisterne e serbatoi)
area: acqua
difficolta: 2
tempo_richiesto: "Installazione: 1-2 giornate; manutenzione: 2 ore/anno"
stagione: autunno-inverno (raccolta), estate (uso)
materiali:
  - Cisterna o serbatoio (fuori terra o interrato)
  - Grondaie e pluviali di raccolta
  - Filtro foglie / cestello a monte
  - Deviatore di prima pioggia (first flush)
  - Troppopieno con scarico controllato
  - Rubinetto e raccordo per pompa o caduta a gravità
strumenti:
  - Attrezzi per collegare grondaie e tubazioni
  - Eventuale pompa (se manca dislivello)
tags:
  - tecnica
  - acqua
  - irrigazione
---

# 💧 Raccolta acqua piovana (cisterne e serbatoi)

> Area: `=this.area` · Difficoltà: `=this.difficolta`/5 · Tempo: `=this.tempo_richiesto`

## A cosa serve
Raccogliere e immagazzinare l'acqua piovana dai tetti per usarla in irrigazione durante la stagione secca. È acqua dolce, priva di calcare e di sale, ideale per la goccia (non intasa i gocciolatori) e gradita dalle piante. Sulla costa centro-italiana, dove le piogge sono concentrate in autunno-inverno e l'acqua di pozzo può essere calcarea o salmastra, una cisterna trasforma la pioggia altrimenti persa in riserva per l'estate, riducendo bolletta e dipendenza dall'acquedotto.

## Quando farla
- Installazione: meglio in autunno, in vista delle piogge stagionali
- Raccolta: a ogni pioggia, soprattutto autunno-inverno-primavera
- Uso: estate, quando la riserva alimenta l'irrigazione
- Manutenzione: pulizia filtri e grondaie a inizio autunno, svuotamento/ispezione cisterna una volta l'anno

## Dimensionamento
La regola pratica: per ogni millimetro di pioggia e ogni metro quadrato di tetto si raccoglie circa 1 litro (meno le perdite, circa 0,8 L reali). Esempio: un tetto di 80 m² con un acquazzone da 20 mm raccoglie circa 80 × 20 × 0,8 ≈ 1.280 litri. Per dimensionare la cisterna, stimare la pioggia stagionale recuperabile e il fabbisogno estivo dell'orto; spesso 1.000-5.000 litri coprono un orto familiare come riserva di soccorso.

## Materiali e strumenti
- **Cisterna/serbatoio**: fuori terra (economico, ispezionabile, ma teme gelo e alghe se trasparente) o interrato (acqua fresca e al buio, costo maggiore)
- **Grondaie e pluviali** che convoglino l'acqua del tetto alla cisterna
- **Filtro foglie / cestello** a monte, per trattenere detriti
- **Deviatore di prima pioggia (first flush)**: scarta i primi litri che dilavano polveri e sporco dal tetto, migliorando la qualità
- **Troppopieno**: scarico controllato verso un punto sicuro (o verso uno [[Swale_Canali_Infiltrazione]]) quando la cisterna è piena
- **Uscita**: rubinetto a gravità se la cisterna è rialzata, altrimenti una pompa per mandare l'acqua all'impianto

## Procedimento
1. **Scegliere il punto di raccolta**: il tetto con più superficie e grondaie già esistenti
2. **Posizionare la cisterna**: vicino al pluviale, possibilmente rialzata per sfruttare la caduta a gravità verso l'orto
3. **Collegare grondaia, filtro e deviatore di prima pioggia** all'ingresso della cisterna
4. **Predisporre il troppopieno**: tubo di sfioro che scarica l'eccesso senza allagare, idealmente verso un'aiuola o uno swale
5. **Uscita verso l'impianto**: rubinetto + raccordo per goccia a gravità, oppure pompa se manca dislivello
6. **Coprire la cisterna**: chiusa e al buio per evitare alghe e zanzare
7. **Collaudo**: alla prima pioggia verificare riempimento, tenuta e funzionamento del troppopieno

## Accorgimenti per il clima costiero
L'acqua piovana è il miglior alleato contro i due problemi idrici della costa: niente calcare (gocciolatori puliti più a lungo) e niente sale (a differenza dei pozzi con intrusione salina). Le piogge mediterranee sono concentrate e intense: servono grondaie ben dimensionate e un troppopieno generoso, perché in un singolo temporale autunnale la cisterna si riempie in fretta. Combinare la cisterna con uno swale per il troppopieno fa sì che anche l'acqua eccedente resti nel terreno invece di andare persa. In zona ventosa, fissare bene serbatoi fuori terra leggeri quando sono vuoti.

## Errori comuni
- Nessun filtro né deviatore di prima pioggia: acqua sporca, sedimenti che intasano la goccia
- Cisterna aperta o trasparente: proliferazione di alghe e zanzare
- Troppopieno assente o sottodimensionato: allagamenti durante i temporali
- Cisterna troppo piccola rispetto al tetto: gran parte della pioggia va persa al troppopieno
- Posizione senza dislivello e senza pompa: acqua immagazzinata ma difficile da usare
- Usare l'acqua piovana per uso potabile senza adeguati trattamenti: qui è destinata solo all'irrigazione

## Piante / situazioni in cui si applica
- Alimentazione di impianti a [[Irrigazione_a_Goccia]] e [[Subirrigazione]] (acqua dolce, non intasa)
- Riempimento di conche per [[Irrigazione_a_Conca_e_Solco]]
- Riserva di soccorso per l'orto in piena estate
- Agrumi e piante in vaso, sensibili al calcare dell'acqua di rete
- Da abbinare a [[Swale_Canali_Infiltrazione]] per gestire il troppopieno

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
- [[Swale_Canali_Infiltrazione]]
- [[Gestione_Idrica_Estiva]]

#tecnica #acqua #irrigazione
