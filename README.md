# README

## Data Access

The original datasets are hosted on the Wharton Research Data Services (WRDS) platform.  
Please see **WRDS.pdf** (included in this repository) for detailed instructions on how to access and download the data from WRDS.  

Due to licensing restrictions, no WRDS data of any form (raw, intermediate, or preprocessed) is included in this repository.  
All results must be generated directly from raw WRDS downloads.

---

## Repository Structure

```
notebooks/
├─ preprocessing_stock/  → notebooks for stock price preprocessing
├─ data_prep/            → notebooks for general data preprocessing
└─ analysis/             → main analysis notebooks
```

---

## Running the Analysis

1. **Download WRDS data** following the instructions in `WRDS.pdf`.  
   Place the downloaded files into the `data/raw/` folder.

2. **Run preprocessing notebooks** in:
   - `notebooks/data_prep/`  
   - `notebooks/preprocessing_stock/`  
   These will generate all required intermediate files locally.

3. **Run analysis notebooks** in:
   - `notebooks/analysis/`  
   to reproduce the main results.

---

## Usage Notes

- All notebooks use relative paths, so the project should run as-is once the raw WRDS data is placed in the correct location.  
