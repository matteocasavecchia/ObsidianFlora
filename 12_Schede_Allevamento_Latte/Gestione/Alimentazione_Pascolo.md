---
tipo: gestione_allevamento
titolo: Alimentazione e pascolo
area: alimentazione
difficolta: 3
frequenza: quotidiana
stagione: tutto l'anno
materiali: pascolo, fieno, concentrati, sali minerali, acqua pulita
strumenti: rastrelliera/mangiatoia, abbeveratoio, recinto mobile per pascolo turnato
tags:
  - allevamento_latte
  - gestione
---

# 🛠️ Alimentazione e pascolo

> Area: alimentazione · Difficoltà: 3/5 · Frequenza: quotidiana

## A cosa serve
L'alimentazione è il fattore che più incide su quantità e qualità del latte, sulla salute e sulla fertilità. Per capre e pecore da latte l'obiettivo è una razione equilibrata in fibra, energia e proteine, basata sul pascolo e integrata in funzione della fase produttiva. Una corretta alimentazione si riflette direttamente sulla resa casearia (vedi [[_MOC_Caseificazione]]).

## Quando farlo
- Stagione / periodo: tutto l'anno; il fabbisogno è massimo nei due mesi attorno al parto e nel picco di lattazione.
- Frequenza: pascolo quotidiano, controllo di acqua e foraggio ogni giorno, concentrati in 1-2 razioni.

## Cosa dare
- Pascolo: base della dieta nella bella stagione; copre buona parte del fabbisogno se l'erba è abbondante e di qualità.
- Fieno: sempre a disposizione, soprattutto quando il pascolo scarseggia; fondamentale la fibra per la funzione ruminale.
- Concentrati (cereali, fioccati, mangime composto): integrazione proporzionata alla produzione di latte, da aumentare gradualmente per evitare disturbi ruminali.
- Sali minerali e oligoelementi: a disposizione in blocco o granulare; il calcio è cruciale per la lattazione.
- Acqua: pulita e sempre disponibile; una capra/pecora in lattazione beve molto, ancora di più al caldo.

## Materiali e strumenti
- Materiali: foraggio (pascolo + fieno), concentrati, sali minerali, acqua.
- Strumenti: rastrelliera per il fieno (riduce gli sprechi e lo calpestio), mangiatoia per i concentrati, abbeveratoio pulito, eventuale recinto mobile per il pascolo turnato.

## Gestione del pascolo
- Pascolo turnato/a rotazione: si suddivide l'area in parcelle e si spostano gli animali, lasciando ricrescere l'erba. Migliora la resa del prato e riduce drasticamente la carica parassitaria.
- Carico animale: adeguarlo alla disponibilità del prato per non sovrapascolare.
- Specie a confronto: la capra è brucatrice (predilige arbusti, foglie, essenze alte e amare), la pecora è pascolatrice (erba bassa e fitta); insieme sfruttano meglio lo stesso terreno. L'asina è frugale e tende a ingrassare, quindi va su pascoli poveri con pochi concentrati.

## Accorgimenti per il clima costiero
In estate l'erba mediterranea ingiallisce e perde valore: prevedi scorte di fieno e ombra durante il pascolo nelle ore calde. Conserva fieno e concentrati in luogo asciutto, perché l'umidità marina favorisce muffe e micotossine. Più punti d'acqua fresca nei mesi caldi.

## Errori comuni
- Troppi concentrati di colpo: acidosi ruminale e calo del grasso del latte.
- Poca fibra (solo erba giovane o solo mangime): feci molli, disturbi digestivi.
- Cambi di dieta bruschi: vanno fatti sempre in modo graduale (7-10 giorni).
- Pascolo continuo sullo stesso terreno: esplosione dei parassiti gastrointestinali (vedi [[Salute_Profilassi_Latte]]).

## Segnali da tenere d'occhio
Condizione corporea (né troppo magre né troppo grasse), consistenza delle feci, andamento della produzione di latte, consumi d'acqua in estate, presenza di erbe tossiche al pascolo.

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
- [[Salute_Profilassi_Latte]]
- [[Mungitura_Igiene_Latte]]
- [[Compostaggio]]

#allevamento_latte #gestione
