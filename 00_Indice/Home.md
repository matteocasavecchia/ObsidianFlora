---
tipo: home
clima_riferimento: Mediterraneo costiero (Centro Italia)
---

# 🌱 Vault Agricoltura

Casa base del vault. Da qui raggiungi tutto.

## Mappe tematiche (MOC)
- [[_MOC_Piante|🥬 Schede Piante]]
- [[_MOC_Pollicoltura|🐔 Pollicoltura]]
- [[_MOC_Allevamento_Latte|🐐 Allevamento da Latte]]
- [[_MOC_Caseificazione|🧀 Caseificazione]]
- [[calendario_master|📅 Calendario Master]]
- [[_MOC_Tecniche|🛠️ Tecniche e Pratiche]]
- [[_README_Diario|📓 Diario di Campo]]

## Stagioni
- [[primavera|🌸 Primavera]] · [[estate|☀️ Estate]] · [[autunno|🍂 Autunno]] · [[inverno|❄️ Inverno]]

## Riferimento
- Clima: mediterraneo costiero, inverni miti (gelate rare), estati calde-secche, umidità marina, esposizione a salsedine e venti.
- Approccio: biologico/sostenibile, orto domestico + frutticoltura + pollaio familiare integrato + piccolo allevamento da latte e caseificazione.

## Ultime aggiunte
```dataview
TABLE file.mtime AS "Modificato"
FROM "agricoltura"
WHERE file.name != "Home"
SORT file.mtime DESC
LIMIT 10
```

#home #vault

Da aggiungere in futuro:
- Aggiungiamo una sezione di ricette che prevedano l'uso dei prodotti dell'orto? Probabilmente ha senso anche una sorta di ordine in funzione delle stagioni, in modo da poter consultare le ricette in modo stagionale. E' comunque importante che ci siano tutti i link tra ricette e piante.
