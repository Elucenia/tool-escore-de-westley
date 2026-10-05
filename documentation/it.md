<!-- ELUCENIA technical documentation · escore-de-westley · it · no clinical/professional/rights approval -->

# Punteggio di Westley (croup)

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/escore-de-westley)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Livello di coscienza

`cons`

- `0` — Normale (anche durante il sonno)
- `5` — Disorientato

### Cianosi

`cian`

- `0` — Assente
- `4` — Con agitazione
- `5` — A riposo

### Stridore

`estr`

- `0` — Assente
- `1` — Con agitazione
- `2` — A riposo

### Ingresso d’aria

`ar`

- `0` — Normale
- `1` — Ridotta
- `2` — Molto ridotta

### Retrazioni

`ret`

- `0` — Assenti
- `1` — Lievi
- `2` — Moderate
- `3` — Gravi

## Edizione del metodo

Westley 1978: 5 fattori, 0–17; croup

## Formula documentata

Somma di 5 item: coscienza (0 o 5), cianosi (0, 4 o 5), stridore (da 0 a 2), ingresso d’aria (da 0 a 2), rientramenti (da 0 a 3). Totale da 0 a 17.

## Limiti e popolazione

La pubblicazione Westley 1978 ha valutato 20 bambini da 4 mesi a 5 anni, ricoverati per croup acuto con stridore persistente a riposo, in uno studio di intervento. Questa fascia descrive la coorte originale e non determina da sola i limiti universali di uso del punteggio. La tabella di punteggio e la classificazione di gravità adottate richiedono una verifica specifica.

## Riferimenti

- [Westley CR, Cotton EK, Brooks JG. Nebulized racemic epinephrine by IPPB for the treatment of croup: a double-blind study. Am J Dis Child, 1978.](https://doi.org/10.1001/archpedi.1978.02120300044008)

- [Bjornson CL, Johnson DW. Croup in children. CMAJ, 2013.](https://doi.org/10.1503/cmaj.121645)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
