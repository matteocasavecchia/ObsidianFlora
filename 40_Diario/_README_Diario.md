---
tipo: readme
ambito: diario di campo
---

# 📓 Diario di Campo

Cartella dei daily notes (plugin **Periodic Notes**). Ogni giornata di lavoro avrà una nota con data `YYYY-MM-DD` collegata automaticamente alle piante e tecniche citate.

## Configurazione Periodic Notes
- Daily notes folder: `agricoltura/40_Diario`
- Daily notes format: `YYYY-MM-DD`
- Daily notes template: `agricoltura/90_Template/template_diario.md`

> Il template verrà creato in Fase 2.

## Ultimi interventi
```dataview
TABLE meteo AS "Meteo", piante AS "Piante", interventi AS "Interventi"
FROM "agricoltura/40_Diario"
WHERE tipo = "diario"
SORT file.name DESC
LIMIT 15
```

#diario #readme
