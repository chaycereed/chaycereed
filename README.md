<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:010409,100:161b22&height=120&section=header&text=Chayce%20Reed&fontColor=e6edf3&fontSize=42&fontAlignY=65&fontFamily=Georgia&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=12&duration=2500&pause=99999&color=3D444D&background=0D111700&center=true&vCenter=true&width=700&height=24&lines=MS+HEALTH+DATA+SCIENCE+-+DARTMOUTH+COLLEGE+%C2%B7+GRA++-+COMPUTATIONAL+CAUSAL+INFERENCE" alt="role"/>
</p>

```yaml
name:       Chayce Reed
location:   Boston, MA
role:       Graduate Research Assistant · Computational Causal Inference
education:  UMass Amherst (BS Chemical Engineering) · Dartmouth College (MS Health Data Science)
industry:   BMS · Moderna · Oncorus
consulting: Datageek Designs LLC
website:    chaycereed.com
```

---

### Research

Computational causal inference for health systems, policy, and equity.

Research, publications, and preprints: [chaycereed.com](https://chaycereed.com)

**Methods**

<p>
  <img src="https://img.shields.io/badge/Difference--in--Differences-21262d?style=flat-square&color=21262d"/>
  <img src="https://img.shields.io/badge/Interrupted_Time_Series-21262d?style=flat-square&color=21262d"/>
  <img src="https://img.shields.io/badge/Transportability-21262d?style=flat-square&color=21262d"/>
  <img src="https://img.shields.io/badge/AIPW_%2F_DML-21262d?style=flat-square&color=21262d"/>
  <img src="https://img.shields.io/badge/IV_%2F_RDD-21262d?style=flat-square&color=21262d"/>
  <img src="https://img.shields.io/badge/Causal_Forests-21262d?style=flat-square&color=21262d"/>
</p>

**Stack**

<p>
  <img src="https://img.shields.io/badge/R-21262d?style=flat-square&logo=r&logoColor=6e7681"/>
  <img src="https://img.shields.io/badge/Python-21262d?style=flat-square&logo=python&logoColor=6e7681"/>
  <img src="https://img.shields.io/badge/SQL-21262d?style=flat-square&logo=postgresql&logoColor=6e7681"/>
</p>

---

### Projects

<div align="center">

| | | |
|:---:|:---:|:---:|
| [![medicaid-map.com](medicaid-map.png)](https://medicaid-map.com) | [![causal-workbench](causal-methods.png)](https://causal-methods.com) | [![researchatlas.ai](research-atlas.png)](https://researchatlas.ai) |
| [![annualhealthreview.com](annual-health-review.png)](https://annualhealthreview.com) | [![dag-studio](dag-studio.png)](https://dag-studio.com) | |

</div>

<br/>


<details>
<summary><b>medicaid-map.com</b> &mdash; Interactive Visualization of Medicaid Expansion Effects &nbsp;<code>web</code></summary>
<br>
  
| | |
|---|---|
| **Description** | Interactive visualization of Medicaid expansion effects: DiD on ACS PUMS 2010–2023 with state-level treatment variation; accompanying research poster |
| **Link** | https://medicaid-map.com |
| **Stack** | `R` `fixest` `TypeScript` `D3.js` `Next.js` |
 
</details>
<details>
<summary><b>causal-methods.com</b> &mdash; Code-First Reference for Causal Inference and Causal ML &nbsp;<code>web</code></summary>
<br>
  
| | |
|---|---|
| **Description** | Code-first reference for causal inference and causal ML: DiD, IV, TMLE, DML, AIPW, synthetic control, and causal forests, with worked R and Python examples |
| **Link** | https://causal-methods.com |
| **Stack** | `R` `Python` `Next.js` |
 
</details>
<details>
<summary><b>dag-studio.com</b> &mdash; Interactive DAG Construction and Analysis &nbsp;<code>web</code></summary>
<br>
  
| | |
|---|---|
| **Description** | Interactive DAG construction and analysis: build causal graphs and compute identification analysis and adjustment sets |
| **Link** | https://dag-studio.com |
| **Stack** | `TypeScript` `Next.js` `D3.js` |
 
</details>
<details>
<summary><b>annualhealthreview.com</b> &mdash; U.S. Population Health Metrics &nbsp;<code>web</code></summary>
<br>
  
| | |
|---|---|
| **Description** | Survey-style annual U.S. population health reports from NHANES: mental, physical, and lifestyle health metrics |
| **Link** | https://annualhealthreview.com |
| **Stack** | `Python` `Next.js` `plotly.js` `dplyr` `haven` |
 
</details>
<details>
<summary><b>researchatlas.ai</b> &mdash; NLP and Knowledge-Graph Literature Explorer &nbsp;<code>web</code></summary>
<br>
  
| | |
|---|---|
| **Description** | NLP and knowledge-graph literature explorer: maps connections across scientific literature using embeddings and force-directed graphs, via the Semantic Scholar API |
| **Link** | https://researchatlas.ai |
| **Stack** | `Python` `FastAPI` `Next.js` `react-force-graph` |
 
</details>

---

### R Packages

<details>
<summary><b>wmap</b> &mdash; Multi-Study Causal Effect Estimation &nbsp;<code>R</code></summary>
<br>

| | |
|---|---|
| **Description** | Causal meta-analysis integrating multiple observational studies: FLEXOR balancing weights, ranger-based propensity pipeline with cross-fitting, parallel bootstrap inference |
| **API** | `balancing_weights()` · `causal_estimate()` |
| **CRAN** | https://cran.r-project.org/web/packages/WMAP/index.html |
| **Status** | Complete · methods paper under review (R Journal) |

</details>

<details>
<summary><b>translate</b> &mdash; Causal Transport Across Populations &nbsp;<code>R</code></summary>
<br>

| | |
|---|---|
| **Description** | Transports causal estimates from large external cohorts to smaller target populations: ESS-maximizing reweighting, bootstrap inference |
| **API** | `translate()` · `translate_weights()` · `translate_estimate()` |
| **CRAN** | In Progress |
| **Status** | Preparing for CRAN submission · accompanying methods paper in progress |

</details>

<details>
<summary><b>causalsim</b> &mdash; Causal Estimator Benchmarking under Known Ground Truth &nbsp;<code>R</code></summary>
<br>

| | |
|---|---|
| **Description** | Simulation-ready causal data-generating processes with known ground truth for benchmarking estimator bias, variance, and coverage |
| **API** | `causalsim()` · `causalsim_dgp()` · `causalsim_draw()` · `causalsim_eval()` · `causalsim_grid()` |
| **CRAN** | https://cran.r-project.org/web/packages/causalsim/index.html |
| **Status** | Complete |

</details>

<details>
<summary><b>nhanesqc</b> &mdash; NHANES Preprocessing Pipeline &nbsp;<code>R</code></summary>
<br>

| | |
|---|---|
| **Description** | Quality-control pipeline for NHANES survey data: recoding, missingness handling, special values, and cross-cycle consistency checks |
| **API** | `nhanes_qc()` · `summary()` · `plot()` |
| **Repo** | https://github.com/chaycereed/nhanesqc |
| **Status** | Complete |

</details>

<details>
<summary><b>lotr</b> &mdash; Lord of the Rings Color Palettes for ggplot2 &nbsp;<code>R</code></summary>
<br>

| | |
|---|---|
| **Description** | 10 Lord of the Rings-themed color palettes for ggplot2 |
| **API** | `scale_color_lotr()` · `scale_fill_lotr_c()` · `scale_fill_lotr_d()` · `lotr_palette()` |
| **Repo** | https://github.com/chaycereed/lotr |
| **Status** | Complete |

</details>

---

### Python Tools

<details>
<summary><b>researchkit</b> &mdash; Reproducible Research Project Scaffolding &nbsp;<code>cli</code></summary>
<br>

| | |
|---|---|
| **Description** | Standardized templates and automation for reproducible analysis projects: consistent folder structure, notebooks, and READMEs |
| **API** | `researchkit`|
| **Repo** | https://github.com/chaycereed/researchkit |
| **Status** | Complete |

</details>

<details>
<summary><b>metascholar</b> &mdash; Automated Literature Retrieval and Reporting &nbsp;<code>cli</code></summary>
<br>

| | |
|---|---|
| **Description** | Automated retrieval, metadata extraction, and structured literature-scan reports via the Semantic Scholar API |
| **API** | `metascholar` |
| **Repo** | https://github.com/chaycereed/metascholar |
| **Status** | Complete |

</details>
