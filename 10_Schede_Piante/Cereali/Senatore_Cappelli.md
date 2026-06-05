---
tipo: scheda_pianta
categoria: cereale
nome_comune: Senatore Cappelli
nome_scientifico: Triticum turgidum subsp. durum
famiglia: Poaceae
ciclo: annuale
periodo_semina: "Ottobre-Novembre"
periodo_raccolta: "Giugno-Luglio"
calendario:
  - tipo: semina
    da_settimana: 42
    a_settimana: 48
    luna: calante
  - tipo: raccolta
    da_settimana: 25
    a_settimana: 30
    luna: calante
distanza_pianta_cm: 5
distanza_fila_cm: 15
profondita_semina_cm: 4
esposizione: sole pieno
ph_min: 6.0
ph_max: 7.5
fabbisogno_idrico: basso
difficolta: 2
consociazioni_buone:
  - Leguminose (sovescio precedente)
  - Favino
consociazioni_da_evitare:
  - Altri cereali
successioni_buone:
  - Leguminose
  - Favino
  - Veccia
predecessori_da_evitare:
  - Frumento
  - Orzo
  - Mais
tags:
  - pianta
  - cereale
  - poaceae
  - grano_antico
---

# 🌾 Senatore Cappelli

> Famiglia: `=this.famiglia` · Ciclo: `=this.ciclo` · Difficoltà: `=this.difficolta`/5

## Caratteristiche
Frumento duro selezionato nei primi del Novecento da Nazareno Strampelli a partire da una popolazione tunisina (Jenah Rhetifah) e dedicato al senatore Raffaele Cappelli. È il capostipite di gran parte del grano duro mediterraneo moderno. Pianta **alta** (140-180 cm), a taglia molto più sviluppata dei frumenti moderni: questo lo rende rustico e capace di soffocare le infestanti, ma anche soggetto ad allettamento. Cariosside ambrata, ricca, con glutine "tenace ma poco forte" molto apprezzato per pasta e pane di semola dal sapore intenso. Adatto al **biologico** e ai terreni poveri del Centro-Sud, dove le concimazioni azotate spinte sarebbero controproducenti (favoriscono l'allettamento).

## Semina e trapianto
- Solo **semina diretta** a spaglio o a file, in autunno
- Ottobre-novembre, su letto di semina ben preparato e non eccessivamente fine
- Profondità: 3-5 cm
- Dose indicativa: ~180-200 kg/ha (più rada del grano moderno, vista la taglia alta)
- Evitare semine troppo fitte: peggiorano l'allettamento

## Cura
- Esposizione: sole pieno
- Irrigazione: in asciutta nella maggior parte degli areali; eventuale soccorso solo in primavere molto siccitose alla levata-spigatura
- Concimazione: **azoto moderato**. È il punto chiave: troppo azoto = piante che si allettano. Meglio sfruttare l'azoto residuo di una leguminosa in precessione
- Controllo infestanti: la taglia alta e la rapidità di accestimento aiutano molto; in biologico, falsa semina e rotazione

## Avversità tipiche
- **Allettamento**: il rischio numero uno per le varietà a taglia alta. Semine rade, poco azoto, scelta di terreni non troppo fertili
- **Ruggini** (bruna, gialla): sorvegliare, rusticità discreta ma non immune
- **Septoria** e **fusariosi della spiga**: favorite da primavere umide; rotazione e residui ben gestiti
- **Afidi** della spiga: monitoraggio, di norma non servono interventi

## Raccolta e conservazione
- Periodo: `=this.periodo_raccolta`, a piena maturazione (cariosside dura, paglia secca, umidità della granella ~13%)
- Mietitrebbia regolata dolce per non spezzare le cariossidi
- Conservazione della granella: pulita, secca e arieggiata, al riparo da umidità e insetti dei granai (tonchi, punteruoli)
- Si macina in **semola** per pasta e pane; molitura a pietra per conservare germe e crusca

## Consociazioni e rotazioni
- **Compagne**: in coltura è una coltura pura; conta soprattutto la **rotazione**
- **Da evitare**: ristoppio (grano dopo grano) e altri cereali in successione stretta
- **Buoni predecessori**: leguminose da granella o da sovescio (favino, veccia, pisello), che lasciano azoto
- **Da non far seguire a**: frumento, orzo, mais (parassiti e stanchezza del terreno)

## Note clima costiero
Frumento duro **mediterraneo per eccellenza**: ama gli inverni miti e le primavere asciutte e luminose della costa centro-italiana. Tollera bene il caldo e la siccità di fine ciclo, anzi li sfrutta per la maturazione. Buona tolleranza alla salsedine rispetto a molte orticole. L'unico vero nemico costiero è il **vento** sulle piante alte in fase di spigatura: allettamento. In zone molto ventose, valutare le selezioni a taglia leggermente ridotta o un frangivento.

## Diario di campo collegato
```dataview
TABLE meteo AS "Meteo", interventi AS "Interventi"
FROM "agricoltura/40_Diario"
WHERE contains(piante, this.file.link) OR contains(file.outlinks, this.file.link)
SORT file.name DESC
LIMIT 10
```

## 🍽️ Ricette collegate
```dataview
TABLE stagione AS "Stagione", portata AS "Portata"
FROM "agricoltura/50_Ricette"
WHERE tipo = "ricetta" AND contains(ingredienti_orto, this.file.link)
SORT file.name ASC
```

## Note personali
- 

## Riferimenti
- [[_MOC_Piante]]
- Grani antichi: [[Saragolla]] · [[Timilia]] · [[Russello]]
- [[autunno]] · [[estate]]

#pianta #cereale #grano_antico
