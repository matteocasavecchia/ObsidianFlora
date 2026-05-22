---
tipo: scheda_formaggio
nome_prodotto: <% tp.file.title %>
tipo_prodotto: 
latte: 
coagulazione: 
pasta: 
stagionatura: 
resa_pct: 
temperatura_coagulo_c: 
difficolta: 2
tempo_lavorazione: 
tags:
  - caseificazione
  - formaggio
---

# 🧀 <% tp.file.title %>

> Tipo: `=this.tipo_prodotto` · Latte: `=this.latte` · Stagionatura: `=this.stagionatura` · Difficoltà: `=this.difficolta`/5

## Descrizione
_(che prodotto è, profilo gusto/consistenza, latte di partenza ideale)_

## Ingredienti
- Latte: `=this.latte`
- Caglio: _(tipo e dose)_
- Fermenti / colture: _(se previsti)_
- Sale: _(quantità, modalità)_
- Altro: _(eventuali aromatizzazioni)_

## Attrezzatura
- _(pentola, termometro, fuscelle/stampi, telo, ecc.)_

## Procedimento
1. Preparazione e trattamento del latte: _(temperatura `=this.temperatura_coagulo_c` °C)_
2. Coagulazione: `=this.coagulazione`
3. Rottura della cagliata: _(dimensione, tempi)_
4. Estrazione e messa in forma: _(pasta `=this.pasta`)_
5. Salatura: _(a secco / in salamoia)_
6. Stagionatura: `=this.stagionatura`

## Resa e conservazione
- Resa indicativa: `=this.resa_pct`% (litri latte → kg prodotto)
- Conservazione: _(frigo, cantina, durata)_

## Note per il clima costiero
_(gestione di umidità e temperatura della cantina/stagionatura sulla costa)_

## Difetti possibili
- _(vedi [[Difetti_Formaggio]])_

## Note personali
- 

## Riferimenti
- [[_MOC_Caseificazione]]
- [[_MOC_Allevamento_Latte]]

#caseificazione #formaggio
