---
stagione: Estate
mesi: "Giugno, Luglio, Agosto"
attivita_principale: Raccolta e Irrigazione
---

# ☀️ Semina e Raccolta: Estate
> Periodo: Giugno - Luglio - Agosto

In questo periodo l'attenzione si sposta sulla gestione idrica e sulle prime grandi raccolte.

## 🌱 Semine
- **Giugno:** [[Fagiolino|Fagiolini]], [[Bietola|bietole]] da costa, cicorie tardive.
- **Luglio:** [[Finocchio|Finocchi]], cavoli, [[Broccolo|broccoli]], porri (per l'inverno).
- **Agosto:** [[Spinacio|Spinaci]], [[Valeriana]], [[Radicchio|radicchio]], scarola.

## 🧺 Raccolte
- [[Pomodoro|Pomodori]], [[Zucchina|zucchine]], [[Peperone|peperoni]], [[Melanzana|melanzane]], [[Cetriolo|cetrioli]], [[Melone|meloni]], [[Anguria|angurie]].
- [[Cipolla|Cipolle]] e [[Aglio]] (da essiccare).
- [[Patata|Patate]] novelle.

## 🍽️ Ricette di stagione
```dataview
TABLE portata AS "Portata", ingredienti_orto AS "Dall'orto"
FROM "agricoltura/50_Ricette"
WHERE tipo = "ricetta" AND contains(stagione, this.stagione)
SORT file.name ASC
```

---
**Correlati:** [[Irrigazione_Panoramica]] | [[Irrigazione_a_Goccia]] | [[Gestione_Idrica_Estiva]] | [[Compostaggio]]
#estate #raccolto #sole
