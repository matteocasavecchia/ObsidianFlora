---
tipo: scheda_pianta
categoria: albero_da_frutto
nome_comune: Albicocco
nome_scientifico: Prunus armeniaca
famiglia: Rosaceae
periodo_raccolta: "Giugno-Luglio"
periodo_potatura: "Estate post-raccolta (privilegiata); leggera in inverno"
forma_allevamento: "Vaso"
portainnesto_consigliato: "Mirabolano (rustico) o franco (da seme)"
esposizione: sole pieno (riparato da venti freddi tardivi)
resistenza_salsedine: media
resistenza_freddo: "-20°C pianta; fiori distrutti a -2°C"
entrata_in_produzione_anni: 3
autofertile: true
impollinatori_richiesti: "Nessuno (rare eccezioni)"
sesto_impianto_m: "4 × 5"
tecniche_irrigazione:
  - "[[Irrigazione_a_Goccia]]"
  - "[[Irrigazione_a_Conca_e_Solco]]"
  - "[[Subirrigazione]]"
tags:
  - albero
  - drupacee
  - rosaceae
---

# 🟠 Albicocco

> Famiglia: `=this.famiglia` · Raccolta: `=this.periodo_raccolta` · Potatura: `=this.periodo_potatura`

## Caratteristiche
Drupacea precoce, produce uno dei primi frutti dell'estate. Frutti tondi, gialli con sfumature rosse, polpa profumata. Varietà classiche italiane: **Reale d'Imola** (classica, frutto medio, ottima per fresco e marmellata), **Bella d'Imola**, **San Castrese** (campano, precoce, rosso), **Cafona** (vesuviano), **Tirynthos** (precoce, greco-italico), **Vitillo**, **Pellecchiella**. Pianta abbastanza esigente in cure ma generosa: una pianta adulta può produrre 60-100 kg.

## Impianto
- Esposizione: sole pieno; **importante riparare da venti freddi del nord** (fioriture precoci a marzo, sensibili a gelate tardive)
- Sesto: 4 × 5 m
- Portainnesto: mirabolano o franco
- Periodo: novembre-marzo a radice nuda
- Buca: 60 × 60 × 60 cm con buon drenaggio (l'albicocco teme i ristagni più del susino)
- Ammendanti: compost maturo, cornunghia

## Cura annuale
- Concimazione: ottobre-novembre, compost + cornunghia
- Irrigazione: regolare in formazione frutti (aprile-giugno). Sospendere a maturazione (1-2 settimane prima della raccolta) per concentrare sapore
- Pacciamatura organica
- Spollonatura del portainnesto
- **Diradamento frutti**: se carico (è frequente), diradare 1 frutto ogni 5-7 cm a nocciolo formato

## Potatura
- **Verde estiva post-raccolta** (luglio-agosto): è la potatura **principale** dell'albicocco. Si tagliano rami che hanno fruttificato, succhioni, rami in eccesso. Vantaggio rispetto a potatura invernale: le ferite cicatrizzano rapidamente, si riducono gommosi e cancri rameali
- Inverno: solo interventi leggeri di pulizia (rami secchi, rotti)
- Forma a vaso aperto, 3-4 branche principali
- L'albicocco fruttifica su rami misti, brindilli, mazzetti di maggio: mantenere varietà di rami giovani

## Impollinazione e produzione
- Praticamente tutte le varietà sono autofertili
- Fioritura: febbraio-marzo (precoce!): **principale rischio gelate tardive** sui fiori
- Entrata in produzione: 3-4 anni
- Produzione adulta: 60-100 kg per pianta
- **Alternanza di produzione** frequente: si attenua con potatura e diradamento

## Avversità tipiche
- **Monilia** (Monilinia laxa): la più seria, dissecca rami fioriferi a primavera ("disseccamento" dell'albicocco), marciumi sui frutti. Rame in poltiglia bordolese a fine inverno e dopo le piogge primaverili. Eliminare rami secchi e frutti mummificati
- **Corineo** (Stigmina carpophila): macchie circolari rossastre, fori sulle foglie, cancri sui rami. Rame autunnale e a fine inverno
- **Gommosi**: essudazione di gomma. Evitare tagli in periodo umido, drenaggio buono
- **Apoplessia**: morte improvvisa di una branca o tutta la pianta in piena estate. Causa principale stress estivo + agenti fungini su radici. Drenaggio, irrigazione regolare, pacciamatura
- **Afide farinoso del pesco**: anche sull'albicocco, foglie accartocciate. Sapone molle, predatori
- **Cocciniglia di San José**: scudetti rossastri sui rami. Olio bianco minerale in inverno

## Resistenza al contesto costiero
Salsedine tollerata mediamente. La pianta resiste benissimo al freddo invernale (-20°C), ma **i fiori precocissimi** (febbraio-marzo) sono distrutti a -2°C: per questo conviene piantare in zone protette o ritardare la fioritura con esposizione nord o pendio fresco. Sulla costa centro-italiana questo problema è meno acuto rispetto all'entroterra. Buon drenaggio essenziale.

## Raccolta e conservazione
- A piena maturazione, frutto profumato e leggermente cedevole al tatto. Si raccoglie in pianta gradualmente (i frutti maturano scalari)
- Forbice o stacco a mano. Albicocco molto delicato, manipolare con cura
- Conservazione: 3-5 giorni in fresco, 1-2 settimane in frigo (perde aroma)
- Trasformazione: marmellata (eccellente), sciroppo, essiccazione, sotto spirito, liquore al nocciolo (cura però: amaretti, ma anche tossico se eccessivo)

## Diario di campo collegato
```dataview
TABLE meteo AS "Meteo", interventi AS "Interventi"
FROM "agricoltura/40_Diario"
WHERE contains(piante, this.file.link) OR contains(file.outlinks, this.file.link)
SORT file.name DESC
LIMIT 10
```

## Note personali
- 

## Riferimenti
- [[_MOC_Piante]]
- Irrigazione: [[Irrigazione_Panoramica]] · [[Irrigazione_a_Goccia]] · [[Irrigazione_a_Conca_e_Solco]] · [[Subirrigazione]]
- [[primavera]] · [[estate]] · [[inverno]]

#pianta #albero_da_frutto #drupacee
