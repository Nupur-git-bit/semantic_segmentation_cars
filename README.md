# Semantic Segmentation on Carvana Dataset

This repository contains an implementation of **semantic segmentation** on the [Carvana Image Masking Challenge dataset](https://www.kaggle.com/c/carvana-image-masking-challenge).  
The goal is to accurately segment **cars from high-resolution images** using deep learning models.

---

## Project Overview
- **Task:** Semantic Segmentation of cars in images  
- **Dataset:** Carvana (Kaggle)  
- **Model:** U-Net  
- **Framework:** PyTorch

## **Short Summary:**
This project implements a U-Net deep learning model to perform semantic segmentation of cars on the Carvana dataset. It takes high-resolution car images as input and produces accurate binary masks highlighting the car regions.
The results are evaluated on IoU, Dice score.
  
## Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/Nupur-git-bit/semantic_segmentation_cars.git
cd semantic_segmentation_cars
pip install -r requirements.txt



