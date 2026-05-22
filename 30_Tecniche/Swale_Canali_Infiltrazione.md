---
tipo: tecnica
titolo: Swale (canali di infiltrazione)
area: acqua
difficolta: 3
tempo_richiesto: "Progettazione: mezza giornata; scavo: 1-2 giornate secondo lunghezza"
stagione: autunno-inverno (realizzazione), tutto l'anno (funzione)
materiali:
  - Materiale organico per riempire/pacciamare l'argine (cippato, sfalci, ramaglie)
  - Piante da mettere a dimora sull'argine
  - Eventuale telo o pietrame per troppopieno
strumenti:
  - Livella ad acqua o livello laser (per tracciare la curva di livello)
  - Vanga, zappa, eventuale piccolo escavatore
tags:
  - tecnica
  - acqua
  - irrigazione
  - permacultura
---

# 💧 Swale (canali di infiltrazione)

> Area: `=this.area` · Difficoltà: `=this.difficolta`/5 · Tempo: `=this.tempo_richiesto`

## A cosa serve
Lo swale è un fosso poco profondo scavato lungo la curva di livello (quindi perfettamente orizzontale), con il terreno di risulta accumulato a valle a formare un argine. Non è irrigazione attiva ma raccolta e infiltrazione passiva dell'acqua piovana: la pioggia che scorrerebbe via viene intercettata, trattenuta nel fosso e fatta infiltrare lentamente nel terreno, ricaricando la falda superficiale e idratando il pendio a valle. Sull'argine si piantano alberi e siepi, che attingono all'acqua immagazzinata. È una tecnica di permacultura per ridurre la dipendenza dall'irrigazione in climi con piogge concentrate ed estati siccitose, come la costa mediterranea.

## Quando farla
- Realizzazione: autunno-inverno, terreno lavorabile e in vista delle piogge stagionali
- Funzione: tutto l'anno, in modo passivo, a ogni pioggia significativa
- Messa a dimora sull'argine: nella stagione di impianto adatta alle specie scelte
- Manutenzione: controllo del troppopieno dopo eventi intensi, ripristino dell'argine se eroso

## Materiali e strumenti
- **Livella ad acqua o livello laser**: fondamentale per tracciare la curva di livello esatta; se lo swale non è orizzontale, l'acqua scorre a un'estremità ed erode
- **Vanga, zappa** o piccolo escavatore secondo la scala
- **Materiale organico** (cippato, sfalci, ramaglie) per pacciamare fosso e argine e aumentare la ritenzione
- **Piante per l'argine**: alberi da frutto, siepi, fissatori di azoto
- **Troppopieno**: punto rinforzato (pietrame o telo) dove l'acqua in eccesso esce in modo controllato

## Procedimento
1. **Tracciare la curva di livello**: con livella ad acqua o laser, segnare una linea orizzontale lungo il pendio; questo è il tracciato dello swale
2. **Scavo del fosso**: aprire un fosso largo e poco profondo lungo la linea, accumulando la terra a valle
3. **Formare l'argine**: compattare il cumulo di terra a valle, sagomandolo per ospitare le piante
4. **Troppopieno**: predisporre un punto di sfioro rinforzato a una quota leggermente inferiore, per scaricare l'acqua in eccesso senza erodere
5. **Pacciamatura**: riempire il fosso con materiale organico, che trattiene umidità e si trasforma in humus
6. **Messa a dimora**: piantare alberi e siepi sull'argine, dove l'acqua infiltrata resta disponibile più a lungo
7. **Verifica dopo la prima pioggia**: controllare che l'acqua si distribuisca uniformemente e che il troppopieno funzioni

## Accorgimenti per il clima costiero
Il regime mediterraneo (piogge intense e concentrate in autunno-inverno, estati lunghe e secche) è esattamente lo scenario in cui lo swale dà di più: cattura le piogge violente che altrimenti ruscellerebbero verso il mare e le immagazzina per la stagione secca. Su terreni sabbiosi costieri l'infiltrazione è rapida: lo swale ricarica bene la falda ma trattiene poco in superficie, quindi va abbinato a molta pacciamatura e materiale organico. In presenza di falda salmastra poco profonda, attenzione a non favorire la risalita salina: meglio swale poco profondi e ben drenanti. Lo swale combinato con un frangivento sull'argine protegge anche dalla salsedine.

## Errori comuni
- Fosso non in piano: l'acqua scorre a un'estremità ed erode invece di infiltrarsi
- Nessun troppopieno: in caso di pioggia intensa l'argine cede e si rompe
- Argine non compattato o senza piante: erosione e dilavamento
- Swale troppo profondo su terreno argilloso: ristagno e asfissia radicale
- Realizzarlo in estate: terreno duro e nessuna pioggia per testarlo prima della stagione utile

## Piante / situazioni in cui si applica
- Frutteto e agrumeto su terreno in leggera pendenza
- Siepi frangivento e specie da legno sull'argine
- Recupero di terreni soggetti a ruscellamento e siccità estiva
- Sistemi di permacultura e agricoltura rigenerativa
- Da abbinare a [[Irrigazione_a_Goccia]] o [[Irrigazione_a_Conca_e_Solco]] nei primi anni di impianto

### Schede pianta collegate
```dataview
LIST
FROM "agricoltura/10_Schede_Piante"
WHERE contains(tecniche_irrigazione, this.file.link)
SORT file.name ASC
```

## Diario di campo collegato
```dataview
TABLE file.name AS "Nota", meteo AS "Meteo"
FROM "agricoltura/40_Diario"
WHERE contains(interventi, this.file.link) OR contains(file.outlinks, this.file.link)
SORT file.name DESC
LIMIT 10
```

## Riferimenti
- [[Irrigazione_Panoramica]]
- [[_MOC_Tecniche]]
- [[Pacciamatura]]
- [[Gestione_Salsedine_Vento]]

#tecnica #acqua #irrigazione #permacultura
