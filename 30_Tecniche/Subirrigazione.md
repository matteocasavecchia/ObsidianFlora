---
tipo: tecnica
titolo: Subirrigazione (manichetta interrata)
area: acqua
difficolta: 3
tempo_richiesto: "Installazione: 1 giornata; manutenzione: 1-2 ore/stagione"
stagione: primavera-estate
materiali:
  - Ali gocciolanti interrate antirisucchio (autocompensanti)
  - Tubo principale PE 16-20 mm
  - Filtro a Y a maglia fine
  - Riduttore di pressione
  - Valvola antisifone / antirisucchio
  - Programmatore irrigazione (timer)
  - Eventuale linea di flussaggio a fine ciclo
strumenti:
  - Vanga o motozappa per interrare le linee
  - Punzonatrice e forbici per tubi
tags:
  - tecnica
  - acqua
  - irrigazione
---

# 💧 Subirrigazione (manichetta interrata)

> Area: `=this.area` · Difficoltà: `=this.difficolta`/5 · Tempo: `=this.tempo_richiesto`

## A cosa serve
Portare l'acqua direttamente alle radici tramite ali gocciolanti interrate a 10-20 cm di profondità. È l'evoluzione della goccia: la superficie resta asciutta, l'evaporazione è quasi nulla e l'efficienza idrica è la più alta di tutti i metodi (85-95%). Ideale per filari stabili, frutteto e colture pluriennali, dove l'impianto resta in posto per anni. Riduce anche la crescita delle erbe spontanee in superficie (il secco superficiale non le favorisce) e azzera il rischio di bagnare le foglie.

## Quando farla
- Installazione: a inizio impianto del filare/frutteto, o in primavera prima delle colture
- Funzionamento: aprile-ottobre; cicli più lunghi e distanziati rispetto alla goccia in superficie
- Manutenzione: flussaggio delle linee a inizio e fine stagione, pulizia filtro, controllo della valvola antirisucchio
- Le linee restano interrate tutto l'anno (svuotare in zone soggette a gelo intenso)

## Materiali e strumenti
- **Ali gocciolanti interrate antirisucchio**: gocciolatori con membrana che impedisce al terreno di risucchiare dentro l'ugello quando si chiude l'acqua; autocompensanti per portata costante
- **Filtro a Y a maglia fine**: ancora più importante che in superficie, perché un'ala interrata intasata è difficile da ispezionare
- **Valvola antisifone/antirisucchio** sulla linea: evita l'aspirazione di terra e radici a fine ciclo
- **Riduttore di pressione** e **programmatore**
- **Linea di flussaggio** a fine fila: terminale apribile per spurgare sedimenti

## Procedimento
1. **Disegno**: definire i filari fissi; la subirrigazione conviene dove l'impianto resta per anni
2. **Scavo**: aprire solchi a 10-20 cm di profondità (più profondi per alberi, più superficiali per ortaggi a radice corta)
3. **Posa ali interrate**: stendere le ali antirisucchio nei solchi, collegarle alla principale con valvola antisifone
4. **Test prima di interrare**: aprire l'acqua e verificare che tutti i gocciolatori funzionino, poi richiudere il solco
5. **Programmazione**: cicli più lunghi (l'acqua deve risalire per capillarità verso la superficie e diffondersi); verificare scavando dove arriva il bulbo umido
6. **Flussaggio**: a inizio e fine stagione aprire i terminali e far scorrere acqua per pulire le linee dai sedimenti

## Accorgimenti per il clima costiero
L'acqua calcarea è ancora più insidiosa qui: i depositi si formano dentro ali non ispezionabili. Usare solo ali antirisucchio di qualità, filtro a maglia fine e flussaggi regolari. Vantaggio sulla costa: superficie asciutta significa meno evaporazione sotto sole e vento, e radici spinte in profondità, più resistenti alla siccità e alla salsedine superficiale. Non usare acqua salmastra: il sale si accumula in profondità intorno alle radici senza dilavarsi.

## Errori comuni
- Ali non antirisucchio: il terreno entra nei gocciolatori e li ottura definitivamente
- Niente valvola antisifone: aspirazione di terra a ogni chiusura
- Profondità sbagliata: troppo profonde per ortaggi a radici corte (l'acqua non risale), troppo superficiali per alberi
- Mancato flussaggio stagionale: accumulo di sedimenti e calcare
- Cicli troppo brevi: il bulbo umido non raggiunge la superficie né le radici fini

## Piante / situazioni in cui si applica
- Frutteto e agrumeto adulto (impianto stabile)
- Vite e filari permanenti
- Aiuole perenni di aromatiche
- Orticole a filare fisso su bancali rialzati
- Sconsigliata dove si lavora spesso il terreno in profondità (rischio di tagliare le ali)

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
- [[Irrigazione_a_Goccia]]
- [[Pacciamatura]]

#tecnica #acqua #irrigazione
