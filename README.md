# Doping position estimation for FeRh‑based alloys
This is the repository for the paper Doping position estimation for FeRh‑based alloys. 
FeRh‑based alloys have attracted significant attention due to their magnetic phase transition and significant magnetocaloric effects. These properties position them as promising candidates for fundamental research and practical applications, including magnetic cooling and targeted drug delivery. The study of FeRh alloys, particularly those where Rhodium or Iron atoms are substituted with other transition metals, is crucial as certain substitutions preserve the alloy’s magnetocaloric properties. However, even within a specific structural type and without considering competing phases, determining which atom (Fe or Rh) is replaced upon introducing a third element remains unclear. This paper addresses this ambiguity through ab initio calculations. We propose an approach to predict whether a dopant will replace Fe or Rh, offering insights into the electronic and structural factors influencing the substitution. Additionally, we present a dataset of ab initio calculations on doped FeRh alloys, which will support future data‑driven modeling efforts. Our findings not only advance the understanding of FeRh‑based alloys but also contribute to the design of novel materials for experimental and industrial applications.

```
@article{10.1038/s41598-024-71058-2, 
year = {2024}, 
title = {{Doping position estimation for FeRh-based alloys}}, 
author = {Rumiantsev, Egor and Khrabrov, Kuzma and Tsypin, Artem and Peresypkin, Nikita D and Gimaev, Radel R and Zverev, Vladimir and Eremin, Roman and Kadurin, Artur}, 
journal = {Scientific Reports}, 
doi = {10.1038/s41598-024-71058-2}, 
abstract = {{FeRh-based alloys have attracted significant attention due to their magnetic phase transition and significant magnetocaloric effects. These properties position them as promising candidates for fundamental research and practical applications, including magnetic cooling and targeted drug delivery. The study of FeRh alloys, particularly those where Rhodium or Iron atoms are substituted with other transition metals, is crucial as certain substitutions preserve the alloy’s magnetocaloric properties. However, even within a specific structural type and without considering competing phases, determining which atom (Fe or Rh) is replaced upon introducing a third element remains unclear. This paper addresses this ambiguity through ab initio calculations. We propose an approach to predict whether a dopant will replace Fe or Rh, offering insights into the electronic and structural factors influencing the substitution. Additionally, we present a dataset of ab initio calculations on doped FeRh alloys, which will support future data-driven modeling efforts. Our findings not only advance the understanding of FeRh-based alloys but also contribute to the design of novel materials for experimental and industrial applications.}}, 
pages = {20612}, 
number = {1}, 
volume = {14}
}
```

## Dataset

The dataset consists of the energy relaxation DB ([full_db](data/FeRhDoped.db), [relaxed_db](data/FeRhDopedOptimized.db)) and electronic structure data file [CSV_file](data/doped_stats.csv).

## Notebooks

[Database overview](notebooks/Atomic%20databases.ipynb)

[Decision tree construction](notebooks/doped_decision_tree.ipynb)