---
stagione: Inverno
mesi: "Dicembre, Gennaio, Febbraio"
attivita_principale: Riposo, potature, pianificazione
---

# ❄️ Semina e Raccolta: Inverno
> Periodo: Dicembre - Gennaio - Febbraio

Periodo di riposo vegetativo, ideale per la pianificazione e le potature.

## 🌱 Semine (Sotto Tunnel o Semenzaio)
- **Gennaio:** [[Lattuga|Lattughe]] da taglio, [[Radicchio|radicchio]], [[Sedano|sedano]] (in ambiente protetto).
- **Febbraio:** [[Cipolla|Cipolle]], [[Patata|patate]] (al Sud), [[Pomodoro|pomodori]] in semenzaio riscaldato.

## 🧺 Raccolte
- Cavoli neri, verze, [[Radicchio|radicchi]] invernali, [[Spinacio|spinaci]], carciofi (al Sud).
- Agrumi ([[Limone|limoni]], [[Arancio|arance]], [[Mandarino|mandarini]]).

## 🍽️ Ricette di stagione
```dataview
TABLE portata AS "Portata", ingredienti_orto AS "Dall'orto"
FROM "agricoltura/50_Ricette"
WHERE tipo = "ricetta" AND contains(stagione, this.stagione)
SORT file.name ASC
```

---
**Pianificazione:** [[Rotazione_Colture]] | [[Semenzaio_Moltiplicazione]]
#inverno #riposo #pianificazione
