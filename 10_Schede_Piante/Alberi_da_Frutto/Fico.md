---
tipo: scheda_pianta
categoria: albero_da_frutto
nome_comune: Fico
nome_scientifico: Ficus carica
famiglia: Moraceae
periodo_raccolta: "Fioroni: Giugno; Forniti: Agosto-Settembre"
periodo_potatura: "Febbraio-Marzo (leggera)"
forma_allevamento: "Libera o vaso aperto"
portainnesto_consigliato: "Da talea autoradicata o propaggine (no innesto)"
esposizione: sole pieno
resistenza_salsedine: alta
resistenza_freddo: "-10°C pianta; rami giovani danni a -5°C"
entrata_in_produzione_anni: 2
autofertile: true
impollinatori_richiesti: "Nessuno (varietà comuni partenocarpiche)"
sesto_impianto_m: "5 × 5"
tags:
  - albero
  - moraceae
---

# 🟢 Fico

> Famiglia: `=this.famiglia` · Raccolta: `=this.periodo_raccolta` · Potatura: `=this.periodo_potatura`

## Caratteristiche
Pianta tipica mediterranea, generosa e poco esigente. Una caratteristica unica: molte varietà producono **due raccolti l'anno**: **fioroni** (a giugno, dai fiori dell'anno precedente che hanno svernato) e **fichi veri** o **forniti** (agosto-settembre, dai fiori dell'anno corrente). Varietà classiche: **Dottato** (verde-giallo, polpa rossa, una delle migliori da seccare), **Brogiotto bianco**, **Brogiotto nero**, **Verdino**, **Fico Bianco del Cilento** DOP, **Reggiano** (rosso intenso), **Fico fragola di Albano**. Il fico è praticamente partenocarpico (le varietà comuni in coltura producono frutti senza impollinazione); le varietà "caprifico" che richiedono impollinazione dalla vespa Blastophaga sono molto più rare.

## Impianto
- Esposizione: sole pieno
- Sesto: 5 × 5 m. In angoli protetti di muretti o muri esposti sud si comporta molto bene
- Propagazione: per **talea** (semplice, autunno-inverno) o **propaggine**. Non per innesto
- Periodo: novembre-marzo per talee/piante a radice nuda; tutto l'anno se in vaso
- Buca: 50 × 50 × 50 cm
- Ammendanti: compost. Il fico non è esigente
- Apparato radicale superficiale e invasivo: non piantare troppo vicino a case, tubazioni, pozzi neri (le radici possono rovinare)

## Cura annuale
- Concimazione: poca o nessuna se in pieno campo. Compost a fine inverno per giovani esemplari
- Irrigazione: di soccorso in estate per giovani esemplari. Adulto, tollera bene siccità
- Pacciamatura organica utile
- Eliminazione polloni alla base (il fico ricaccia molto da radice)

## Potatura
- Periodo: febbraio-marzo, prima del germoglio. **Leggera**: il fico produce su rami dell'anno scorso (per i fioroni) e rami dell'anno (per i forniti), quindi tagli eccessivi riducono il raccolto
- Eliminare succhioni verticali, rami secchi, rami che si incrociano
- Mantenere chioma aperta a vaso (3-4 branche principali)
- Le ferite di taglio essudano lattice biancastro (irritante per la pelle): proteggere mani

## Impollinazione e produzione
- Autofertile (partenocarpico per le varietà comuni)
- Fioritura "nascosta" all'interno del siconio (il "frutto" del fico è in realtà un'infiorescenza chiusa)
- Entrata in produzione: 2-3 anni (precoce)
- Produzione adulta: 50-150 kg per pianta

## Avversità tipiche
- **Cocciniglia del fico** (Ceroplastes rusci): scudetti bianchi o rossi sui rami. Olio bianco minerale in inverno, sapone molle
- **Mosca dei fichi** (Lonchaea aristella, Ceratitis capitata): larve nei frutti, fermentazione. Raccolta tempestiva, trappole proteiche, distruzione frutti caduti
- **Antracnosi del fico**: macchie scure sui frutti, soprattutto in autunno umido. Rame
- **Marciume agrobacterico**: tumori al colletto. Eliminare piante colpite
- **Tarlo** (rodilegno): larva nel legno
- **Uccelli**: ghiotti dei fichi maturi, reti se necessario

## Resistenza al contesto costiero
**Pianta nata per il Mediterraneo costiero**: tollera salsedine, vento, siccità, suoli poveri e calcarei. La costa centro-italiana è habitat ideale. Resistenza al freddo: la pianta sopporta -10°C (gli organi sotterranei anche di più, ricaccia da terra in caso di danni gravi), i rami giovani subiscono danni a -5°C prolungato. Pianta che si rinaturalizza facilmente, si trova selvatica lungo muretti e pendii.

## Raccolta e conservazione
- **Fioroni**: a giugno, frutti grossi, dolci, molto delicati. Conservazione minima, consumo immediato
- **Forniti**: agosto-settembre, frutti più piccoli ma più numerosi. Quando il frutto si china sul peduncolo, ha "lacrima" di nettare sul fondo, buccia screpolata e cedevole al tatto: è maturo
- Raccolta delicata, manipolare con cura
- Conservazione: 2-3 giorni in fresco. Per conservazione: **essiccazione** classica (al sole o essiccatore), poi sterilizzazione in forno. Marmellata. Sciroppo. Fichi sotto grappa o rum

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
- [[primavera]] · [[estate]] · [[autunno]]

#pianta #albero_da_frutto
