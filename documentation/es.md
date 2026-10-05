<!-- ELUCENIA technical documentation · escore-de-westley · es · no clinical/professional/rights approval -->

# Puntuación de Westley (crup)

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/escore-de-westley)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Nivel de conciencia

`cons`

- `0` — Normal (incluso durante el sueño)
- `5` — Desorientado

### Cianosis

`cian`

- `0` — Ausente
- `4` — Con agitación
- `5` — En reposo

### Estridor

`estr`

- `0` — Ausente
- `1` — Con agitación
- `2` — En reposo

### Entrada de aire

`ar`

- `0` — Normal
- `1` — Disminuida
- `2` — Muy disminuida

### Retracciones

`ret`

- `0` — Ausentes
- `1` — Leves
- `2` — Moderadas
- `3` — Graves

## Edición del método

Westley 1978: 5 factores, 0–17; crup

## Fórmula documentada

Suma de 5 ítems: conciencia (0 o 5), cianosis (0, 4 o 5), estridor (0 a 2), entrada de aire (0 a 2) y retracciones (0 a 3). Total de 0 a 17.

## Límites y población

La publicación Westley 1978 evaluó a 20 niños de 4 meses a 5 años, hospitalizados por crup agudo con estridor persistente en reposo, en un ensayo de intervención. Ese intervalo describe la cohorte original y no determina por sí solo los límites universales de uso de la puntuación. La tabla de puntuación y la clasificación de gravedad adoptadas requieren una comprobación específica.

## Referencias

- [Westley CR, Cotton EK, Brooks JG. Nebulized racemic epinephrine by IPPB for the treatment of croup: a double-blind study. Am J Dis Child, 1978.](https://doi.org/10.1001/archpedi.1978.02120300044008)

- [Bjornson CL, Johnson DW. Croup in children. CMAJ, 2013.](https://doi.org/10.1503/cmaj.121645)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
