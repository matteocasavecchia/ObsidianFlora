---
tipo: moc
ambito: calendario
---

# 📅 MOC Calendario

Mappa di tutti i riferimenti temporali del vault: stagioni, calendario operativo mensile, calendario master Dataview.

## Stagioni
```dataview
TABLE mesi AS "Mesi", attivita_principale AS "Focus"
FROM "agricoltura/20_Calendario/Stagioni"
WHERE stagione != null
SORT file.name ASC
```

## Calendario operativo mensile
```dataview
TABLE numero_mese AS "Mese", stagione_principale AS "Stagione", clima_costa_centro_italia AS "Clima"
FROM "agricoltura/20_Calendario/Mensile"
WHERE tipo = "calendario"
SORT numero_mese ASC
```

## Master
- [[calendario_master|📅 Calendario Master (riepilogo stagioni)]]

## Navigazione veloce per mese
- 🥶 [[01_Gennaio|Gennaio]] · [[02_Febbraio|Febbraio]] · [[12_Dicembre|Dicembre]]
- 🌸 [[03_Marzo|Marzo]] · [[04_Aprile|Aprile]] · [[05_Maggio|Maggio]]
- ☀️ [[06_Giugno|Giugno]] · [[07_Luglio|Luglio]] · [[08_Agosto|Agosto]]
- 🍂 [[09_Settembre|Settembre]] · [[10_Ottobre|Ottobre]] · [[11_Novembre|Novembre]]

#moc #calendario
