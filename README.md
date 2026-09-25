<h1>PROLONGED DRY HALTS LEAF LITTER DECOMPOSITION IN AN EPHEMERAL RIVER OF THE BRAZILIAN TROPICAL SEMIARID REGION<h1>
<h3>Abstract</h3>
The decomposition of terrestrial leaf litter (LLD) links terrestrial vegetation with microbial and invertebrate activity and plays a key role in stream ecosystem functioning. However, few studies have investigated LLD in ephemeral rivers, and no research has been done in ephemeral rivers in the Brazilian semiarid region. We quantified LLD rates of four native Caatinga species, including two deciduous and two evergreen species with contrasting foliar traits, under different hydrological conditions in the ephemeral Umbuzeiro River. We hypothesized that rainfall events and water availability would primarily drive decomposition rates, but that species would also differ by foliar traits associated with drying resistance. We conducted experiments under three different hydrological conditions (Dry, Very Dry, and Wet) at 15 sites and in two habitats (dry riverbeds and isolated pools) along the river. We incubated leaf litter for 30 days and analyzed decomposition rates using linear mixed-effects models. Decomposition rates differed strongly among experiments and species, with a significant interaction between these factors on dry riverbeds. Overall, all species had extremely higher decomposition rates in the Wet experiment, followed by the Dry experiment and extremely lower rates in the Very Dry experiment.  Although deciduous species were also expected to decompose faster than evergreen species, deciduous B. cheilantha decomposed faster than all four species, and deciduous C. blanchetianus decomposed more slowly than evergreen species in isolated pools and in wet experiments on dry riverbeds, while the evergreen species S. joazeiro decomposed faster in the Very Dry experiment on dry riverbeds. In the Umbuzeiro River, decomposition was much higher in wet experiments, suggesting that water likely triggers biological interactions and leaves anatomic traits such as cuticle removal.

<h3>Keywords</h3>
Deciduous leaves, evergreen leaves, dry riverbed, Non-Perennial Rivers, Caatinga ---
<h3>Hypothesis</h3>
Decomposition rates would be primarily driven by rainfall events and water availability, but would also differ among species according to foliar traits associated with drying resistance.

<h3>Repository structure</h3>

```plaintext
├── Codes and Data
│   ├── 01_PCA_analyses.txt
│   ├── 02_LME_analyses.txt
│   ├── 03_Traits_Anatomical_analyses.txt
│   ├── data_LLD_Brasil.csv
│   ├── PCA_data.csv
│   ├── UM.csv
│   ├── tpc.csv
│   ├── pat_fenol.txt
│   └── pat_tab.txt
│
├── README.md
└── LICENSE

```
---
<h3>Description</h3>
This study assesses how seasonal drying affects leaf litter decomposition in four native Caatinga species in the ephemeral Umbuzeiro River.

We provide:
1. LLD rate data (k) for 4 native species in 3 experimental periods and two habitat (isolated pools and dry riverbeds)
2. Anatomical traits
3. Ambiental variables
4. R scripts for analyses ran in the manuscript


<h3>How to reproduce the analyses</h3>
Open the `.txt` files in the `scripts/` folder using R or RStudio.
Run them in the following order:

```r
source("scripts/01_PCA_analyses.txt")
source("scripts/02_LME\_analyses.txt")
source("scripts/03_Traits_Anatomical_analyses.txt")
```
---
<h3>Software:</h3>
R version 4.6.1 (R Core Team, 2026)


<h3>File formats:</h3>
Databases: .csv and .txt
Scripts: .r (saved here as .txt)


<h3>License:</h3>
Code: MIT License
Data: Creative Commons Attribution 4.0 International (CC BY 4.0)

