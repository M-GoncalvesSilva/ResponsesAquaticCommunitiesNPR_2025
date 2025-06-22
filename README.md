# Responses of aquatic communities to seasonal changes in a non-perennial river of the Brazilian semiarid region

## Abstract

Non-perennial rivers (NPRs) are highly dynamic ecosystems that cease to flow or dry up partially or completely across time and space, representing over half of the global river network. These systems are expanding globally under climate change, yet their biodiversity patterns remain poorly understood in tropical semi-arid regions. We evaluated the effects of seasonal drying on the taxonomic (α and β) and functional diversity of fish and aquatic insects in the Cruxati NPR. Fish α-diversity remained stable between the two phases, likely reflecting physiological, trophic, and reproductive adaptations of dominant species. Insects exhibited higher α-diversity during the non-flowing phase, driven by lentic-adapted taxa. Fish β-diversity increased during the non-flowing phase due to environmental heterogeneity across isolated pools and founder effects, whereas insect β-diversity did not vary, possibly due to the limited spatial scale. Functional diversity remained unchanged between flowing and non-flowing phases in both fish and aquatic insect communities, likely due to historical periods of intense and frequent droughts. Our findings reveal that aquatic communities in semi-arid NPRs exhibit distinct results from those in temperate regions, showing seasonal persistence and highlighting the importance of historical and regional contexts in shaping biodiversity responses to hydrological fluctuations. Given the strong dependence of these communities on remnant isolated pools during the non-flowing phase, proper water resource management is crucial to ensure the ecological resilience of NPRs.

## Keywords

*intermittent streams*, *tropical semi-arid regions*, *local and regional diversity*, *functional redundancy*, *aquatic macroinvertebrates*

---

## Repository structure

```plaintext
.
├── Codes and Data
│   ├── 01_preliminary_analyses.txt
│   ├── 02_H1_alpha_diversity.txt
│   ├── 03_H2_beta_diversity.txt
│   └── 04_H3_functional_diversity.txt
│   ├── fish_density.csv
│   ├── insect_density.csv
│   ├── fish_traits.csv
│   └── insect_traits.csv
├── README.md
└── LICENSE
```

---

## Description

This study assesses how seasonal drying affects fish and aquatic insect communities in a non-perennial river of the Brazilian semiarid region. We provide:

- Density data for fish and aquatic insects  
- Functional trait matrices for both groups  
- R scripts for each hypothesis tested in the manuscript

### Hypotheses tested:

- **H1**: Reduced taxonomic α-diversity during the non-flowing phase compared to the flowing phase due drying acts as a filter that constrains aquatic communities.
- **H2**: Increased spatial β-diversity in the non-flowing phase due to environmental heterogeneity among isolated pools  
- **H3**: Stable functional diversity due to historical functional redundancy

## How to reproduce the analyses

1. Open the `.txt` files in the `scripts/` folder using R or RStudio.  
2. Run them in the following order:

```r
source("scripts/01_preliminary_analyses.txt")
source("scripts/02_H1_alpha_diversity.txt")
source("scripts/03_H2_beta_diversity.txt")
source("scripts/04_H3_functional_diversity.txt")
```

---

### Software:

- R version 4.4.2 (R Core Team, 2025)

---

### File formats: 

- Databases: .csv
- Scripts: .r (saved here as .txt)

---

### Licence:

- Code: MIT License
- Data: Creative Commons Attribution 4.0 International (CC BY 4.0)
