---
tipo: gestione_pollaio
titolo: Salute Profilassi
area: salute
difficolta: 3
frequenza: controlli settimanali + interventi stagionali
stagione: tutto l'anno (parassiti in aumento col caldo-umido)
materiali: sabbia e cenere per bagni, terra di diatomee, prodotti antiparassitari, disinfettante
strumenti: guanti, spruzzatore, contenitore per bagno di sabbia
tags:
  - pollicoltura
  - gestione
---

# 🛠️ Salute Profilassi

> Area: salute · Difficoltà: 3/5 · Frequenza: controlli settimanali

## A cosa serve
La prevenzione è molto più efficace della cura. Igiene, controllo dei parassiti, quarantena dei nuovi arrivi e osservazione quotidiana mantengono il gruppo sano e produttivo. Per un pollaio familiare, poche pratiche regolari evitano la gran parte dei problemi.

## Quando farlo
- Stagione / periodo: tutto l'anno; i parassiti esterni esplodono con il caldo-umido, quindi attenzione extra in estate.
- Frequenza: osservazione quotidiana, controllo parassiti settimanale, pulizie e profilassi stagionali.

## Materiali e strumenti
- Materiali: sabbia + cenere di legna per i bagni, terra di diatomee, antiparassitari specifici per avicoli, disinfettante per il vuoto sanitario.
- Strumenti: guanti, spruzzatore, area dedicata al bagno di sabbia.

## Buone pratiche di prevenzione
1. Quarantena: tieni i nuovi arrivi separati 2-4 settimane prima di unirli al gruppo.
2. Igiene: pulizia regolare di lettiera, posatoi e nidi; periodico vuoto sanitario con disinfezione.
3. Bagno di sabbia e cenere: indispensabile, le galline lo usano per liberarsi dai parassiti esterni.
4. Osservazione quotidiana: cresta rossa e turgida, occhio vivo, piumaggio in ordine, appetito e feci normali sono segni di buona salute.

## Parassiti esterni
- Acari rossi (Dermanyssus gallinae): si nascondono nelle fessure di posatoi e pareti e attaccano di notte. Controlla i posatoi al buio; trattamenti e pulizia delle fessure.
- Pidocchi pollini (mallofagi): vivono sul corpo; controlla sotto le ali e attorno alla cloaca.
- Difesa: bagni di sabbia/cenere, terra di diatomee, antiparassitari mirati.

## Parassiti interni e malattie
- Vermi intestinali (ascaridi, capillaria): sverminazione periodica secondo necessità.
- Coccidiosi: soprattutto nei giovani, favorita da lettiera umida; igiene e asciutto sono la prima difesa.
- Vaccinazioni: i pulcini sono spesso già vaccinati contro la malattia di Marek; per il piccolo allevamento familiare la profilassi vaccinale ulteriore va valutata con il veterinario.

## Accorgimenti per il clima costiero
L'umidità costiera favorisce acari, coccidi e muffe. Tieni la lettiera asciutta, garantisci ventilazione (vedi [[Pollaio_Struttura]]) e intensifica i controlli antiparassitari in estate.

## Errori comuni
- Saltare la quarantena dei nuovi capi: si introducono malattie e parassiti.
- Lettiera umida trascurata: anticamera di coccidiosi e problemi respiratori.
- Non controllare i posatoi di notte: gli acari rossi passano inosservati finché non è grave.

## Segnali da tenere d'occhio
Cresta pallida o violacea, piumaggio arruffato, apatia, calo di appetito o di deposizione, difficoltà respiratorie, feci anomale (diarrea, presenza di sangue), prurito e perdita di penne attorno alla cloaca. In caso di dubbio o sintomi diffusi, consulta un veterinario.

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
- [[Pollaio_Struttura]]
- [[Deposizione_Uova]]

#pollicoltura #gestione
