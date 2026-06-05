---
tipo: moc
ambito: schede piante
---

# 🥬 MOC Piante

Mappa di tutte le schede pianta del vault, suddivise per categoria.

## 🥕 Orticole
```dataview
TABLE famiglia AS "Famiglia", ciclo AS "Ciclo", periodo_semina AS "Semina", periodo_raccolta AS "Raccolta"
FROM "agricoltura/10_Schede_Piante/Orticole"
WHERE tipo = "scheda_pianta"
SORT file.name ASC
```

## 🌿 Aromatiche
```dataview
TABLE famiglia AS "Famiglia", perenne AS "Perenne", esposizione AS "Esposizione"
FROM "agricoltura/10_Schede_Piante/Aromatiche"
WHERE tipo = "scheda_pianta"
SORT file.name ASC
```

## 🌳 Alberi da frutto
```dataview
TABLE famiglia AS "Famiglia", periodo_raccolta AS "Raccolta", periodo_potatura AS "Potatura"
FROM "agricoltura/10_Schede_Piante/Alberi_da_Frutto"
WHERE tipo = "scheda_pianta"
SORT file.name ASC
```

## 🌾 Cereali e grani antichi
```dataview
TABLE nome_scientifico AS "Specie", periodo_semina AS "Semina", periodo_raccolta AS "Raccolta", fabbisogno_idrico AS "Acqua"
FROM "agricoltura/10_Schede_Piante/Cereali"
WHERE tipo = "scheda_pianta"
SORT file.name ASC
```

> Le tabelle si popolano automaticamente quando aggiungi schede con il template corretto.

#moc #piante
