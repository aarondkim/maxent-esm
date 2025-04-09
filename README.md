# Investigating Environemntal Suitability and its Impact on Global Top Crops

Building upon prior ecology research and environmental suitability modeling, (1) we train suitability models for asian rice (oryza sativa), sugar (saccharum officinarum), maize (zea mays), wheat (triticum aestivum), and arabica coffee (coffea arabica), (2) create a new method for calculating each country’s composite environmental suitability, (3) analyze feature importance of bioclimatic variables, and (4) conduct regional crop case studies

## Environmental Suitability Model:
<img width="727" alt="Screen Shot 2025-04-09 at 1 58 47 PM" src="https://github.com/user-attachments/assets/fff4e7a0-b048-4b0d-98fe-c3388fc4a7bb" />

## Model Output:
<img width="729" alt="Screen Shot 2025-04-09 at 2 00 16 PM" src="https://github.com/user-attachments/assets/c9db00e8-534e-4b3d-b6b3-352c4f038054" />

## Notable Findings:
<img width="730" alt="Screen Shot 2025-04-09 at 2 12 03 PM" src="https://github.com/user-attachments/assets/088dde24-5044-48c1-b02b-e13f5d789480" />
Comparison of region with predicted sugarcane suitability increase between 1970 - 2000 and 2021 - 2041 (left) and the Amazon Rainforest in South America (right).
The left figure is a visualization of the difference/anomaly between the suitability of sugarcane in the past and future based on our model. Here, we see how the region with higher predicted suitability in the future overlaps significantly with the Amazon Rainforest. Since Brazil was the only one of the top sugarcane producing countries that showed a promising increase in predicted suitability, this is especially concerning as the expansion of sugarcane production into the Amazon Rainforest leads to deforestation and many other adverse effects on its fragile and bio-diverse ecosystem. This is corroborated by ongoing policy debates about farming in the Amazon, a region of great ecological importance.

Setup:
```bash
conda env create -f environment.yml
conda activate coffee_venv
```

Data download instructions in `data/raw/`
