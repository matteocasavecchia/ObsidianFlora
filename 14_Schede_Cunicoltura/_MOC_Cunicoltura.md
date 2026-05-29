---
tipo: moc
ambito: cunicoltura
---

# 🐰 MOC Cunicoltura

Mappa dell'area cunicoltura: razze da carne e gestione del coniglio domestico.
Allevamento familiare orientato alla produzione di carne, clima costiero mediterraneo (La Spezia).

## 🐰 Razze
```dataview
TABLE attitudine AS "Attitudine", peso_macellazione_kg AS "Macell. (kg)", eta_macellazione_mesi AS "Età (mesi)", prolificita AS "Prolificità", rusticita AS "Rusticità"
FROM "agricoltura/14_Schede_Cunicoltura/Razze"
WHERE tipo = "scheda_razza_cunicola"
SORT peso_macellazione_kg DESC
```

## 🔗 Collegamenti utili
- [[_MOC_Tecniche]] — tecniche (compostaggio della lettiera, ecc.)
- [[_MOC_Piante]] — schede piante (per foraggio verde e scarti dell'orto)
- [[calendario_master]] — interventi stagionali

> La tabella si popola automaticamente man mano che aggiungi schede con il template `template_razza_cunicola`.

#moc #cunicoltura
