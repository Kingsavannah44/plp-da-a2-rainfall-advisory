# plp-da-a2-rainfall-advisory

A data-analytics assignment for the PLP programme that cleans monthly rainfall data for five Kenyan counties, analyses patterns with NumPy, and produces a planting-window advisory for a farmer-support NGO.

## How to run

1. Install dependencies: `pip install -r requirements.txt`
2. Launch Jupyter: `jupyter notebook rainfall_analysis.ipynb`
3. In the Jupyter menu choose **Kernel → Restart & Run All** to execute every cell from top to bottom.
4. After the final cell runs, `rainfall_summary.csv` will be written to the same directory.

## Planting Advisory

- **April–May is the primary planting window** for Nairobi, Nakuru, Kisumu, and Mombasa, where the two months combined deliver 265–420 mm — the highest consecutive rainfall in the year and the most reliable window for establishing staple crops such as maize and beans.
- **Machakos follows a different calendar**: its wettest consecutive months are November–December (278 mm combined), so farmers there should plant at the start of the short-to-long-rains transition; with six dry months per year, drought-tolerant varieties and water-harvesting structures are strongly recommended.
- **Data-quality caveat:** Two Machakos station readings (April and September) were missing or non-numeric in the raw data and were imputed using the rounded mean of the ten valid readings (68 mm each); NGO advisories for Machakos should be verified against updated station records before SMS dissemination.
