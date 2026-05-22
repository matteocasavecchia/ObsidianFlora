---
tipo: gestione_pollaio
titolo: Deposizione Uova
area: deposizione
difficolta: 2
frequenza: raccolta quotidiana
stagione: tutto l'anno (picco primavera, calo autunno-inverno)
materiali: nidi con lettiera pulita, eventuale uovo finto come richiamo
strumenti: cestino per la raccolta, registro uova
tags:
  - pollicoltura
  - gestione
---

# 🛠️ Deposizione Uova

> Area: deposizione · Difficoltà: 2/5 · Frequenza: raccolta quotidiana

## A cosa serve
Capire e gestire la deposizione permette di massimizzare le uova in modo sano e di riconoscere subito i problemi (gusci deboli, cali, ovofagia). Per un pollaio familiare l'obiettivo è una produzione costante e uova pulite e integre.

## Quando farlo
- Stagione / periodo: si depone tutto l'anno, con picco in primavera e calo naturale in autunno-inverno e durante la muta.
- Frequenza: raccolta delle uova 1-2 volte al giorno (più spesso in estate per evitare che si scaldino o vengano beccate).

## Quando iniziano a deporre
Le ovaiole iniziano in genere a 18-22 settimane (circa 5 mesi); ibridi commerciali anche un po' prima, razze rustiche talvolta più tardi. La prima uova sono piccole e si normalizzano nelle settimane successive.

## Fattori che influenzano la deposizione
1. Luce: servono circa 14-16 ore di luce al giorno per una deposizione sostenuta; con le giornate corte la produzione cala fisiologicamente.
2. Alimentazione: proteine e calcio adeguati (vedi [[Alimentazione]]).
3. Età: massima nel primo-secondo anno, poi cala progressivamente.
4. Muta: in autunno le galline rifanno il piumaggio e smettono di deporre per alcune settimane.
5. Stress e caldo: spostamenti, predatori, sovraffollamento e ondate di calore riducono la deposizione.

## Materiali e strumenti
- Materiali: nidi puliti con lettiera morbida, eventualmente un uovo finto per invogliare a deporre nel nido giusto.
- Strumenti: cestino per la raccolta, registro (vedi cartella Registro) per annotare le uova raccolte.

## Procedimento (buone pratiche quotidiane)
1. Raccogli le uova al mattino e, in estate, anche nel pomeriggio.
2. Controlla che i nidi siano puliti e asciutti; sostituisci la lettiera sporca.
3. Annota la quantità (utile per notare cali improvvisi).
4. Conserva le uova in luogo fresco; se non lavate si conservano più a lungo grazie alla cuticola naturale.

## Accorgimenti per il clima costiero
In estate le uova si deteriorano in fretta al caldo: raccogli spesso e conservale al fresco. L'umidità nei nidi favorisce uova sporche e parassiti: tieni la lettiera asciutta.

## Errori comuni
- Raccogliere di rado: uova sporche, rotte e rischio di ovofagia (galline che imparano a mangiare le uova).
- Nidi pochi o troppo illuminati: depongono a terra o negli angoli.
- Attribuire al "problema" un calo che è in realtà stagionale (giornate corte) o dovuto alla muta.

## Segnali da tenere d'occhio
Gusci molli/rugosi (calcio o caldo), uova deposte a terra (nidi non graditi), gusci beccati o vuoti (ovofagia da correggere subito), calo improvviso non stagionale (stress, parassiti, predatori notturni, malattia).

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
- [[Alimentazione]]
- [[Salute_Profilassi]]

#pollicoltura #gestione
