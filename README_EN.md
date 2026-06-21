![header](https://capsule-render.vercel.app/api?type=cylinder&color=0:16213e,100:0f3460&height=180&text=Spatial%20Analysis%20of%20Neonatal%20Mortality%20in%20Burkina%20Faso&fontSize=20&fontColor=ffffff&desc=GIS%20|%20QGIS%20|%20Public%20Health%20|%20Spatial%20Analysis&descSize=15&descAlignY=75)

<p align="center">

<img src="https://img.shields.io/badge/QGIS-Geospatial%20Analysis-589632?style=for-the-badge&logo=qgis&logoColor=white"/>

<img src="https://img.shields.io/badge/Python-Data%20Processing-3776AB?style=for-the-badge&logo=python&logoColor=white"/>

<img src="https://img.shields.io/badge/Excel-Data%20Preparation-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white"/>

<img src="https://img.shields.io/badge/Domain-Public%20Health-red?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Study%20Area-Burkina%20Faso-orange?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>

</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

<p align="center">
  <a href="README.md">
    <img src="https://img.shields.io/badge/🇫🇷%20Français-2d6a4f?style=for-the-badge" alt="French Version"/>
  </a>

  <a href="#">
    <img src="https://img.shields.io/badge/🇬🇧%20English-1d3557?style=for-the-badge" alt="English Version"/>
  </a>
</p>


# Executive Summary

*Neonatal mortality remains a major public health challenge in Burkina Faso. Despite significant progress in maternal and child health, substantial geographic disparities persist across the country's provinces.*

*This project uses Geographic Information Systems (GIS) to analyze the spatial distribution of neonatal mortality at the provincial level. Drawing on health, demographic, and socio-economic data, several indicators were mapped to identify the most vulnerable areas and explore the factors associated with neonatal deaths.*

*The study combines data extraction, statistical processing, exploratory analysis, and thematic cartography in QGIS to provide a territorial perspective on health inequalities in Burkina Faso.*

### 🚀 Key Results

✔ Analysis conducted across **45 provinces** of Burkina Faso

✔ Provincial mapping of neonatal mortality

✔ Identification of high-risk provinces

✔ Assessment of geographical accessibility to healthcare facilities

✔ Investigation of the relationship between poverty and neonatal mortality

✔ Production of thematic maps using QGIS

✔ Integration of health, demographic, and socio-economic datasets

**Skills Applied:** GIS, geospatial analysis, public health analytics, thematic cartography, Python, data processing, spatial visualization, and decision-support analysis.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 📌 Background

Neonatal mortality refers to the death of a child during the first twenty-eight days after birth.

In Burkina Faso, this indicator remains a major concern for public health stakeholders. Differences observed across provinces suggest that geographical, economic, and healthcare-related factors may influence neonatal mortality risk differently from one territory to another.

Geographic Information Systems (GIS) provide powerful tools to visualize these disparities, identify priority intervention areas, and support evidence-based health policies.

> 💡 **Research Question**
>
> Which provinces are most affected by neonatal mortality in Burkina Faso, and to what extent do healthcare accessibility and poverty contribute to the observed spatial disparities?

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🎯 Objectives

### General Objective

Analyze the spatial distribution of neonatal mortality in Burkina Faso in order to identify priority intervention areas.

### Specific Objectives

* Map the spatial distribution of neonatal mortality.
* Identify high-risk provinces.
* Investigate the influence of health and socio-economic factors.
* Assess geographical accessibility to healthcare facilities.
* Produce thematic maps for decision support.
* Formulate recommendations for policymakers.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🗂️ Données

<table>

<tr>

<td width="35%" valign="top">

<h3 align="center">Sources</h3>

| Item                  | Description                             |
| --------------------- | --------------------------------------- |
| Country               | Burkina Faso                            |
| Geographic Level      | Province                                |
| Number of Units       | 45 Provinces                            |
| Health Source         | Ministry of Health Statistical Yearbook |
| Demographic Source    | 2019 Population Census Projections      |
| Socio-economic Source | Poverty Incidence Data                  |
| Analysis Type         | Spatial Analysis                        |

</td>

<td width="65%" valign="top">

<h3 align="center">Selected Variables</h3>

| Variable                | Description                                            |
| ----------------------- | ------------------------------------------------------ |
| `province`              | Province name                                          |
| `id_province`           | Unique identifier                                      |
| `neo_natal_death_rate`  | Neonatal mortality proportion                          |
| `poverty_incidence`     | Poverty incidence                                      |
| `health_access_0_4km`   | Population living within 4 km of a health facility     |
| `population_csps_ratio` | Population-to-health-center ratio                      |
| `prenatal_visit_rate`   | Women attending first-trimester prenatal consultations |

</td>

</tr>

</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🔬 Methodology

```text
Data Collection
        │
        ▼
PDF Table Extraction
        │
        ▼
Excel Processing
        │
        ▼
Data Cleaning and Preparation
using Python
        │
        ▼
Indicator Construction
        │
        ▼
Statistical Analysis
• Correlations
• Descriptive Analysis
        │
        ▼
Spatial Data Integration
with GIS Layers
        │
        ▼
Thematic Mapping
using QGIS
        │
        ▼
Spatial Interpretation
and Recommendations
```

### Main Steps

#### 1. Data Collection

Data were extracted from the 2023 Statistical Yearbook of the Ministry of Health and complementary socio-economic sources.

#### 2. Table Extraction

PDF tables were converted and restructured into usable datasets.

#### 3. Data Preparation

* Data cleaning
* Provincial aggregation
* Geographic identifier creation
* Indicator construction

#### 4. Statistical Analysis

Relationships between variables were explored using Pearson correlation coefficients.

#### 5. GIS Mapping

Data were joined with administrative boundary layers to produce thematic choropleth maps.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🛠️ Technical Stack

<p align="center">

<img src="https://img.shields.io/badge/Pandas-Data%20Manipulation-3776AB?style=flat-square"/>

<img src="https://img.shields.io/badge/OpenPyXL-Excel-3776AB?style=flat-square"/>

<img src="https://img.shields.io/badge/QGIS-Cartography-589632?style=flat-square"/>

<img src="https://img.shields.io/badge/PDF-Extraction-3776AB?style=flat-square"/>

<img src="https://img.shields.io/badge/Excel-Transformation-217346?style=flat-square"/>

<img src="https://img.shields.io/badge/SIG-Analyse%20Spatiale-589632?style=flat-square"/>

<img src="https://img.shields.io/badge/SIG-QGIS%203.34-success?style=for-the-badge&logo=qgis"/>
</p>


# 📊 Results

<table>

<tr>

<td width="50%" valign="top">

<h3>Observed Correlations</h3>

| Variable                         | Correlation |
| -------------------------------- | ----------- |
| Poverty Incidence                | 0.148       |
| Healthcare Accessibility         | -0.180      |
| Population / Health Center Ratio | -0.283      |
| Prenatal Consultation Rate       | 0.008       |

</td>

<td width="50%" valign="top">

<h3>High-Risk Provinces</h3>

| Province |
| -------- |
| Léraba   |
| Sissili  |
| Zondoma  |

</td>

</tr>

</table>

## Visualizations

### Neonatal Mortality by Province

![Carte mortalité néo-natale](Cartes/PROP.jpeg)


### Accessibility to Health Facilities

![Accessibilité](Cartes/CT_prop04km.jpeg)

### Poverty Incidence

![Pauvreté](Cartes/CT_INCID.jpeg)

### First-Trimester Prenatal Consultations

![Consultation prénatale](Cartes/CT_propFem.jpeg)

### Neonatal Mortality and Women's Coverage

![Carte mortalité néo-natale](Cartes/CT_deces_propf.jpeg)

### Population-to-CSPS Ratio

![Ratio habitants CSPS](Cartes/CT_ratio.jpeg)



<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 💡 Interpretation

### Priority Areas

Léraba, Sissili, and Zondoma appear as the provinces with the highest neonatal mortality levels.

### Healthcare Accessibility

Provinces where populations live closer to health facilities tend to exhibit lower neonatal mortality rates.

### Poverty Effect

A positive relationship is observed between poverty incidence and neonatal mortality, although the association remains relatively weak.

### Prenatal Consultations

The analysis reveals a very weak relationship between first-trimester prenatal consultations and neonatal mortality.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🌍 Potential Impact

The findings can support:

* Territorial health planning
* Identification of priority intervention zones
* Improvement of healthcare accessibility
* Reduction of geographic health inequalities
* Efficient allocation of healthcare resources
* Public health research
* GIS-based development studies

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>


# ⚠️ Limitations

> [!WARNING]
>
> The analysis relies on a relatively small number of observations (45 provinces), which limits the statistical power of correlation analyses.

> [!WARNING]
>
> The datasets originate from multiple sources and may contain inaccuracies resulting from extraction and aggregation processes.

> [!WARNING]
>
> Correlation does not imply causation.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🧠 Skills Developed

| Domain           | Skills                                 |
| ---------------- | -------------------------------------- |
| GIS              | QGIS, thematic cartography             |
| Spatial Analysis | Territorial analysis                   |
| Data Cleaning    | Data extraction and preparation        |
| Python           | Automated data processing              |
| Public Health    | Health indicator analysis              |
| Statistics       | Correlation analysis                   |
| Geomatics        | Spatial joins and GIS layer management |
| Visualization    | Cartographic production                |
| Decision Support | Territorial decision-making            |

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 👥 Team & Supervision

## Developed by

<table align="center">

<tr>

<td align="center">

<b>SAVADOGO Harouna</b><br/>
<sub>Licence Professionnelle en Analyse Statistique</sub>
<br/>

<a href="https://github.com/harouna">

<img src="https://img.shields.io/badge/GitHub-harouna-181717?style=flat-square&logo=github"/>

</a>
</td>

<td align="center">

<b>YAMEOGO Saïdou</b><br/>
<sub>Licence Professionnelle en Analyse Statistique</sub><br/>

<a href="https://github.com/yamsaid">

<img src="https://img.shields.io/badge/GitHub-yamsaid-181717?style=flat-square&logo=github"/>

</a>

</td>

</tr>

</table>

## Academic Supervision

<table align="center">

<tr>

<td align="center">

<b>Dr SANGLI Gabriel</b><br/>
<sub>Enseignant SIG</sub><br/>
<sub>Institut Supérieur des Sciences de la Population (ISSP)</sub><br/>
<sub>Université Joseph Ki-Zerbo · Burkina Faso 🇧🇫</sub>

</td>

</tr>

</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 📁 Project Structure

```text
📦 analyse-spatiale-mortalite-neonatale/
│
├── README.md
├── Rapport.pdf
│
├── Data/
│
├── docs/
│
└── QGIS/
    ├── Cartes/
    ├── Couches/
    └── projets/
```

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 📄 Read the report

<p align="center">

![cover](Cartes/image.png)

</p>

<p align="center">

<a href="Rapport.pdf">

<img src="https://img.shields.io/badge/Read%20the%20report-PDF-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"/>

</a>

</p>


<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 📚 References

- Laurent Boissier (2013). *La mortalité liée aux crues torrentielles dans le Sud de la France : une approche de la vulnérabilité humaine face à l'inondation.*

- Ministère de la Santé du Burkina Faso. *Annuaire Statistique 2023.*

- INSD. *Projections démographiques du RGPH 2019.*

- Investissements marginaux pour la santé maternelle et néonatale : analyse de l'accessibilité géographique aux soins obstétricaux et néonataux d'urgence.

- Plan stratégique pour le développement des systèmes d'information dans la région du Pacifique occidental.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>



<p align="center">

<sub>
Project completed as part of the Geographic Information Systems (GIS) course — ISSP · Joseph Ki-Zerbo University · Burkina Faso 🇧🇫
</sub>

</p>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:16213e,100:0f3460&height=100&section=footer)