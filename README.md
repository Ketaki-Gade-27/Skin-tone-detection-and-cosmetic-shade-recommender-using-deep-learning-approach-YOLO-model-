# Skin tone detection and cosmetic shade recommendation using deep learning approach (YOLO model)

This project predicts skin tones from images using deep learning models and recommends suitable cosmetic shades (foundation and concealer) from some top cosmetic brands.  

## Features
- Trained YOLOv8 and YOLO11n models for skin tone detection.  
- Predicts skin tone and recommends suitable cosmetic shades (YOLO11n is used for recommendation due to its higher accuracy of 85%).  

## Files in the Repository
- `YOLO8.ipynb` → Python code for YOLOv8.
- `YOLO11.ipynb` → Python code for YOLO11n (used for shade recommendation).
- `shade recommendation.ipynb` → Recommends cosmetic shades based on YOLO11n predictions.
- `Dataset` → Contains train, test and validation images.
- `Project Report.pdf` → Full project documentation.
- `README.md` → Project description.

## Usage
1. Unzip the dataset.
2. Run `YOLO11.ipynb` to detect skin tone.
3. Run `shade recommendation.ipynb` to get cosmetic shade recommendations.

---
