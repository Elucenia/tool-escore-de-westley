<!-- ELUCENIA technical documentation · escore-de-westley · de · no clinical/professional/rights approval -->

# Westley-Score (Pseudokrupp)

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/escore-de-westley)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Bewusstseinslage

`cons`

- `0` — Normal (auch im Schlaf)
- `5` — Desorientiert

### Zyanose

`cian`

- `0` — Nicht vorhanden
- `4` — Bei Agitiertheit
- `5` — In Ruhe

### Stridor

`estr`

- `0` — Nicht vorhanden
- `1` — Bei Agitiertheit
- `2` — In Ruhe

### Lufteintritt

`ar`

- `0` — Normal
- `1` — Vermindert
- `2` — Stark vermindert

### Einziehungen

`ret`

- `0` — Nicht vorhanden
- `1` — Leicht
- `2` — Mäßig
- `3` — Schwer

## Fassung der Methode

Westley 1978: 5 Faktoren, 0–17; Krupp

## Dokumentierte Formel

Summe aus 5 Merkmalen: Bewusstsein (0 oder 5), Zyanose (0, 4 oder 5), Stridor (0 bis 2), Lufteintritt (0 bis 2), Einziehungen (0 bis 3). Gesamt 0 bis 17.

## Grenzen und Population

Westley 1978 untersuchte in einer Interventionsstudie 20 Kinder von 4 Monaten bis 5 Jahren, hospitalisiert wegen akuten Krupps mit anhaltendem Ruhestridor. Dieser Altersbereich beschreibt die Originalkohorte und legt allein keine universellen Scoreanwendungsgrenzen fest. Punktetabelle und verwendete Schweregradeinteilung müssen spezifisch geprüft werden.

## Referenzen

- [Westley CR, Cotton EK, Brooks JG. Nebulized racemic epinephrine by IPPB for the treatment of croup: a double-blind study. Am J Dis Child, 1978.](https://doi.org/10.1001/archpedi.1978.02120300044008)

- [Bjornson CL, Johnson DW. Croup in children. CMAJ, 2013.](https://doi.org/10.1503/cmaj.121645)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

Leichter Pseudokrupp (≤ 2)

Orales Dexamethason 0,15 bis 0,6 mg/kg als Einzeldosis; Entlassung mit Anweisungen.


### 2

Leichter Pseudokrupp (≤ 2)

Orales Dexamethason 0,15 bis 0,6 mg/kg als Einzeldosis; Entlassung mit Anweisungen.


### 3

Mäßiger Pseudokrupp (3 bis 5)

Dexamethason; bei Stridor in Ruhe vernebeltes Epinephrin erwägen und nach Epinephrin 2 bis 4 Stunden beobachten.


### 4

Schwerer Pseudokrupp (6 bis 11)

Vernebeltes Epinephrin + Dexamethason, bei Bedarf Sauerstoff und verlängerte Beobachtung oder Hospitalisierung.


### 5

Drohendes respiratorisches Versagen (≥ 12)

Vernebeltes Epinephrin, Sauerstoff und Alarmierung des Atemwegsteams sowie der pädiatrischen Intensivstation.

