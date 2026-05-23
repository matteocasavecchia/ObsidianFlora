---
tipo: moc
ambito: ricette
---

# 🍽️ MOC Ricette

Ricette che valorizzano i prodotti dell'orto, della frutta e dell'aromatica del vault, ordinate per stagione. Ogni ricetta è collegata via wikilink alle piante che utilizza (campo `ingredienti_orto`), così il legame ricetta-pianta è navigabile in entrambi i sensi.

## 🌸 Primavera
```dataview
TABLE portata AS "Portata", ingredienti_orto AS "Dall'orto", tempo_minuti AS "Min", difficolta AS "Diff."
FROM "agricoltura/50_Ricette"
WHERE tipo = "ricetta" AND contains(stagione, "Primavera")
SORT file.name ASC
```

## ☀️ Estate
```dataview
TABLE portata AS "Portata", ingredienti_orto AS "Dall'orto", tempo_minuti AS "Min", difficolta AS "Diff."
FROM "agricoltura/50_Ricette"
WHERE tipo = "ricetta" AND contains(stagione, "Estate")
SORT file.name ASC
```

## 🍂 Autunno
```dataview
TABLE portata AS "Portata", ingredienti_orto AS "Dall'orto", tempo_minuti AS "Min", difficolta AS "Diff."
FROM "agricoltura/50_Ricette"
WHERE tipo = "ricetta" AND contains(stagione, "Autunno")
SORT file.name ASC
```

## ❄️ Inverno
```dataview
TABLE portata AS "Portata", ingredienti_orto AS "Dall'orto", tempo_minuti AS "Min", difficolta AS "Diff."
FROM "agricoltura/50_Ricette"
WHERE tipo = "ricetta" AND contains(stagione, "Inverno")
SORT file.name ASC
```

## 📒 Tutte le ricette per portata
```dataview
TABLE stagione AS "Stagione", ingredienti_orto AS "Dall'orto"
FROM "agricoltura/50_Ricette"
WHERE tipo = "ricetta"
SORT portata ASC, file.name ASC
```

> Le tabelle si popolano da sole man mano che aggiungi ricette con il template `template_ricetta`.

#moc #ricette
