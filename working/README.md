Launch notebooks from this directory. Temporary and submission files will also be created here.

Notebooks:
* [1_prepare_data.ipynb](1_prepare_data.ipynb) - load the data from zip-archives and re-save in a convenient 3D-tensor form;
* [2_eda.ipynb](2_eda.ipynb) - explore the patterns in the data;
* [3_synthetic_dataset.ipynb](3_synthetic_dataset.ipynb) - generate the data for auxiliary task of finding patterns in time series;
* [4_synthetic_model.ipynb](4_synthetic_model.ipynb) - train a neural network to find patterns and apply it to the original data;
* [5_final_model.ipynb](5_final_model.ipynb) - train a linear model on a bunch of simple statistic features and feed them together with a NN output to the LightGBM stacker.
