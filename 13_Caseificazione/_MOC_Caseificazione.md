---
tipo: moc
ambito: caseificazione
---

# 🧀 MOC Caseificazione

Mappa dell'area lavorazione del latte: tecniche di base, schede dei formaggi e registro di produzione.
Trasformazione del latte di capra, pecora e asina prodotto in azienda, con attenzione a igiene, resa e tracciabilità per la piccola vendita. Clima mediterraneo costiero (La Spezia).

## 🥛 Tecniche di base
```dataview
TABLE area AS "Area", fase AS "Fase", difficolta AS "Diff."
FROM "agricoltura/13_Caseificazione/Tecniche"
WHERE tipo = "tecnica_casearia"
SORT fase ASC
```

## 🧀 Formaggi e latticini
```dataview
TABLE tipo_prodotto AS "Tipo", latte AS "Latte", coagulazione AS "Coagulazione", stagionatura AS "Stagionatura", difficolta AS "Diff."
FROM "agricoltura/13_Caseificazione/Formaggi"
WHERE tipo = "scheda_formaggio"
SORT difficolta ASC
```

## 📒 Registri
```dataview
TABLE tipo AS "Tipo"
FROM "agricoltura/13_Caseificazione/Registro"
SORT file.name ASC
```

## 🔗 Collegamenti utili
- [[_MOC_Allevamento_Latte]] — gli animali e la produzione del latte
- [[Mungitura_Igiene_Latte]] — qualità del latte alla fonte, a monte della trasformazione
- [[_MOC_Tecniche]] — tecniche di azienda (compostaggio del siero/scarti, ecc.)

> Le tabelle si popolano automaticamente man mano che aggiungi schede con i template `template_tecnica_casearia` e `template_formaggio`.

#moc #caseificazione
