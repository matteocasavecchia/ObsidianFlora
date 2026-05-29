---
tipo: stagione
stagione: Autunno
mesi: "Settembre, Ottobre, Novembre"
attivita_principale: Raccolta autunnale e preparazione invernale
---

# 🍂 Semina e Raccolta: Autunno
> Periodo: Settembre - Ottobre - Novembre

Fase di transizione verso le colture resistenti al freddo e preparazione del terreno.

## 🌱 Semine
- **Settembre:** Cime di rapa, [[Ravanello|ravanelli]], [[Rucola]], [[Prezzemolo|prezzemolo]].
- **Ottobre:** [[Aglio]], [[Scalogno]], [[Fava|fave]], [[Pisello|piselli]] (varietà resistenti).
- **Novembre:** Trapianto di alberi da frutto e arbusti a radice nuda.

## 🧺 Raccolte
- [[Zucca|Zucche]], [[Cavolfiore|cavolfiori]], verze, [[Finocchio|finocchi]], porri.
- [[Olivo|Olive]] (dipendono dalla latitudine e varietà).
- Castagne e piccoli frutti autunnali.

## 🍽️ Ricette di stagione
```dataview
TABLE portata AS "Portata", ingredienti_orto AS "Dall'orto"
FROM "agricoltura/50_Ricette"
WHERE tipo = "ricetta" AND contains(stagione, this.stagione)
SORT file.name ASC
```

---
**Vedi anche:** [[Forme_Allevamento_Potatura]] | [[Sovesci]]
#autunno #preparazione #orto
