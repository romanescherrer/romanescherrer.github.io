---
page_id: project_2
layout: page
title: Sols, pluie et leptospirose
description: Prédiction du risque spatial de leptospirose avec des GNNs
img: assets/img/project2/carto.png
importance: 1
category: work
related_publications: false
map: true
chart:
  echarts: true
---

---

> ## Informations
>
> ---
>
> - `Type de projet`: ANR SPIraL
> - `Rôle`: Post-dostorante
> - `Période`: Jan. 2024 - Jun. 2024
> - `Partenaires`: ISEA, IPNC, HSM, IMPMC
> - `Thèmes de recherche` : _Graph mining_, GNN, _Pooling layers_, Regression, Classification.

```geojson
{
  "type": "FeatureCollection",
  "features": [
    {
      "type": "Feature",
      "properties": {},
      "geometry": {
        "coordinates": [
          [
            [
              163.58588101445508,
              -19.780097079124715
            ],
            [
              163.58588101445508,
              -22.775780967581667
            ],
            [
              168.2061092423732,
              -22.775780967581667
            ],
            [
              168.2061092423732,
              -19.780097079124715
            ],
            [
              163.58588101445508,
              -19.780097079124715
            ]
          ]
        ],
        "type": "Polygon"
      }
    }
  ]
}
```

<div class="caption">
    Zone d'étude.
</div>

## `ANR SPIraL : Étude de l'Écosystème de Leptospira et Risque de Leptospirose`

La leptospirose est une maladie bactérienne grave qui exerce un impact significatif, particulièrement en zones tropicales. Malgré son incidence croissante en Europe, notamment en France, en Belgique, en Croatie et aux Pays-Bas, elle demeure largement négligée. Chaque année, elle affecte près d'un million de personnes et cause la mort de 58 900 individus.

Les leptospires colonisent chroniquement les reins des mammifères et sont excrétés dans l'environnement, où ils peuvent infecter les humains. Les interactions complexes entre les animaux, leur environnement et les humains déterminent la propagation de cette maladie. Comprendre l'écologie des leptospires au sein des écosystèmes est donc crucial. Malgré des décennies d'études sur la leptospirose en tant que zoonose, les déterminants écologiques de sa transmission n'ont pas été pleinement explorés.

Le projet SpIRAL vise à définir l'habitat de Leptospira en dehors de l'hôte. Ses objectifs principaux sont :

- Identifier les facteurs abiotiques influençant la survie de Leptospira dans les sols et les eaux douces.
- Caractériser le microbiote environnemental qui héberge Leptospira.
- Modéliser la dynamique de dispersion de Leptospira lors des épisodes de pluies.
- Générer une carte spatiale du risque intégrant des paramètres environnementaux, écologiques et climatiques.

---

## `Contributions dans le projet`

```echarts
{
  "title": {
    "text": "Nombre de cas"
  },
  "responsive": true,
  "tooltip": {},
  "legend": {
    "top": "30px",
    "data": ["sale"]
  },
  "xAxis": {
    "data": ["2011", "2012", "2013", "2014", "2015", "2016", "2017", "2018", "2019", "2020", "2021", "2022"]
  },
  "yAxis": {},
  "series": [
    {
      "name": "cas",
      "type": "bar",
      "data": [138, 78, 73, 21, 56, 73, 91, 76, 66, 68, 226, 264]
    }
  ]
}
```
