---
tipo: moc
ambito: pollicoltura
---

# 🐔 MOC Pollicoltura

Mappa dell'area pollicoltura: razze, schede di gestione e registro del pollaio.
Allevamento familiare orientato alla produzione di uova, clima costiero mediterraneo (La Spezia).

## 🐓 Razze
```dataview
TABLE attitudine AS "Attitudine", uova_anno AS "Uova/anno", colore_uovo AS "Guscio", rusticita AS "Rusticità", adatta_clima_costiero AS "Costa"
FROM "agricoltura/11_Schede_Pollicoltura/Razze"
WHERE tipo = "scheda_razza"
SORT uova_anno DESC
```

## 🛠️ Gestione
```dataview
TABLE area AS "Area", frequenza AS "Frequenza", stagione AS "Stagione", difficolta AS "Diff."
FROM "agricoltura/11_Schede_Pollicoltura/Gestione"
WHERE tipo = "gestione_pollaio"
SORT area ASC
```

## 🥚 Registro
- [[Registro_Uova]] — conteggio della deposizione

## 📅 Calendario
- [[Calendario_Pollaio]] — promemoria stagionale della gestione

## 🔗 Collegamenti utili
- [[Pollaio_e_Orto]] — integrazione orto-pollaio (pollina, scarti, antiparassita)
- [[_MOC_Piante]] — schede piante (per scarti orto, sovesci, consociazione orto-pollaio)
- [[_MOC_Tecniche]] — tecniche (compostaggio della pollina, ecc.)
- [[calendario_master]] — interventi stagionali dell'orto

> Le tabelle si popolano automaticamente man mano che aggiungi schede con i template `template_razza_gallina` e `template_gestione_pollaio`.

#moc #pollicoltura
