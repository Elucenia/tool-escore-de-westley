<!-- ELUCENIA technical documentation · escore-de-westley · en · no clinical/professional/rights approval -->

# Westley score (croup)

[conditions, sources and permissions](https://elucenia.org/en/tools/escore-de-westley)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Level of consciousness

`cons`

- `0` — Normal (including during sleep)
- `5` — Disoriented

### Cyanosis

`cian`

- `0` — Absent
- `4` — With agitation
- `5` — At rest

### Stridor

`estr`

- `0` — Absent
- `1` — With agitation
- `2` — At rest

### Air entry

`ar`

- `0` — Normal
- `1` — Reduced
- `2` — Markedly reduced

### Retractions

`ret`

- `0` — Absent
- `1` — Mild
- `2` — Moderate
- `3` — Severe

## Method edition

Westley 1978: 5 factors, 0–17; croup

## Documented formula

Sum of 5 items: consciousness (0 or 5), cyanosis (0, 4 or 5), stridor (0 to 2), air entry (0 to 2) and retractions (0 to 3). Total 0 to 17.

## Limits and population

The Westley 1978 publication assessed 20 children aged 4 months to 5 years, hospitalized for acute croup with persistent stridor at rest, in an intervention trial. That range describes the original cohort and does not by itself determine universal limits for use of the score. The adopted scoring table and severity classification require specific checking.

## References

- [Westley CR, Cotton EK, Brooks JG. Nebulized racemic epinephrine by IPPB for the treatment of croup: a double-blind study. Am J Dis Child, 1978.](https://doi.org/10.1001/archpedi.1978.02120300044008)

- [Bjornson CL, Johnson DW. Croup in children. CMAJ, 2013.](https://doi.org/10.1503/cmaj.121645)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Mild croup (≤ 2)

Oral dexamethasone 0,15 to 0,6 mg/kg as a single dose; discharge with instructions.


### 2

Mild croup (≤ 2)

Oral dexamethasone 0,15 to 0,6 mg/kg as a single dose; discharge with instructions.


### 3

Moderate croup (3 to 5)

Dexamethasone; consider nebulized epinephrine if stridor at rest and observe for 2 to 4 hours after epinephrine.


### 4

Severe croup (6 to 11)

Nebulized epinephrine + dexamethasone, oxygen if needed, and prolonged observation or hospitalization.


### 5

Impending respiratory failure (≥ 12)

Nebulized epinephrine, oxygen, and activation of the airway team and pediatric ICU.

