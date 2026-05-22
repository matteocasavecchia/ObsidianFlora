---
tipo: tecnica
titolo: Irrigazione a pioggia (aspersione)
area: acqua
difficolta: 2
tempo_richiesto: "Installazione: mezza giornata; manutenzione: 1 ora/stagione"
stagione: primavera-estate
materiali:
  - Tubo principale PE 20-25 mm
  - Irrigatori statici o dinamici (a turbina/oscillanti)
  - Microirrigatori a getto per semenzai
  - Raccordi, gomiti, terminali
  - Filtro a Y
  - Riduttore di pressione
  - Programmatore irrigazione (timer)
strumenti:
  - Forbici per tubi
  - Chiave per raccordi
tags:
  - tecnica
  - acqua
  - irrigazione
---

# 💧 Irrigazione a pioggia (aspersione)

> Area: `=this.area` · Difficoltà: `=this.difficolta`/5 · Tempo: `=this.tempo_richiesto`

## A cosa serve
Distribuire l'acqua simulando la pioggia, tramite irrigatori che la spruzzano in aria sopra le colture. È il metodo più semplice per coprire superfici ampie e uniformi (prati, semine fitte, cereali, ortaggi a foglia) e per accompagnare attecchimento e germinazione, quando serve bagnare tutta la superficie del terreno e non solo il piede della pianta. Bagna però le foglie, quindi è meno indicato per colture sensibili alle crittogame.

## Quando farla
- Installazione: primavera, prima del caldo
- Funzionamento: nelle ore fresche, presto al mattino (riduce evaporazione e lascia asciugare le foglie in giornata)
- Mai nelle ore calde e ventose: gran parte dell'acqua evapora o viene portata via dal vento (deriva)
- Manutenzione: pulizia ugelli e filtro a inizio stagione, controllo getto a stagione avviata

## Materiali e strumenti
- **Tubo principale** PE 20-25 mm: l'aspersione richiede portata e pressione maggiori della goccia
- **Irrigatori**: statici a ventaglio (piccole aiuole), dinamici a turbina o oscillanti (superfici ampie), microirrigatori a getto basso (semenzai e talee)
- **Filtro a Y** e **riduttore di pressione**: utili come per la goccia, ma l'aspersione tollera acque un po' meno filtrate
- **Programmatore**: consigliato per rispettare le ore fresche del mattino
- **Raccordi e terminali** per chiudere le linee

## Procedimento
1. **Disegno**: misurare la superficie e il raggio di gittata degli irrigatori, prevedere sovrapposizione dei getti (testa-piede) per evitare zone secche
2. **Linea principale**: rubinetto > filtro > riduttore pressione > programmatore > tubo PE 20-25 mm
3. **Posizionamento irrigatori**: distanza tra irrigatori pari a circa il raggio di gittata, così i coni d'acqua si sovrappongono
4. **Test pressione**: verificare che l'ultimo irrigatore della linea giri/spruzzi correttamente; se cala, accorciare la linea o aumentare il diametro
5. **Programmazione**: cicli al mattino presto, durata regolata in base a quanto bagna il terreno in profondità (controllare scavando)
6. **Verifica uniformità**: appoggiare alcuni barattoli vuoti sull'area e misurare quanta acqua raccolgono dopo un ciclo: differenze marcate indicano cattiva sovrapposizione

## Accorgimenti per il clima costiero
Il vento marino è il principale nemico dell'aspersione: sposta i getti e crea zone bagnate e zone secche, oltre a far evaporare molta acqua. Irrigare nelle ore di calma (alba) e, in zone molto ventose, valutare microaspersione bassa o passare a goccia. Con acqua calcarea gli ugelli si incrostano: smontarli e pulirli in aceto a inizio stagione. Non usare acqua salmastra in aspersione: il sale depositato sulle foglie le brucia.

## Errori comuni
- Irrigare nelle ore calde o ventose: forte evaporazione e deriva, spreco fino al 40-50%
- Irrigatori troppo distanti: zone secche tra un getto e l'altro
- Bagnare le foglie di colture sensibili (pomodoro, vite, cucurbitacee) di sera: favorisce peronospora e oidio
- Pressione insufficiente: l'ultimo irrigatore non gira e bagna male
- Nessun controllo di uniformità: si crede di bagnare tutto e invece restano aree asciutte

## Piante / situazioni in cui si applica
- Prati e tappeti erbosi
- Semine fitte e germinazione (ortaggi a foglia, carota, ravanello, rucola)
- Semenzai e talee (con microirrigatori a bassa portata)
- Cereali e colture da rinverdimento
- Sconsigliata su colture sensibili alle crittogame e in zone molto ventose

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
- [[Microaspersione]]
- [[Gestione_Salsedine_Vento]]

#tecnica #acqua #irrigazione
