---
tipo: gestione_allevamento
titolo: Anagrafe e normativa
area: normativa
difficolta: 4
frequenza: adempimenti periodici
stagione: tutto l'anno
materiali: marche auricolari, registro di stalla, modello 4, documentazione autocontrollo
strumenti: accesso BDN/portale anagrafe, registri, contatto ASL e veterinario
tags:
  - allevamento_latte
  - gestione
---

# 🛠️ Anagrafe e normativa

> Area: normativa · Difficoltà: 4/5 · Frequenza: adempimenti periodici

> ⚠️ Nota: la normativa zootecnica e igienico-sanitaria è nazionale e regionale e cambia nel tempo. Questa scheda è un quadro orientativo: verifica sempre gli obblighi aggiornati con la tua ASL e con la Regione (Liguria) prima di partire, soprattutto se vendi latte o formaggi.

## A cosa serve
Anche il piccolo allevamento è soggetto a registrazione e a regole di tracciabilità sanitaria. Mettere in ordine anagrafe e adempimenti è il presupposto per allevare in regola e, soprattutto, per poter vendere latte e formaggi.

## Avvio dell'allevamento (anagrafe zootecnica)
1. Codice aziendale (codice di stalla): si richiede alla ASL competente; identifica l'allevamento nella Banca Dati Nazionale (BDN) dell'anagrafe zootecnica.
2. Registrazione in BDN: l'allevamento e i capi vengono registrati; per gli ovicaprini c'è obbligo di identificazione.
3. Identificazione ovicaprini: ogni capo va identificato con marche auricolari (di norma una con identificazione elettronica), entro i termini di legge dalla nascita.
4. Registro di stalla / registro carico-scarico: vanno annotati nascite, morti, acquisti, vendite e movimentazioni.
5. Movimentazioni: gli spostamenti di animali tra aziende richiedono il documento di trasporto (Modello 4) e la registrazione in BDN.

## Caso asina ed equidi
Gli equidi (compresa l'asina) seguono un'anagrafe dedicata, distinta da quella degli ovicaprini: identificazione con microchip e passaporto/documento di identificazione, registrazione nell'anagrafe degli equidi. Verifica gli adempimenti specifici con la ASL.

## Profilassi obbligatorie
L'allevamento rientra nei piani sanitari gestiti dalla ASL (per gli ovicaprini, ad esempio, la sorveglianza della brucellosi). Tieni i rapporti con il veterinario di riferimento e conserva la documentazione sanitaria (vedi [[Salute_Profilassi_Latte]]).

## Vendita di latte e formaggi
- Registrazione sanitaria: per trasformare e vendere serve in genere registrare l'attività presso la ASL (notifica/registrazione ai sensi del "pacchetto igiene"); per certe forme di vendita può servire un riconoscimento dedicato.
- Autocontrollo (HACCP): predisponi un piano di autocontrollo proporzionato alla dimensione, eventualmente basato su un manuale di corretta prassi igienica; molte piccole realtà adottano procedure semplificate.
- Tracciabilità e lotti: registra latte trasformato, lotti di prodotto e destinazioni (vedi [[Registro_Produzione_Casearia]] nella sezione caseificazione).
- Tempi di sospensione: il latte di animali trattati con farmaci non può essere venduto durante il periodo di sospensione (vedi [[Salute_Profilassi_Latte]]).
- Latte crudo ed etichettatura: la vendita di latte crudo e l'etichettatura dei prodotti hanno regole specifiche; informati prima.
- Vendita diretta e piccole quantità: spesso esistono regimi semplificati per la cessione diretta di piccoli quantitativi al consumatore finale o al dettaglio locale, con limiti e condizioni definiti a livello regionale.

## Materiali e strumenti
- Materiali: marche auricolari, registro di stalla, Modello 4, documentazione di autocontrollo e registri di trasformazione.
- Strumenti: accesso al portale BDN/anagrafe (spesso tramite veterinario o associazione), registri cartacei/digitali, contatto con ASL e veterinario.

## Errori comuni
- Iniziare ad allevare senza codice di stalla e registrazione.
- Registro di stalla non aggiornato o movimentazioni non documentate.
- Vendere latte/formaggi senza la registrazione sanitaria e senza autocontrollo.
- Trascurare etichettatura e tracciabilità dei lotti.

## Da verificare con ASL / Regione
- Termini esatti per identificazione e registrazione dei capi.
- Adempimenti per la trasformazione e la vendita diretta nella tua zona.
- Eventuali requisiti del locale di caseificazione.

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
- [[Mungitura_Igiene_Latte]]

#allevamento_latte #gestione
