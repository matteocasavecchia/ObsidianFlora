---
tipo: gestione_allevamento
titolo: Ricovero e recinzioni
area: strutture
difficolta: 2
frequenza: una tantum + manutenzione
stagione: tutto l'anno
materiali: pali, rete elettrificata o rete fissa, lettiera (paglia), materiali per ricovero
strumenti: attrezzi da recinzione, elettrificatore, attrezzi di pulizia
tags:
  - allevamento_latte
  - gestione
---

# 🛠️ Ricovero e recinzioni

> Area: strutture · Difficoltà: 2/5 · Frequenza: una tantum + manutenzione

## A cosa serve
Un buon ricovero e una recinzione efficace garantiscono benessere, sicurezza dai predatori e dalle fughe, e una gestione comoda di mungitura e parti. Capre e asini in particolare mettono alla prova qualsiasi recinzione.

## Quando farlo
- Stagione / periodo: realizzazione una tantum, con manutenzione continua; controlli più frequenti dopo maltempo e venti forti.
- Frequenza: ispezione regolare di recinti e ricovero; pulizia della lettiera secondo necessità.

## Procedimento
1. Ricovero: locale o tettoia asciutta, ben ventilata ma riparata dai venti dominanti, con lettiera di paglia mantenuta asciutta. Prevedi ~1,5-2 m²/capo per ovicaprini; molto più spazio per l'asina.
2. Zona mungitura: angolo o sala dedicata, pulibile, con punto di contenimento (rastrelliera/posta) per mungere comodi.
3. Recinzione: rete a maglie strette o rete elettrificata; per le capre serve altezza adeguata e tensione, perché saltano e si arrampicano.
4. Acqua e ombra: punti d'acqua puliti e zone ombreggiate in ogni paddock.
5. Suddivisione in parcelle per il pascolo turnato (vedi [[Alimentazione_Pascolo]]).

## Materiali e strumenti
- Materiali: pali, rete fissa o elettrificata, isolatori, lettiera (paglia), materiali per tettoia/ricovero.
- Strumenti: attrezzi da recinzione, elettrificatore (a rete o fotovoltaico), attrezzi per pulizia e rimozione lettiera.

## Predatori e sicurezza
In molte aree il rischio principale è il lupo o il cane vagante, oltre a volpi per i piccoli. Difese: recinzioni robuste e ben tenute, ricovero notturno chiuso, eventuale cane da guardiania per il gregge. Controlla sempre chiusure e tenuta dopo il maltempo.

## Accorgimenti per il clima costiero
Privilegia ventilazione e ombra (estati calde-umide) ma proteggi dai venti marini e dalla Bora/Tramontana. Lettiera sempre asciutta: l'umidità costiera favorisce problemi a piedi e vie respiratorie. Usa materiali resistenti alla salsedine (acciaio zincato, legno trattato).

## Errori comuni
- Recinzione troppo bassa o poco tesa: le capre la superano.
- Ricovero umido o poco ventilato: zoppie, parassiti, problemi respiratori.
- Lettiera sporca lasciata accumulare: ammoniaca e patogeni.
- Nessuna zona d'ombra nei paddock estivi.

## Segnali da tenere d'occhio
Punti di fuga o varchi nella recinzione, lettiera bagnata o maleodorante, segni di tentativi di predazione, animali che cercano riparo dal vento o dal sole.

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
