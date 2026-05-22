---
tipo: tecnica
titolo: Irrigazione a goccia
area: acqua
difficolta: 2
tempo_richiesto: "Installazione: mezza giornata; manutenzione: 1 ora/mese"
stagione: primavera-estate
materiali:
  - Tubo principale 16-20 mm
  - Ali gocciolanti autocompensanti (0.5-2 L/h, passo 30 cm)
  - Raccordi a T, gomiti, riduttori
  - Filtro a Y
  - Riduttore di pressione (1-1.5 bar)
  - Programmatore irrigazione (timer)
strumenti:
  - Forbici per tubi
  - Punzonatrice (per spillare microtubi)
tags:
  - tecnica
  - acqua
  - irrigazione
---

# 💧 Irrigazione a goccia

> Area: `=this.area` · Difficoltà: `=this.difficolta`/5 · Tempo: `=this.tempo_richiesto`

## A cosa serve
Distribuire piccole quantità d'acqua al piede della pianta, lentamente e localizzata. Vantaggi rispetto all'irrigazione tradizionale (a pioggia, a scorrimento, manuale): risparmio idrico del 30-60% (acqua arriva solo dove serve, no evaporazione su foglie), foglie asciutte (riduzione drastica di peronospora, oidio e altre crittogame), pacciamatura compatibile, automatizzabile con timer, controllo preciso del fabbisogno per coltura. Sulla costa mediterranea, con estati lunghe e secche, l'irrigazione a goccia è praticamente lo standard del biologico moderno.

## Quando farla
- Installazione: primavera (marzo-aprile) prima del caldo
- Funzionamento: aprile-ottobre nelle estati centro-italiane
- Manutenzione: pulizia filtro mensile, controllo gocciolatori intasati a inizio stagione
- Smontaggio (facoltativo): in inverno conviene smontare e svuotare per evitare gelate (ali a perdere durano 3-5 stagioni, le buone 8-10)

## Materiali e strumenti
- **Tubo principale** PE 16 mm (orto familiare) o 20 mm (impianti più grandi). Lunghezza secondo orto
- **Ali gocciolanti** autocompensanti (mantengono portata costante anche su dislivelli): passo 20 cm (foglie/ortaggi fitti), 30 cm (standard), 50 cm (alberi sparsi). Portata: 0.5 L/h (terreni argillosi), 1 L/h (medi), 2 L/h (sabbiosi)
- **Filtro a Y**: indispensabile, evita intasamento gocciolatori. Pulizia mensile
- **Riduttore di pressione**: se acquedotto sopra 1.5 bar (frequente)
- **Programmatore**: a 1 o più zone, a batteria o elettrico
- **Raccordi**: T, gomiti, terminali per chiudere fine linea, raccordi rapidi

## Procedimento
1. **Disegno**: tracciare la mappa dell'orto, posizionare il punto acqua, decidere il tracciato delle ali
2. **Linea principale**: collegare al rubinetto > filtro > riduttore pressione > programmatore > tubo PE 16-20 mm
3. **Ali gocciolanti**: derivare dalle principali con raccordi a T. Una ala per fila di piante. Su alberi da frutto: anello attorno alla pianta o doppio gocciolatore a 30-40 cm dal tronco
4. **Pacchetto fine linea**: chiusura terminale, importante per non perdere acqua
5. **Programmazione**: 2 cicli al giorno (mattina presto e sera) durante luglio-agosto. Durata 30-60 min per ciclo secondo coltura e suolo
6. **Test**: aprire l'acqua, controllare che tutti i gocciolatori funzionino, verificare assenza di perdite
7. **Pacciamatura sopra**: aumenta efficienza del 30-50% trattenendo l'umidità

## Accorgimenti per il clima costiero
Acqua di pozzo costiero può essere ricca di calcare (calcio carbonato) che intasa i gocciolatori: filtri di buona qualità e ali autopulenti. In zone con acqua salmastra (pozzi vicini al mare con intrusione salina): evitare di usarla, le piante deperiscono. Vento marino: ali gocciolanti coperte da pacciamatura non volano. Estate centro-italiana: bagnatura profonda e meno frequente (es. 60 min ogni 2-3 giorni) è meglio di bagnature corte e quotidiane (radici imparano ad andare in profondità, pianta più resiliente).

## Errori comuni
- Niente filtro: gocciolatori si intasano in poche settimane
- Bagnature troppo brevi e quotidiane: radici superficiali, pianta fragile
- Gocciolatori troppo distanti tra loro: zone secche tra piante
- Niente pacciamatura sopra: spreco di acqua per evaporazione
- Pressione troppo alta: ali esplodono o si staccano dai raccordi
- Dimenticare la manutenzione di inizio stagione: gocciolatori incrostati, rese ridotte

## Piante / situazioni in cui si applica
- Tutte le orticole estive (pomodoro, melanzana, peperone, cucurbitacee, fagiolini, ecc.)
- Alberi da frutto giovani (primi 3-4 anni essenziale)
- Agrumi (anche in vaso)
- Vite da tavola
- Aiuole di aromatiche perenni
- Semenzai (con micro-asperisori a bassissima portata)

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
- [[_MOC_Tecniche]]
- [[Pacciamatura]]
- [[Gestione_Salsedine_Vento]]

#tecnica #acqua #irrigazione
