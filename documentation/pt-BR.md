<!-- ELUCENIA technical documentation · escore-de-westley · pt-BR · no clinical/professional/rights approval -->

# Escore de Westley (crupe)

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/escore-de-westley)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Nível de consciência

`cons`

- `0` — Normal (inclusive dormindo)
- `5` — Desorientado

### Cianose

`cian`

- `0` — Ausente
- `4` — Com agitação
- `5` — Em repouso

### Estridor

`estr`

- `0` — Ausente
- `1` — Com agitação
- `2` — Em repouso

### Entrada de ar

`ar`

- `0` — Normal
- `1` — Diminuída
- `2` — Muito diminuída

### Retrações

`ret`

- `0` — Ausentes
- `1` — Leves
- `2` — Moderadas
- `3` — Graves

## Edição do método

Westley 1978:5 fatores,0–17; crupe

## Fórmula documentada

Soma de 5 itens: nível de consciência (0 ou 5), cianose (0, 4 ou 5), estridor (0 a 2), entrada de ar (0 a 2) e retrações (0 a 3). Total de 0 a 17.

## Limites e população

A publicação Westley 1978 avaliou 20 crianças de 4 meses a 5 anos, hospitalizadas por crupe agudo com estridor persistente em repouso, em um ensaio de intervenção. Essa faixa descreve a coorte original e não determina, sozinha, os limites universais de uso do escore. A tabela de pontuação e a classificação de gravidade adotada precisam de conferência específica.

## Referências

- [Westley CR, Cotton EK, Brooks JG. Nebulized racemic epinephrine by IPPB for the treatment of croup: a double-blind study. Am J Dis Child, 1978.](https://doi.org/10.1001/archpedi.1978.02120300044008)

- [Bjornson CL, Johnson DW. Croup in children. CMAJ, 2013.](https://doi.org/10.1503/cmaj.121645)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
