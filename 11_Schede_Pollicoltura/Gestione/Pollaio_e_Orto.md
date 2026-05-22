---
tipo: gestione_pollaio
titolo: Pollaio e Orto
area: integrazione orto
difficolta: 2
frequenza: continua / stagionale
stagione: tutto l'anno
materiali: pollina e lettiera usata, scarti dell'orto, compost
strumenti: forca, carriola, composter
tags:
  - pollicoltura
  - gestione
  - suolo
---

# 🛠️ Pollaio e Orto

> Area: integrazione orto · Difficoltà: 2/5 · Frequenza: continua/stagionale

## A cosa serve
Il pollaio e l'orto si alimentano a vicenda: è il cuore di un piccolo sistema chiuso e biologico. Le galline trasformano scarti ed erbacce in uova e in concime, e l'orto restituisce loro cibo fresco. Questa scheda raccoglie i quattro principali punti di contatto.

## 1. Pollina → concime e compost
La pollina (deiezioni + lettiera usata) è un fertilizzante ricchissimo, soprattutto di azoto. Però è "calda": usata fresca brucia le radici e può veicolare patogeni. Va quindi sempre maturata.
- Non spargerla fresca sulle colture.
- Aggiungila al cumulo di [[Compostaggio|compost]] come materiale azotato (verde): attiva e scalda il cumulo. Bilancia con abbondante materiale bruno (paglia, foglie secche, cartone) per non farlo impuzzolentire.
- Dopo 4-6 mesi di compostaggio diventa un ammendante sicuro e prezioso.
- Distribuiscila matura in autunno o prima delle colture esigenti (vedi [[calendario_master]]).

## 2. Scarti dell'orto → mangime
Molti residui dell'orto integrano la dieta delle galline (vedi [[Alimentazione]] per i sì e i no): foglie esterne di insalata e cavoli, zucchine fuori misura, cocomero, sfalci d'erba non trattata, ortaggi non più presentabili. È un riciclo che riduce sprechi e costi del mangime, da tenere comunque entro ~10% della razione.

## 3. Galline come antiparassita e "diserbo"
Le galline razzolando mangiano larve, lumache, cavallette, semi di infestanti e scarificano il terreno. Usate con criterio (in recinti mobili o a rotazione) ripuliscono una parcella a fine coltura.
- Ottime su una parcella libera tra una coltura e l'altra: mangiano residui, parassiti svernanti e infestanti, lasciando terreno concimato.
- Da tenere fuori dalle parcelle coltivate: beccano germogli, ortaggi a foglia e fragole, e razzolando scoprono le radici.
- Un recinto mobile (chicken tractor) permette di sfruttarle dove serve senza danni.

## 4. Lettiera usata → pacciamatura e struttura
La lettiera di paglia/trucioli mista a pollina, una volta compostata, arricchisce e struttura il terreno. Compostata bene può andare anche come strato nutritivo sotto la [[Pacciamatura|pacciamatura]] di alberi e colture esigenti.

## Accorgimenti per il clima costiero
In estate il cumulo con pollina asciuga in fretta: bagnalo e tienilo coperto. L'autunno umido della costa è il momento migliore per compostare la pollina accumulata. Evita di spargere pollina fresca nei mesi caldi: l'odore e l'ammoniaca aumentano.

## Errori comuni
- Usare pollina fresca sulle piante: brucia le radici.
- Squilibrio nel compost: troppa pollina senza bruni fa puzzare e impaludare il cumulo.
- Lasciare le galline libere nell'orto coltivato: danni a germogli e ortaggi.
- Dare scarti vietati o ammuffiti (vedi [[Alimentazione]]).

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
- [[Compostaggio]] · [[Pacciamatura]] · [[Alimentazione]]

#pollicoltura #gestione #suolo
