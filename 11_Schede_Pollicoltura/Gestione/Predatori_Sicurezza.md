---
tipo: gestione_pollaio
titolo: Predatori Sicurezza
area: sicurezza
difficolta: 3
frequenza: chiusura quotidiana + verifiche periodiche
stagione: tutto l'anno (pressione predatori maggiore in inverno e durante lo svezzamento dei loro piccoli)
materiali: rete elettrosaldata zincata a maglia fine, lamiera, eventuale recinto elettrificato
strumenti: pinze, vanga, avvitatore, sportello pop-hole (anche automatico)
tags:
  - pollicoltura
  - gestione
---

# 🛠️ Predatori Sicurezza

> Area: sicurezza · Difficoltà: 3/5 · Frequenza: chiusura quotidiana

## A cosa serve
Proteggere il gruppo dai predatori è essenziale: una sola incursione notturna può sterminare l'intero pollaio. La sicurezza si gioca su recinzione a prova di intrusione, chiusura serale puntuale e protezione dall'alto.

## Quando farlo
- Stagione / periodo: tutto l'anno; la pressione aumenta in inverno (cibo scarso) e quando i predatori svezzano i piccoli.
- Frequenza: chiusura ogni sera al tramonto, verifica periodica di rete e fessure.

## Predatori tipici (Liguria/costa)
- Volpe: scava sotto le recinzioni e attacca all'alba o al tramonto.
- Faina e donnola (mustelidi): passano da fori piccolissimi (faina ~5 cm, donnola anche meno) e fanno stragi notturne.
- Ratti: rubano mangime e uova, uccidono i pulcini.
- Rapaci (poiana, astore) e corvidi (cornacchie, gazze): attaccano dall'alto, soprattutto pulcini; i corvidi rubano le uova.
- Cani randagi e bisce (uova e pulcini).

## Materiali e strumenti
- Materiali: rete elettrosaldata zincata a maglia fine (la rete a maglia larga NON ferma i mustelidi), lamiera/copertura, eventuale recinto elettrificato contro la volpe.
- Strumenti: pinze, vanga per interrare la rete, avvitatore, sportello pop-hole richiudibile (anche con apertura/chiusura automatica a tempo o crepuscolare).

## Procedimento
1. Recinta con rete a maglia fine su tutti i lati, compreso un eventuale "tetto" di rete contro i rapaci.
2. Interra la rete 30-50 cm o piega il bordo a L verso l'esterno, contro gli animali che scavano.
3. Elimina ogni fessura nel ricovero: chiudi fori, fessure e giunture da cui possono entrare faine e donnole.
4. Installa una pop-hole solida e chiudila ogni sera (l'automatismo crepuscolare evita le dimenticanze).
5. Rialza il ricovero da terra e gestisci il mangime in tramogge chiuse per non attirare i ratti.

## Accorgimenti per il clima costiero
La ferramenta zincata resiste meglio alla salsedine; controlla comunque periodicamente la corrosione di rete e cerniere, perché un punto indebolito è una via d'ingresso.

## Errori comuni
- Affidarsi alla rete a maglia larga: inutile contro faine, donnole e ratti.
- Dimenticare la chiusura serale: la causa più frequente di stragi.
- Non interrare la rete: la volpe scava e passa sotto.
- Lasciare mangime a terra di notte: richiama roditori e, di conseguenza, i loro predatori.

## Segnali da tenere d'occhio
Buchi o scavi lungo il perimetro, penne sparse, galline agitate o che non vogliono rientrare, cali improvvisi di capi o di uova, escrementi di roditori vicino alla mangiatoia.

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
- [[Pollaio_Struttura]]

#pollicoltura #gestione
