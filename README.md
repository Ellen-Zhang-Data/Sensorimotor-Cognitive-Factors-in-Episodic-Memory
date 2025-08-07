# Sensorimotor-Cognitive Factors in Episodic Memory

## Overview

This project investigates how various sensorimotor and cognitive factors—such as spatial physical activity, mindfulness, and body awareness—relate to **episodic memory performance**. Data were collected through a large-scale psychological survey administered to University of Toronto undergraduates. Statistical techniques including ANOVA, Kruskal-Wallis tests, and multiple linear regression were applied to explore these relationships.

**Key Findings:**
- Spatial activity and mindfulness focused on *observing* are positively associated with episodic memory.
- Mindfulness focused on *acting with awareness* and body-focused imagery are negatively associated with memory.
- Total fitness, interoception, and proprioception showed weaker or non-significant associations.


## Project Structure

- `Final Report.qmd`: Quarto source document for the final report (R Markdown-style).
- `Final-Report.pdf`: Compiled PDF version of the final report.
- `data/`: (Not included here) Raw and cleaned data files used for analysis.
- `plots/`: (Optional) Visualizations used in the report.
- `scripts/`: (Optional) R scripts for data cleaning, analysis, and model building.


## Methodology

- **Participants:** 269 undergraduates from PSY100 (University of Toronto).
- **Data Collection:** Online survey using validated psychological instruments (e.g., SAM, PAS, FFMQ, Psi-Q, THISQ).
- **Key Constructs Measured:**
  - Sensorimotor activity (Team, Individual, Spatial, Non-Spatial)
  - Physical fitness across life stages
  - Trait mindfulness (5 facets)
  - Mental imagery (7 modalities)
  - Proprioception and interoception

- **Statistical Analyses:**
  - Descriptive statistics & data visualization
  - One-way ANOVA & Kruskal-Wallis tests
  - Multiple linear regression with model selection (Stepwise AIC, Elastic Net)

## Results Summary

| Predictor                        | Direction | Significance |
|----------------------------------|-----------|--------------|
| Spatial Activity (Professional) | ↑         | Marginal     |
| Mindfulness - Observing         | ↑         | Significant  |
| Mindfulness - Acting Awareness  | ↓         | Significant  |
| Body-Focused Imagery            | ↓         | Significant  |

Adjusted R² of final model: ~0.25  
RMSE: ~10.6  

## Limitations

- Homogeneous sample (mostly undergrads)
- Self-report data prone to bias
- Modest model fit (many unexplained factors remain)

## Future Directions

- Use objective cognitive tasks to validate memory performance
- Extend to diverse populations and age groups
- Explore causal mechanisms using experimental designs
- Investigate interventions like spatial training or mindfulness-based cognitive therapy

## Citation

Zhang, E. (2025). *Spatial Activity and Observing Mindfulness Enhance Episodic Memory, While Acting with Awareness and Body-Focused Imagery Impair It: A Sensorimotor-Cognitive Analysis*. University of Toronto.

---

## License

This project is intended for academic and educational use only. Please contact the author for any reuse or derivative work.
