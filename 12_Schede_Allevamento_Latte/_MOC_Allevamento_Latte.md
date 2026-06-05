---
tipo: moc
ambito: allevamento_latte
---

# 🐐 MOC Allevamento da Latte

Mappa dell'area allevamento di piccoli ruminanti da latte (capre, pecore) e degli equini (asini e cavalli da lavoro): razze, schede di gestione e registri.
Piccolo allevamento orientato alla produzione di latte e alla caseificazione, con possibilità di vendita locale. Clima mediterraneo costiero (La Spezia).

## 🐑 Razze
```dataview
TABLE categoria AS "Specie", latte_litri_lattazione AS "Litri/lattaz.", durata_lattazione_giorni AS "Giorni latt.", grasso_pct AS "Grasso %", rusticita AS "Rusticità", adatta_clima_costiero AS "Costa"
FROM "agricoltura/12_Schede_Allevamento_Latte/Razze"
WHERE tipo = "scheda_razza_lattifera"
SORT latte_litri_lattazione DESC
```

## 🐴 Equini (asini e cavalli)
```dataview
TABLE categoria AS "Specie", attitudine AS "Attitudine", origine AS "Origine", rusticita AS "Rusticità", adatta_clima_costiero AS "Costa"
FROM "agricoltura/12_Schede_Allevamento_Latte/Razze"
WHERE tipo = "scheda_razza_equina"
SORT file.name ASC
```

## 🛠️ Gestione
```dataview
TABLE area AS "Area", frequenza AS "Frequenza", stagione AS "Stagione", difficolta AS "Diff."
FROM "agricoltura/12_Schede_Allevamento_Latte/Gestione"
WHERE tipo = "gestione_allevamento"
SORT area ASC
```

## 📒 Registri
```dataview
TABLE tipo AS "Tipo"
FROM "agricoltura/12_Schede_Allevamento_Latte/Registro"
SORT file.name ASC
```

## 📅 Calendario
- [[Calendario_Allevamento]] — promemoria stagionale di monte, parti, lattazione e pascolo

## 🔗 Collegamenti utili
- [[_MOC_Caseificazione]] — lavorazione del latte e schede formaggi
- [[_MOC_Pollicoltura]] — l'altra area zootecnica (pollaio familiare)
- [[_MOC_Piante]] — schede piante (foraggio, pascolo, scarti orto)
- [[_MOC_Tecniche]] — tecniche (compostaggio del letame, ecc.)
- [[calendario_master]] — interventi stagionali dell'orto

> Le tabelle si popolano automaticamente man mano che aggiungi schede con i template `template_razza_lattifera`, `template_razza_equina` e `template_gestione_allevamento`.

#moc #allevamento_latte
