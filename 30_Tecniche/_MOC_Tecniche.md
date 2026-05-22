---
tipo: moc
ambito: tecniche colturali
---

# 🛠️ MOC Tecniche

Pratiche, tecniche colturali e gestione del terreno, raccolte per tema.

```dataview
TABLE area AS "Area", difficolta AS "Difficoltà"
FROM "agricoltura/30_Tecniche"
WHERE tipo = "tecnica"
SORT area ASC, file.name ASC
```

## 💧 Acqua e irrigazione
Hub di riferimento: [[Irrigazione_Panoramica]] (confronto dei metodi e guida alla scelta).

```dataview
TABLE difficolta AS "Difficoltà", stagione AS "Stagione"
FROM "agricoltura/30_Tecniche"
WHERE tipo = "tecnica" AND area = "acqua"
SORT difficolta ASC, file.name ASC
```

## Aree previste
- Suolo e fertilità: compostaggio, sovesci, pacciamatura.
- Acqua: panoramica e confronto, goccia, subirrigazione, microaspersione, a pioggia, conca e solco, swale, gestione idrica estiva, raccolta acqua piovana.
- Difesa: difesa biologica, consociazioni, biodiversità funzionale.
- Pianificazione: rotazioni, calendario operativo, semenzaio.
- Specifiche costa: gestione salsedine, frangivento, protezione gelate marine.

#moc #tecniche
