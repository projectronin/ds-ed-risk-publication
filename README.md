# ds-ed-risk-publication
This repo contains analysis code to generate the figures and tables
from the following publication:

George RD, Ellis BH, *et al*. Ensuring fair, safe, and interpretable
artificial intelligence-based prediction tools in a real-world
oncological setting. *In Revision*. Nat Comm Med.

Note that the orginal data files are not included in this repo due to
patient data sharing restrictions.

## Notebook Descriptions
* **ed_insights_metadata_performance.ipynb** - 
* **fig1_model_performance_test.ipynb** - notebook that generates
  figure 1 from the manuscript, model performance (discrimination and
  calibration) on a held-out test dataset.
* **fig2_explainability.ipynb** - notebook that generates figure 2
  from the manuscript, overall feature/value importance from shap values and
  feature contributions for two sample patients. Note that the lables
  on the plots were manually edited after this figure was generated.
* **fig3_monitoring.ipynb** - notebook that generates
  figure 3 from the manuscript, monitoring various drift metrics (data
  drift, prediction drift, label drift, model drfit) across a 3-month
  time period while the ed prediction model was deployed.
* **calibration_utils.ipynb** - notebook containing a handful of
  functions used to calculate and plot calibration metrics. These
  functions are imported into the fig1 and fig3 notebooks.
