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
Explain folders

## How to Run
pip install -r requirements.txt
