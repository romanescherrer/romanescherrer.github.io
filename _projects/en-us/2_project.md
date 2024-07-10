---
page_id: project_2
layout: page
title: ANR SPIraL
description: Prediction of Spatial Leptospirosis Risk with GNNs
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
> - `Projet Type`: ANR SPIraL
> - `Role`: Postdoctoral researcher
> - `Period`: Jan. 2024 - Jun. 2024
> - `Partners`: ISEA, IPNC, HSM, IMPMC
> - `Research Themes` : Graph mining, GNN, Pooling layers, Regression, Classification.

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
    Study location.
</div>

## `ANR SPIraL: Study of the Leptospira Ecosystem and Leptospirosis Risk`

Leptospirosis is a serious bacterial disease with a significant impact, particularly in tropical regions. Despite its increasing incidence in Europe, notably in France, Belgium, Croatia, and the Netherlands, it remains largely neglected. Each year, it affects nearly one million people and causes 58,900 deaths.

Leptospires chronically colonize the kidneys of mammals and are excreted into the environment, where they can infect humans. The complex interactions between animals, their environment, and humans determine the spread of this disease. Understanding the ecology of leptospires within ecosystems is therefore crucial. Despite decades of studies on leptospirosis as a zoonosis, the ecological determinants of its transmission have not been fully explored.

The SpIRAL project aims to define the habitat of Leptospira outside the host. Its main objectives are:

- Identify the abiotic factors influencing the survival of Leptospira in soils and fresh waters.
- Characterize the environmental microbiota that hosts Leptospira.
- Model the dispersion dynamics of Leptospira during rain episodes.
- Generate a spatial risk map incorporating environmental, ecological, and climatic parameters.

---

## `Contributions to the Project`

```echarts
{
  "title": {
    "text": "Number of reported cases"
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
