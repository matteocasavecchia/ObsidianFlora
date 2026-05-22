---
tipo: gestione_allevamento
titolo: Mungitura e igiene del latte
area: mungitura
difficolta: 3
frequenza: quotidiana
stagione: durante la lattazione
materiali: detergenti/sanificanti, carta monouso, soluzione per i capezzoli (pre/post dipping), filtri latte
strumenti: secchio o mungitrice, contenitori in acciaio, frigorifero/tank di refrigerazione
tags:
  - allevamento_latte
  - gestione
---

# 🛠️ Mungitura e igiene del latte

> Area: mungitura · Difficoltà: 3/5 · Frequenza: quotidiana

## A cosa serve
La mungitura igienica è il punto critico tra animale e prodotto: determina la carica batterica, la conservabilità e la sicurezza del latte, e quindi anche la riuscita dei formaggi. È anche il momento chiave per prevenire le mastiti. Per la vendita, la qualità del latte alla fonte è il primo requisito (vedi [[Anagrafe_Normativa]]).

## Quando farlo
- Stagione / periodo: durante tutta la lattazione.
- Frequenza: di norma due munte al giorno (mattina e sera) a orari regolari; alcune piccole realtà mungono una volta al giorno a fine lattazione.

## Procedimento
1. Prepara un ambiente pulito e tranquillo; lavati le mani e indossa attrezzatura pulita.
2. Pre-dipping: pulisci e disinfetta i capezzoli, asciuga con carta monouso (una per capo).
3. Elimina i primi getti in un contenitore a parte: controlli la presenza di grumi/anomalie (segno di mastite) e scarti il latte più ricco di batteri.
4. Mungi a fondo, a mano o con mungitrice, evitando di traumatizzare la mammella.
5. Post-dipping: disinfetta i capezzoli per proteggere il canale ancora aperto.
6. Filtra subito il latte e raffreddalo rapidamente a +4 °C; conservalo coperto fino alla trasformazione o al ritiro.

## Materiali e strumenti
- Materiali: detergenti e sanificanti idonei, carta monouso, prodotto per pre/post dipping, filtri per il latte.
- Strumenti: secchio in acciaio o mungitrice (a bidone/carrellata per piccoli numeri), contenitori in acciaio inox, frigorifero o tank per la refrigerazione.

## Igiene e sanificazione dell'attrezzatura
Tutto ciò che tocca il latte va lavato e sanificato dopo ogni munta: risciacquo iniziale con acqua tiepida, lavaggio con detergente alcalino a caldo, risciacquo, e periodica disacidificazione. Asciugatura all'aria su superfici pulite. Vedi anche [[Igiene_Sanificazione]] per la parte di trasformazione.

## Accorgimenti per il clima costiero
Con il caldo il latte si deteriora in fretta: raffredda subito e accorcia i tempi tra mungitura e lavorazione/conservazione. L'umidità marina favorisce le muffe sull'attrezzatura: cura asciugatura e ventilazione della sala/locale di mungitura.

## Errori comuni
- Saltare il controllo dei primi getti: mastiti non individuate finiscono nel latte di massa.
- Mancato raffreddamento rapido: carica batterica fuori controllo.
- Igiene approssimativa di mani, mammella e attrezzatura.
- Stress agli animali (rumore, fretta, dolore): bloccano la "discesa" del latte e riducono la resa.

## Segnali da tenere d'occhio
Grumi o latte acquoso (mastite), mammelle gonfie/arrossate/calde, cali improvvisi di produzione, sapori o odori anomali del latte.

## Diario di campo collegato
```dataview
TABLE file.name AS "Nota", meteo AS "Meteo"
FROM "agricoltura/40_Diario"
WHERE contains(file.outlinks, this.file.link)
SORT file.name DESC
LIMIT 10
```

## Riferimenti
- [[_MOC_Allevamento_Latte]]
- [[_MOC_Caseificazione]]
- [[Salute_Profilassi_Latte]]
- [[Anagrafe_Normativa]]

#allevamento_latte #gestione
