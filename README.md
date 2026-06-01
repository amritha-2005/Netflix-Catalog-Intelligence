## 🌐 Live Visual Report
👉🏼 [Click here to view the full interactive dashboard](https://amritha-2005.github.io/Netflix-Catalog-Intelligence/)
# 🎬 Netflix Catalog Intelligence & Audience Segmentation Matrix

> A multi-dimensional analysis of Netflix catalog composition across format, runtime, quality rating, demographic classification, and genre distribution.

-----

## 📌 Project Overview

This project explores the structural patterns within the Netflix content catalog using data visualization and statistical analysis. Six analytical panels translate raw catalog metadata into a coherent intelligence view of how content is organized across a global streaming ecosystem.

-----

## 📊 Dashboard Panels

|Panel|Title                                          |Description                                                                                                                      |
|-----|-----------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
|I    |**Content Volume · Quality · Runtime Density** |Hexbin density map plotting IMDb score vs runtime. High-density zones cluster at 80–120 min runtimes with the strongest ratings. |
|II   |**Portfolio Mix · Global Libraries**           |Donut chart showing catalog format split — 64% Movies vs 36% Shows.                                                              |
|III  |**Production Volume Scale Trajectory**         |Area chart of titles released per year (2000–2023). Peak output ~700+ titles/year around 2019–2020.                              |
|IV   |**Maturity Classification & Reach Profile**    |Bar chart across 8 rating categories. Unrated leads at 2,914 titles; TV-MA tops classified content at 810.                       |
|V    |**Top 10 Demand Genres by Distribution Volume**|Horizontal bar chart. Drama dominates (~2,500+ titles), followed by Comedy and Thriller.                                         |
|VI   |**Annual Quality Trend Variation (IMDb)**      |Average IMDb score tracked annually vs catalog historic mean (~6.6). Modest decline post-2018 correlates with peak volume output.|

-----

## 🔍 Key Findings

- **Dual-format system** — episodic series drive retention; feature films drive acquisition and platform prestige
- **Runtime sweet spot** — 80–120 minute content clusters at the highest IMDb scores, suggesting a structural pacing advantage
- **Mature demographic dominance** — TV-MA and R-rated content lead the classified catalog, reflecting the platform’s core adult audience
- **Genre power-law** — Drama, Comedy, and Thriller form a dominant core; remaining genres serve as long-tail depth
- **Volume–quality trade-off** — IMDb scores dipped modestly after 2018, coinciding with peak catalog expansion

-----

## 📈 Business Impact

The observed catalog structure highlights several measurable characteristics:

- A dual-format system that supports multiple consumption behaviors
- A runtime-performance clustering pattern linked with higher audience ratings
- A strong concentration of content in mature demographic categories
- A genre distribution hierarchy with dominant categories and a wider set of supporting niches

-----

## 🛠️ Tech Stack

|Tool                    |Purpose             |
|------------------------|--------------------|
|Python                  |Core analysis       |
|Pandas                  |Data wrangling      |
|Matplotlib              |Visualization       |
|Seaborn                 |Statistical plots   |
|Jupyter Notebook        |Analysis environment|
|IMDb Dataset            |Quality ratings     |
|Netflix Catalog Metadata|Content attributes  |

## 📌 Summary

This analysis provides a structured overview of catalog composition across format, runtime, demographic segmentation, and genre distribution. It identifies observable structural patterns within the dataset and translates them into a coherent view of content organization within a global streaming ecosystem 🌍.

---

*Analysis scope: Global catalog · 2000–2023 · IMDb-rated*
*Made with Python & Jupyter Notebook*

```

-----

```

-----

## 📋 Dataset

- **Netflix Titles Dataset** — catalog metadata including title, type, genre, rating, and release year
- **IMDb Ratings** — audience scores used for quality trend analysis

-----

*Analysis scope: Global catalog · 2000–2023 · IMDb-rated*
