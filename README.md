# chloride-migration-test-results
Experimental dataset on chloride diffusivity and compressive strength of concrete and its corresponding mortar

## 1. Project Overview
This dataset contains experimental results on the **Chloride Diffusivity** and **Compressive Strength** of concrete and mortar based on various mix proportions. The data was generated from experiments in accordance with NT BUILD 492 and ASTM C39.

## 2. Dataset Description
The repository includes two main data files in CSV format:
- `concrete_data.csv`: Experimental results for concrete specimens at 28 and 90 days.
- `mortar_data.csv`: Experimental results for mortar specimens at 28 and 90 days.

### Key Features (Columns)
- **ID**: Sample identifier (e.g., C60, M50, ISO-S)
- **w/b**: Water-to-Binder ratio
- **s/b**: Sand-to-Binder ratio
- **Water, Cement, FlyAsh, Sand, Gravel**: Mix proportions by weight (Concrete: $kg/m^3$, Mortar: $g$)
- **Age**: Curing period before testing (28 or 90 days)
- **Diffusivity_mean**: Mean chloride diffusivity coefficient ($10^{-12} m^2/s$)
- **Strength_mean**: Mean compressive strength ($MPa$)

## 3. Experimental Conditions
- **Materials**:
- Type I Portland Cement (CM33) or Fly Ash (FA33) 20% of binder substitution
- Fine Aggregate: Sand provided by SGS Korea
- Coarse Aggregate: Gravel (for concrete specimens)
- **Curing**: Water curing at $20 \pm 2^{\circ}C$

## 4. Scientific Contribution
The dataset provides a correlation between mortar and concrete diffusivity, which can be used to develop predictive models for concrete durability. Note that the w/b and s/b are the same for a pair of concrete and mortar samples.
- **Correlation Equation**: $D_{concrete} = 2.174 \times D_{mortar} \quad (R^2 = 0.91)$

## 5. Usage
This dataset is suitable for:
- Benchmarking concrete chloride penetration simulations.

## 6. License
This dataset is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)**.
Please cite this repository when using the data for research purposes.
