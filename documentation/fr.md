<!-- ELUCENIA technical documentation · escore-de-westley · fr · no clinical/professional/rights approval -->

# Score de Westley (laryngite sous-glottique)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/escore-de-westley)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Niveau de conscience

`cons`

- `0` — Normal (y compris pendant le sommeil)
- `5` — Désorienté

### Cyanose

`cian`

- `0` — Absent
- `4` — Avec agitation
- `5` — Au repos

### Stridor

`estr`

- `0` — Absent
- `1` — Avec agitation
- `2` — Au repos

### Entrée d’air

`ar`

- `0` — Normal
- `1` — Diminuée
- `2` — Très diminuée

### Tirage

`ret`

- `0` — Absentes
- `1` — Légères
- `2` — Modérées
- `3` — Sévères

## Édition de la méthode

Westley 1978 : 5 facteurs, 0–17 ; croup

## Formule documentée

Somme de 5 items : conscience (0 ou 5), cyanose (0, 4 ou 5), stridor (0 à 2), entrée d’air (0 à 2) et tirage (0 à 3). Total de 0 à 17.

## Limites et population

Westley 1978 a évalué 20 enfants de 4 mois à 5 ans hospitalisés pour un croup aigu avec stridor persistant au repos, dans un essai d’intervention. Cette tranche d’âge décrit la cohorte originale et ne définit pas, seule, les limites universelles d’utilisation du score. Le tableau de cotation et la classification de sévérité adoptée doivent être spécifiquement vérifiés.

## Références

- [Westley CR, Cotton EK, Brooks JG. Nebulized racemic epinephrine by IPPB for the treatment of croup: a double-blind study. Am J Dis Child, 1978.](https://doi.org/10.1001/archpedi.1978.02120300044008)

- [Bjornson CL, Johnson DW. Croup in children. CMAJ, 2013.](https://doi.org/10.1503/cmaj.121645)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Croup léger (≤ 2)

Dexaméthasone orale 0,15 à 0,6 mg/kg en dose unique ; sortie avec consignes.


### 2

Croup léger (≤ 2)

Dexaméthasone orale 0,15 à 0,6 mg/kg en dose unique ; sortie avec consignes.


### 3

Croup modéré (3 à 5)

Dexaméthasone ; envisager l’épinéphrine nébulisée en cas de stridor au repos et surveiller pendant 2 à 4 heures après l’épinéphrine.


### 4

Croup sévère (6 à 11)

Épinéphrine nébulisée + dexaméthasone, oxygène si nécessaire et surveillance prolongée ou hospitalisation.


### 5

Insuffisance respiratoire imminente (≥ 12)

Épinéphrine nébulisée, oxygène et activation de l’équipe des voies aériennes et des soins intensifs pédiatriques.

