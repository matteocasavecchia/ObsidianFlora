---
tipo: registro_uova
ambito: pollicoltura
anno: 2026
tags:
  - pollicoltura
  - registro
  - uova
---

# 🥚 Registro Uova

Tieni traccia della deposizione per cogliere subito cali anomali (stress, parassiti, predatori notturni) e distinguere i normali andamenti stagionali. Compila la tabella, oppure annota le uova giorno per giorno nel [[_README_Diario|diario]] alla voce "Pollaio".

## Conteggio settimanale
| Settimana (dal) | N° galline in deposizione | Uova totali | Media/gallina/giorno | Note |
|---|---|---|---|---|
|  |  |  |  |  |

## Uova annotate nel diario
```dataview
TABLE WITHOUT ID file.link AS "Giorno", meteo AS "Meteo"
FROM "agricoltura/40_Diario"
WHERE tipo = "diario"
SORT file.name DESC
LIMIT 30
```

## Promemoria di lettura
- Calo netto e improvviso non spiegabile dalla stagione: controlla parassiti, predatori notturni e segnali di malattia (vedi [[Salute_Profilassi]]).
- Calo graduale in autunno-inverno: in gran parte fisiologico (giornate corte e muta), vedi [[Deposizione_Uova]].
- Gusci molli o deformi: rivedi calcio e gestione del caldo (vedi [[Alimentazione]]).

## Riferimenti
- [[_MOC_Pollicoltura]]
- [[Deposizione_Uova]]

#pollicoltura #registro #uova
