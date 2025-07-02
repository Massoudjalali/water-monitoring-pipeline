# Global WaterPack EO Processing Pipeline

A Python-based project for automated extraction and analysis of surface water extent from EO satellite imagery using the DLR Global WaterPack product.

## 📌 Features
- Monthly and overall water occurrence calculation
- Cloud masking & water classification
- MaxFlow-based segmentation
- Time-series water/cloud area analysis
- Blunder detection with z-scores
- GeoTIFF to JPG visual export with legend and lat/lon

## 🛠 Tech Stack
Python · GDAL · Rasterio · NumPy · Matplotlib · Pandas · MaxFlow · TQDM

## 🚀 Run
```bash
python main.py
```
![Water Area](Water%20Area%20Time%20Series.png)
![Binary Water Area](Binary%Water%20Area%20Time%20Series.png)
![Cloud Area](Cloud%20Area%20Time%20Series.png)
