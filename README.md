# InSAR-based Landslide Susceptibility Mapping

## Objective
Evaluate whether InSAR improves landslide prediction using ML.

## Data
- DEM (Copernicus GLO-30 / SRTM)
- Sentinel-1 (InSAR)
- Sentinel-2 (NDVI)
- Landslide inventory

## Methods
- Feature engineering (slope, aspect, TWI)
- InSAR velocity & coherence
- Random Forest model

## Results
- AUROC comparison (with vs without InSAR)

## Structure
├── data/
│   ├── raw/
│   ├── processed/
│
├── notebooks/
│   ├── 01_gis_preprocessing.ipynb
│   ├── 02_insar_processing.ipynb
│   ├── 03_model_training.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── features.py
│   ├── model.py
│   ├── evaluation.py
│
├── results/
│   ├── maps/
│   ├── metrics/
│
├── report/
│   ├── paper.pdf
│
├── slides/
│   ├── summary.pdf
│
├── requirements.txt
├── README.md

## How to Run
pip install -r requirements.txt
