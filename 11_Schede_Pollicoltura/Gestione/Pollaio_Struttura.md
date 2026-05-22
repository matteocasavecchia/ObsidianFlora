---
tipo: gestione_pollaio
titolo: Pollaio Struttura
area: struttura
difficolta: 3
frequenza: una tantum (progettazione) + manutenzione stagionale
stagione: costruzione in primavera/estate
materiali: legno trattato, rete elettrosaldata zincata maglia fine, lamiera/tegole, paglia o trucioli
strumenti: avvitatore, sega, pinze, vanga (per interrare la rete)
tags:
  - pollicoltura
  - gestione
---

# 🛠️ Pollaio Struttura

> Area: struttura · Difficoltà: 3/5 · Frequenza: una tantum + manutenzione

## A cosa serve
Un pollaio ben progettato è la base del benessere e della produzione. Deve garantire riparo dalle intemperie, sicurezza dai predatori, ventilazione senza correnti d'aria, spazio sufficiente e nidi tranquilli per la deposizione. Partendo da zero, è la prima cosa da definire bene: correggerla dopo è scomodo.

## Quando farlo
- Stagione / periodo: costruzione meglio in primavera/estate, così è pronto e asciutto prima dei freddi.
- Frequenza: progettazione una tantum; manutenzione e controlli a ogni cambio di stagione.

## Dimensionamento (pollaio familiare)
- Ricovero notturno (chiuso): circa 3-4 galline per m². Per 4-6 ovaiole bastano 1,5-2 m² coperti.
- Recinto/parchetto esterno: minimo 1-2 m² per capo, ma più spazio è sempre meglio (10 m²/capo è l'ideale per il razzolamento). Lo spazio abbondante riduce stress, cannibalismo e parassiti.
- Posatoi: 15-20 cm di trespolo per gallina, sezione arrotondata (~4-5 cm), posti più in alto dei nidi così le galline non dormono nei nidi.
- Nidi: 1 ogni 3-4 galline, circa 30x30x30 cm, in penombra, raccolti e tranquilli, con lettiera morbida (paglia/trucioli).

## Materiali e strumenti
- Materiali: legno (meglio trattato o verniciato con prodotti atossici), rete elettrosaldata zincata a maglia fine, copertura impermeabile (lamiera coibentata o tegole), lettiera (paglia, trucioli di legno non trattato, canapa).
- Strumenti: avvitatore, sega, pinze per rete, vanga per interrare la recinzione.

## Procedimento
1. Scegli la posizione: terreno ben drenato, non in conca dove ristagna l'acqua, con zone d'ombra naturale per l'estate.
2. Orienta l'apertura principale a sud/sud-est per il sole del mattino, proteggendo il lato esposto ai venti dominanti.
3. Costruisci il ricovero rialzato da terra (evita umidità e roditori) con posatoi e nidi all'interno.
4. Recinta il parchetto con rete a maglia fine, interrata 30-50 cm o ripiegata a L verso l'esterno contro gli animali che scavano.
5. Predisponi la ventilazione alta (sopra la testa delle galline appollaiate) e una pop-hole (sportello) richiudibile.
6. Stendi la lettiera e sistema mangiatoia e abbeveratoio sollevati da terra.

## Accorgimenti per il clima costiero
Il caldo-umido estivo della costa è più pericoloso del freddo: prevedi ombra abbondante, ottima ventilazione e acqua sempre fresca. La salsedine e il vento marino (maestrale, libeccio) corrodono e raffreddano: usa ferramenta zincata, proteggi il lato sopravento e cura il drenaggio della lettiera, perché l'umidità favorisce parassiti e ammoniaca.

## Errori comuni
- Ventilazione insufficiente o, all'opposto, correnti d'aria dirette sui posatoi.
- Nidi troppo bassi o troppo illuminati: le galline ci dormono e li sporcano, oppure non li usano.
- Rete a maglia larga: non ferma faine e donnole (vedi [[Predatori_Sicurezza]]).
- Pollaio sottodimensionato: porta a stress, picaggio e calo deposizione.

## Segnali da tenere d'occhio
Lettiera che si impasta o puzza di ammoniaca (ventilazione/umidità da correggere), galline che dormono nei nidi (posatoi da rialzare), condensa sulle pareti al mattino (manca ricambio d'aria).

## Diario di campo collegato
```dataview
TABLE file.name AS "Nota", meteo AS "Meteo"
FROM "agricoltura/40_Diario"
WHERE contains(file.outlinks, this.file.link)
SORT file.name DESC
LIMIT 10
```

## Riferimenti
- [[_MOC_Pollicoltura]]
- [[Predatori_Sicurezza]]
- [[Salute_Profilassi]]

#pollicoltura #gestione
