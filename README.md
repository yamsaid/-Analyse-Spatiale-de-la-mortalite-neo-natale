![header](https://capsule-render.vercel.app/api?type=cylinder&color=0:16213e,100:0f3460&height=180&text=Analyse%20Spatiale%20de%20la%20Mortalité%20Néo-natale%20au%20Burkina%20Faso&fontSize=20&fontColor=ffffff&desc=SIG%20|%20QGIS%20|%20Santé%20Publique%20|%20Analyse%20Territoriale&descSize=15&descAlignY=75)

<p align="center">

<img src="https://img.shields.io/badge/QGIS-Géomatique-589632?style=for-the-badge&logo=qgis&logoColor=white"/>
<img src="https://img.shields.io/badge/SIG-QGIS%203.34-success?style=for-the-badge&logo=qgis"/>

<img src="https://img.shields.io/badge/Python-Traitement%20des%20données-3776AB?style=for-the-badge&logo=python&logoColor=white"/>

<img src="https://img.shields.io/badge/Excel-Préparation%20des%20données-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white"/>

<img src="https://img.shields.io/badge/Domaine-Santé%20Publique-red?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Zone%20d'étude-Burkina%20Faso-orange?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Statut-Terminé-success?style=for-the-badge"/>

</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

<p align="center">
  <a href="#">
    <img src="https://img.shields.io/badge/🇫🇷%20Français-2d6a4f?style=for-the-badge" alt="Version Française"/>
  </a>

  <a href="README_EN.md">
    <img src="https://img.shields.io/badge/🇬🇧%20English-1d3557?style=for-the-badge" alt="English Version"/>
  </a>
</p>

# Résumé

*La mortalité néo-natale demeure un défi majeur de santé publique au Burkina Faso. Malgré les progrès réalisés dans le domaine de la santé maternelle et infantile, des disparités géographiques importantes persistent entre les provinces du pays.*

*Ce projet mobilise les Systèmes d'Information Géographique (SIG) afin d'analyser la distribution spatiale de la mortalité néo-natale à l'échelle provinciale. À partir de données sanitaires, démographiques et socio-économiques, plusieurs indicateurs ont été cartographiés afin d'identifier les zones les plus vulnérables et d'explorer les facteurs associés à ce phénomène.*

*L'étude combine extraction de données, traitement statistique, analyse exploratoire et cartographie thématique sous QGIS pour fournir une lecture territoriale des inégalités de santé observées au Burkina Faso.*

### 🚀 Principaux résultats

✔ Analyse réalisée sur les **45 provinces** du Burkina Faso

✔ Cartographie de la mortalité néo-natale à l'échelle provinciale

✔ Identification des provinces à risque élevé

✔ Analyse de l'accessibilité géographique aux infrastructures sanitaires

✔ Étude du lien entre pauvreté et mortalité néo-natale

✔ Production de cartes thématiques sous QGIS

✔ Utilisation conjointe de données sanitaires, démographiques et socio-économiques

**Compétences mobilisées :** SIG, géomatique, analyse spatiale, santé publique, cartographie thématique, Python, traitement de données, visualisation territoriale, aide à la décision.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 📌 Contexte

La mortalité néo-natale correspond au décès d'un enfant durant les vingt-huit premiers jours suivant sa naissance.

Au Burkina Faso, cet indicateur demeure une préoccupation majeure pour les acteurs de la santé publique. Les disparités observées entre les provinces suggèrent l'existence de facteurs géographiques, économiques et sanitaires qui influencent différemment le risque de décès néo-natal selon les territoires.

Les Systèmes d'Information Géographique (SIG) constituent un outil particulièrement adapté pour visualiser ces disparités spatiales, identifier les zones prioritaires et soutenir les politiques publiques de santé.

> 💡 **Problématique :**
>
> Quelles sont les provinces les plus touchées par la mortalité néo-natale au Burkina Faso et dans quelle mesure les facteurs liés à l'accessibilité aux soins et à la pauvreté contribuent-ils aux disparités observées ?

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🎯 Objectifs

### Objectif général

Analyser la répartition spatiale de la mortalité néo-natale au Burkina Faso afin d'identifier les zones prioritaires d'intervention.

### Objectifs spécifiques

- Cartographier la distribution spatiale de la mortalité néo-natale.
- Identifier les provinces à haut risque.
- Étudier l'influence de facteurs sanitaires et socio-économiques.
- Évaluer l'accessibilité géographique aux infrastructures sanitaires.
- Produire des cartes thématiques d'aide à la décision.
- Formuler des recommandations pour les décideurs publics.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🗂️ Données

<table>

<tr>

<td width="35%" valign="top">

<h3 align="center">Sources</h3>

| Élément | Description |
|----------|------------|
| Pays | Burkina Faso |
| Niveau géographique | Province |
| Nombre d'unités | 45 provinces |
| Source sanitaire | Annuaire statistique du Ministère de la Santé |
| Source démographique | Projections RGPH 2019 |
| Source socio-économique | Données d'incidence de pauvreté |
| Type d'analyse | Analyse spatiale |

</td>

<td width="65%" valign="top">

<h3 align="center">Variables retenues</h3>

| Variable | Description |
|-----------|------------|
| `province` | Nom de la province |
| `id_province` | Identifiant unique |
| `neo_natal_death_rate` | Proportion de décès néo-natal |
| `poverty_incidence` | Incidence de pauvreté |
| `health_access_0_4km` | Population vivant à moins de 4 km d'un centre de santé |
| `population_csps_ratio` | Ratio habitants / CSPS |
| `prenatal_visit_rate` | Femmes vues au premier trimestre de grossesse |

</td>

</tr>

</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🔬 Méthodologie

```text
Collecte des données
        │
        ▼
Extraction des tableaux PDF
        │
        ▼
Traitement sous Excel
        │
        ▼
Nettoyage et préparation
avec Python
        │
        ▼
Construction des indicateurs
        │
        ▼
Analyse statistique
• Corrélations
• Analyse descriptive
        │
        ▼
Jointure des données
avec les couches SIG
        │
        ▼
Production cartographique
sous QGIS
        │
        ▼
Analyse spatiale
et interprétation
```

### Étapes réalisées

#### 1. Collecte des données

Les données ont été extraites à partir de l'Annuaire Statistique 2023 du Ministère de la Santé ainsi que de bases socio-économiques complémentaires.

#### 2. Extraction des tableaux

Les tableaux contenus dans les fichiers PDF ont été convertis et restructurés afin d'obtenir une base exploitable.

#### 3. Préparation des données

- Nettoyage des données
- Agrégation provinciale
- Création des identifiants géographiques
- Construction des indicateurs

#### 4. Analyse statistique

Les relations entre les variables ont été explorées à l'aide des coefficients de corrélation de Pearson.

#### 5. Cartographie sous QGIS

Les données ont été intégrées dans les couches administratives afin de produire plusieurs cartes choroplèthes.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🛠️ Stack technique

<p align="center">

<img src="https://img.shields.io/badge/Pandas-Data%20Manipulation-3776AB?style=flat-square"/>

<img src="https://img.shields.io/badge/OpenPyXL-Excel-3776AB?style=flat-square"/>

<img src="https://img.shields.io/badge/QGIS-Cartographie-589632?style=flat-square"/>

<img src="https://img.shields.io/badge/PDF-Extraction-3776AB?style=flat-square"/>

<img src="https://img.shields.io/badge/Excel-Transformation-217346?style=flat-square"/>

<img src="https://img.shields.io/badge/SIG-Analyse%20Spatiale-589632?style=flat-square"/>

</p>


# 📊 Résultats

<table>

<tr>

<td width="50%" valign="top">

<h3>Corrélations observées</h3>

| Variable | Corrélation |
|-----------|------------|
| Pauvreté | 0.148 |
| Distance aux soins | -0.180 |
| Ratio habitants/CSPS | -0.283 |
| Consultation prénatale | 0.008 |

</td>

<td width="50%" valign="top">

<h3>Zones à risque élevé</h3>

| Province |
|-----------|
| Léraba |
| Sissili |
| Zondoma |

</td>

</tr>

</table>

## Visualisations

### Mortalité néo-natale par province

![Carte mortalité néo-natale](Cartes/PROP.jpeg)


### Accessibilité aux centres de santé

![Accessibilité](Cartes/CT_prop04km.jpeg)

### Incidence de pauvreté

![Pauvreté](Cartes/CT_INCID.jpeg)

### Femmes vues au premier trimestre

![Consultation prénatale](Cartes/CT_propFem.jpeg)

### Mortalité néo-natale et proportion des femmes par province

![Carte mortalité néo-natale](Cartes/CT_deces_propf.jpeg)

### Ratio habitants / CSPS

![Ratio habitants CSPS](Cartes/CT_ratio.jpeg)



<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 💡 Interprétation

### Zones prioritaires

La Léraba, la Sissili et le Zondoma apparaissent comme les provinces présentant les niveaux les plus élevés de mortalité néo-natale.

### Accessibilité aux soins

Les provinces où la population réside davantage à proximité des centres de santé tendent à présenter des niveaux plus faibles de mortalité néo-natale.

### Influence de la pauvreté

Une corrélation positive est observée entre l'incidence de pauvreté et la mortalité néo-natale, même si cette relation demeure faible.

### Consultations prénatales

Les données analysées montrent une relation très faible entre la consultation au premier trimestre et la mortalité néo-natale.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🌍 Impact

Les résultats peuvent contribuer à :

- La planification sanitaire territoriale.
- L'identification des zones prioritaires d'intervention.
- L'amélioration de l'accessibilité aux soins.
- La réduction des inégalités géographiques de santé.
- L'allocation optimale des ressources sanitaires.
- Les travaux de recherche en santé publique.
- Les études SIG appliquées au développement.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# ⚠️ Limites

> [!WARNING]
>
> Les analyses reposent sur un nombre limité d'observations (45 provinces), ce qui réduit la puissance statistique des corrélations observées.

> [!WARNING]
>
> Les données utilisées proviennent de différentes sources et peuvent comporter certaines imprécisions liées aux opérations d'extraction et d'agrégation.

> [!WARNING]
>
> Une corrélation observée ne constitue pas une relation causale.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 🧠 Compétences développées

| Domaine | Compétences |
|----------|------------|
| SIG | QGIS, cartographie thématique |
| Analyse spatiale | Analyse territoriale |
| Data Cleaning | Extraction et préparation de données |
| Python | Traitement automatisé |
| Santé publique | Analyse d'indicateurs sanitaires |
| Statistiques | Corrélations, indicateurs |
| Géomatique | Jointures et gestion des couches |
| Visualisation | Production de cartes |
| Aide à la décision | Analyse territoriale appliquée |

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 👥 Équipe & Encadrement

## Réalisé par

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

## Encadrement

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

# 📁 Structure du projet

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

# 📄 Lire le rapport

<p align="center">

![cover](Cartes/image.png)

</p>

<p align="center">

<a href="Rapport.pdf">

<img src="https://img.shields.io/badge/Lire%20le%20rapport-PDF-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"/>

</a>

</p>


<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>

# 📚 Références bibliographiques

- Laurent Boissier (2013). *La mortalité liée aux crues torrentielles dans le Sud de la France : une approche de la vulnérabilité humaine face à l'inondation.*

- Ministère de la Santé du Burkina Faso. *Annuaire Statistique 2023.*

- INSD. *Projections démographiques du RGPH 2019.*

- Investissements marginaux pour la santé maternelle et néonatale : analyse de l'accessibilité géographique aux soins obstétricaux et néonataux d'urgence.

- Plan stratégique pour le développement des systèmes d'information dans la région du Pacifique occidental.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:4facfe,100:00f2fe&height=3" width="100%"/>



<p align="center">

<sub>
Projet réalisé dans le cadre du cours de Système d'Information Géographique (SIG) — ISSP · Université Joseph Ki-Zerbo · Burkina Faso 🇧🇫
</sub>

</p>

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:16213e,100:0f3460&height=100&section=footer)
