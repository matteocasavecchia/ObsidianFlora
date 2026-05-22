---
tipo: gestione_pollaio
titolo: Alimentazione
area: alimentazione
difficolta: 2
frequenza: quotidiana
stagione: tutto l'anno
materiali: mangime per ovaiole, granaglie, grit, conchiglie/calcio, acqua pulita
strumenti: mangiatoia, abbeveratoio, contenitore stagno per il mangime
tags:
  - pollicoltura
  - gestione
---

# 🛠️ Alimentazione

> Area: alimentazione · Difficoltà: 2/5 · Frequenza: quotidiana

## A cosa serve
Una corretta alimentazione sostiene la deposizione, la qualità del guscio e la salute generale. Per le ovaiole il punto chiave è l'apporto bilanciato di proteine e calcio, con acqua pulita sempre disponibile.

## Quando farlo
- Stagione / periodo: tutto l'anno; in estate aumenta molto il consumo d'acqua, in inverno cala la deposizione.
- Frequenza: cibo e acqua controllati ogni giorno; mangime a disposizione (ad libitum) o in 1-2 razioni.

## Cosa dare
- Mangime completo per ovaiole: circa 16-17% di proteine e 3,5-4% di calcio. È la base della dieta.
- Consumo medio: ~120-130 g di mangime al giorno per gallina.
- Acqua: sempre fresca e pulita; ~250-300 ml/giorno a gallina, molto di più con il caldo.
- Grit (graniglia insolubile): aiuta il ventriglio a "macinare" il cibo, utile soprattutto se mangiano granaglie ed erba.
- Calcio (gusci d'ostrica o conchiglie tritate): a disposizione separata, fondamentale per gusci robusti.

## Materiali e strumenti
- Materiali: mangime ovaiole, eventuali granaglie (mais, grano) come integrazione, grit, fonte di calcio, acqua.
- Strumenti: mangiatoia a tramoggia (riduce gli sprechi e tiene lontani i roditori), abbeveratoio pulito, bidone a chiusura stagna per conservare il mangime.

## Fasi di crescita
1. Pulcini (0-6 settimane): mangime starter ad alto tenore proteico.
2. Pollastre (6-18 settimane): mangime growth/accrescimento.
3. Inizio deposizione (~18-22 settimane): passaggio al mangime per ovaiole con calcio.

## Scarti dell'orto: sì e no
Concessi con moderazione (max ~10% della dieta): foglie verdi, zucchine, cocomero, scarti di insalata, erba. Da evitare: avocado, patate verdi e germogli (solanina), foglie di pomodoro/melanzana, cipolla e aglio in quantità, cibi salati, zuccherati, ammuffiti o avariati, cioccolato. Mai pane in eccesso.

## Accorgimenti per il clima costiero
Con il caldo le galline mangiano meno e bevono molto: garantisci acqua fresca e all'ombra, eventualmente più punti d'acqua. Conserva il mangime in contenitori stagni perché l'umidità costiera lo fa ammuffire facilmente (rischio micotossine).

## Errori comuni
- Troppe granaglie/mais: ingrassano le galline e diluiscono proteine e calcio, riducendo la deposizione.
- Calcio insufficiente: gusci sottili o molli.
- Mangiatoia a terra: spreco e attrazione di topi (vedi [[Predatori_Sicurezza]]).
- Acqua sporca o scarsa: cala subito la deposizione.

## Segnali da tenere d'occhio
Gusci molli o deformi (calcio/temperatura), galline troppo grasse (eccesso di granaglie), calo dei consumi d'acqua in estate (rischio colpo di calore), mangime umido o ammuffito da scartare.

## Diario di campo collegato
```dataview
TABLE file.name AS "Nota", meteo AS "Meteo"
FROM "agricoltura/40_Diario"
WHERE contains(file.outlinks, this.file.link)
SORT file.name DESC
LIMIT 10
```

## Riferimenti
- [[_MOC_Pollicoltura]]
- [[Deposizione_Uova]]
- [[Compostaggio]]

#pollicoltura #gestione
