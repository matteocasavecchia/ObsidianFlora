---
tipo: gestione_allevamento
titolo: Riproduzione e lattazione
area: riproduzione
difficolta: 3
frequenza: stagionale
stagione: monta in autunno, parti a fine inverno
materiali: registro parti, eventuale colostro di scorta
strumenti: box parto, lampada riscaldante per i piccoli, bilancia
tags:
  - allevamento_latte
  - gestione
---

# 🛠️ Riproduzione e lattazione

> Area: riproduzione · Difficoltà: 3/5 · Frequenza: stagionale

## A cosa serve
Il latte è conseguenza del parto: gestire bene monta, gravidanza, parto e asciutta significa programmare la produzione lungo l'anno e mantenere sane le femmine. Per la piccola vendita, scaglionare i parti aiuta ad avere latte in più periodi.

## Quando farlo
- Stagione / periodo: nei piccoli ruminanti la riproduzione è in genere stagionale, con calori in autunno (giornate calanti) e parti a fine inverno-primavera. Alcune razze (Sarda, Comisana, Massese) si prestano alla destagionalizzazione.
- Frequenza: un ciclo riproduttivo all'anno per capo, con eventuale scaglionamento del gruppo.

## Procedimento
1. Monta: introduci il maschio (o programma la fecondazione) quando le femmine sono in buona condizione corporea; un maschio per il gruppo di femmine.
2. Gravidanza: capre e pecore ~5 mesi (~150 giorni); asina ~12 mesi. Ultime settimane: aumenta gradualmente la razione (vedi [[Alimentazione_Pascolo]]).
3. Asciutta: sospendi la mungitura ~6-8 settimane prima del parto per far rigenerare la mammella e preparare la lattazione successiva.
4. Parto: predisponi un box pulito e asciutto; assisti solo se necessario.
5. Colostro: i piccoli devono assumerlo nelle prime ore di vita (immunità passiva fondamentale).
6. Lattazione: la produzione cresce nelle prime settimane, raggiunge il picco e poi cala fino all'asciutta.

## Materiali e strumenti
- Materiali: registro dei parti e degli accoppiamenti, eventuale colostro di scorta (congelato).
- Strumenti: box parto, lampada riscaldante per i nati nelle giornate fredde, bilancia per pesare i piccoli.

## Gestione dei piccoli
Decidi la linea di allevamento: allattamento naturale (i piccoli con la madre, mungitura parziale), allattamento artificiale (latte ricostituito, più latte disponibile per la vendita) o misto. Lo svezzamento avviene in genere a 6-8 settimane. Annota nascite, sesso e destinazione nel registro (vedi [[Registro_Parti_Sanitario]] quando disponibile).

## Caso asina
Nell'asina la lattazione richiede la presenza del puledro per stimolare la montata lattea: si munge separando il puledro per poche ore e poi riunendoli. Gestazione molto lunga (~12 mesi) e un solo puledro per parto (vedi [[Asina_dell_Amiata|Asina dell'Amiata]]).

## Accorgimenti per il clima costiero
Con parti a fine inverno-inizio primavera, in costa il clima mite è un vantaggio; cura comunque un box asciutto e riparato dai venti. Programma le monte tenendo conto del caldo estivo, che può ridurre fertilità e appetito.

## Errori comuni
- Femmine troppo grasse o troppo magre alla monta: cala la fertilità.
- Saltare l'asciutta: mammella affaticata e lattazione successiva più scarsa.
- Colostro tardivo o insufficiente ai nuovi nati: piccoli più deboli e malaticci.

## Segnali da tenere d'occhio
Calori (irrequietezza, code in movimento, comportamento di monta), avvicinarsi del parto (mammella che si riempie, rilassamento dei legamenti), vitalità dei piccoli e assunzione del colostro.

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
- [[Alimentazione_Pascolo]]
- [[Salute_Profilassi_Latte]]

#allevamento_latte #gestione
