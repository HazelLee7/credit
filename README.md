Project README
Data Access

The original datasets are hosted on the Wharton Research Data Services (WRDS) platform.
Please see WRDS.pdf (included in this repository) for detailed instructions on how to access and download the data from WRDS.
Due to licensing restrictions, the raw WRDS data itself cannot be shared here.

Repository Structure

notebooks/
├─ data_prep/ → notebooks for general data preprocessing
├─ preprocessing_stock/ → notebooks for stock price preprocessing
└─ analysis/ → main analysis notebooks

Running the Analysis

Intermediate, preprocessed datasets are already provided in this repository.
This means you can run the notebooks in notebooks/analysis/ directly without rerunning the preprocessing steps, unless you wish to regenerate from raw WRDS data.

Usage

Review WRDS.pdf for instructions to obtain the raw datasets from WRDS if you want to reproduce everything from scratch.

(Optional) Run notebooks in notebooks/data_prep/ and notebooks/preprocessing_stock/ to recreate intermediary datasets.

Run notebooks in notebooks/analysis/ to reproduce the main analysis using the provided intermediary data.

Notes

All notebooks use relative paths, so the project should run as-is once cloned.

If you download your own WRDS data, place it into the appropriate data/raw/ folder before running preprocessing.
Install all dependencies with:
