# Ship Detection in Satellite Images

## Project Title  
Ship Detection in Satellite Imagery Using Convolutional Neural Networks

## Overview  
This project uses deep learning to detect the presence of ships in high-resolution satellite images. It is a binary classification problem (ship present or not) and explores various CNN-based architectures and head configurations (activation functions, dropout, pooling).

## Key Techniques  
- CNN architecture tuning (layers, dropout, GELU/Tanh)
- Data preprocessing and augmentation
- Validation accuracy tracking
- Performance metrics: confusion matrix, accuracy, recall

## How to Run  
1. Place labeled satellite image data into the `Data/` folder.
2. Open `Ships_in_satellite_images_P2.ipynb`.
3. Run all cells to train models and compare architecture performance.
4. Review output metrics and saved models in the `models/` subdirectories.

## Possible Extensions  
- Upgrade to object detection (e.g., YOLOv5)
- Integrate pretrained models (e.g., ResNet, MobileNet)
- Deploy as inference API or interactive Streamlit dashboard
