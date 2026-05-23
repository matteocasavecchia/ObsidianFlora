---
stagione: Primavera
mesi: "Marzo, Aprile, Maggio"
attivita_principale: Semina estiva
---

# 🥬 Semina e Raccolta: Primavera
> Periodo: Marzo - Aprile - Maggio

La primavera è il momento del risveglio e della semina della maggior parte degli ortaggi estivi.

## 🌱 Semine (Pieno Campo)
- **Marzo:** [[Pisello|Piselli]], [[Fava|fave]], [[Cece|ceci]], [[Carota|carote]], [[Bietola|bietole]], insalate, [[Ravanello|ravanelli]].
- **Aprile:** [[Patata|Patate]], barbabietole, [[Zucca|zucche]], [[Zucchina|zucchine]], [[Fagiolo|fagioli]].
- **Maggio:** [[Pomodoro|Pomodori]], [[Peperone|peperoni]], [[Melanzana|melanzane]] (trapianto), [[Cetriolo|cetrioli]], [[Mais_Dolce|mais]].

## 🧺 Raccolte
- Asparagi, carciofi, [[Spinacio|spinaci]] invernali, prime [[Lattuga|lattughe]], cipollotti, [[Fava|fave]].

## 🍽️ Ricette di stagione
```dataview
TABLE portata AS "Portata", ingredienti_orto AS "Dall'orto"
FROM "agricoltura/50_Ricette"
WHERE tipo = "ricetta" AND contains(stagione, this.stagione)
SORT file.name ASC
```

---
**Note Progetto:** [[Rotazione_Colture]] | [[Swale_Canali_Infiltrazione]]
#primavera #semina #orto
