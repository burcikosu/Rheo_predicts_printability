# Rheo_predicts_printability
Rheology_models
This folder contains the notebook Rheological_models_fit_capillary.ipynb, which fits different rheological models to experimental capillary data. An example dataset, PP_1.0NC.CSV, is provided, containing shear rate, stress, and viscosity values. The output is saved as PP_1.0NC_capillary_output.xlsx. The same code can be used to fit steady-sweep experimental data.

ML_models
This folder contains the dataset (xlsx) with one sample per row. Each row includes printing parameters, rheological parameters calculated from the previous notebook, complex viscosity data, TGA and DSC features, and the final print metrics: weight deviation, internal diameter deviation, and roughness average.

The notebook Printability_models.ipynb first defines different feature sets and runs a Random Forest classification model for each. Then, regression models for geometrical features are built for samples in the best printability region.
