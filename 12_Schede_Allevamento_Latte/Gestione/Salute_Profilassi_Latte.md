---
tipo: gestione_allevamento
titolo: Salute e profilassi
area: salute
difficolta: 3
frequenza: continua + controlli periodici
stagione: tutto l'anno
materiali: prodotti per zoccoli, antiparassitari su prescrizione, disinfettanti
strumenti: forbici/coltello per pareggio unghioni, termometro, registro trattamenti
tags:
  - allevamento_latte
  - gestione
---

# 🛠️ Salute e profilassi

> Area: salute · Difficoltà: 3/5 · Frequenza: continua + controlli periodici

## A cosa serve
Prevenire vale più che curare: un piano sanitario di base e l'osservazione quotidiana mantengono il gregge sano, proteggono la produzione di latte e tutelano la sicurezza del prodotto. Molti interventi vanno concordati con il veterinario.

## Quando farlo
- Stagione / periodo: osservazione tutto l'anno; controlli mirati a primavera (ripresa parassiti) e in autunno.
- Frequenza: controllo quotidiano del gregge, pareggio degli unghioni periodico, trattamenti e profilassi secondo piano veterinario.

## Principali problemi e prevenzione
- Mastiti: la patologia più costosa in un allevamento da latte. Prevenzione con igiene di mungitura, pre/post dipping e controllo dei primi getti (vedi [[Mungitura_Igiene_Latte]]).
- Parassiti gastrointestinali: tipici da pascolo; si controllano con pascolo turnato, non sovraccarico e trattamenti mirati (meglio su esame delle feci) concordati col veterinario.
- Parassiti esterni e zoppie: pidocchi, rogna, mal del piede; pareggio regolare degli unghioni e lettiera asciutta.
- Malattie soggette a piano: in Italia esistono piani di sorveglianza/eradicazione (es. brucellosi negli ovicaprini) gestiti dalla ASL: rientrano negli obblighi sanitari dell'allevamento (vedi [[Anagrafe_Normativa]]).

## Materiali e strumenti
- Materiali: prodotti per la cura degli zoccoli, antiparassitari e farmaci solo su prescrizione, disinfettanti.
- Strumenti: forbici/coltello da pareggio, termometro, eventuale gabbia di contenimento, registro dei trattamenti.

## Registro dei trattamenti e tempi di sospensione
Annota ogni farmaco somministrato: prodotto, animale, data, dose e soprattutto il tempo di sospensione del latte (e delle carni). È un obbligo di legge e una garanzia che nel latte venduto non finiscano residui (vedi [[Anagrafe_Normativa]] e [[Registro_Parti_Sanitario]]).

## Accorgimenti per il clima costiero
L'umidità costiera favorisce zoppie/mal del piede e problemi respiratori: priorità a lettiera asciutta e buona ventilazione. Caldo estivo: rischio di stress da calore (ombra, acqua, ventilazione), in particolare per le razze meno rustiche come la Saanen.

## Errori comuni
- Trattamenti antiparassitari "a calendario" senza necessità: favoriscono la resistenza dei parassiti.
- Ignorare il tempo di sospensione del latte dopo un farmaco.
- Quarantena saltata per i nuovi capi introdotti: rischio di portare malattie nel gruppo.
- Non tenere il registro dei trattamenti.

## Segnali da tenere d'occhio
Inappetenza, isolamento dal gruppo, zoppie, tosse o scolo nasale, dimagrimento, pelo arruffato, mucose pallide (parassiti), mammella anomala. Al dubbio, contatta il veterinario.

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
- [[Mungitura_Igiene_Latte]]
- [[Anagrafe_Normativa]]
- [[Ricovero_Recinzioni]]

#allevamento_latte #gestione
