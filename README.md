# IDC Breast Cancer Histopathology Classification using Fusion CNN and Explainable AI

This project tackles the important challenge of classifying invasive ductal carcinoma (IDC) in breast histopathology images through a deep learning-based approach.

## Project Highlights
- ✅ Developed a **Fusion CNN model** combining EfficientNetB0, ResNet50, and DenseNet121 architectures for robust feature extraction.
- ✅ Performed **balanced sampling** of 60,000 images to ensure a fair representation of both IDC-positive and IDC-negative samples.
- ✅ Implemented **data augmentation techniques** to enhance generalization and prevent overfitting.
- ✅ Emphasized **explainability** by integrating saliency maps and Grad-CAM to provide visual insights into the model's decision-making.
- ✅ Handled class imbalance using **class weighting** during training.
- ✅ Conducted proper dataset stratification into **training**, **validation**, and **test** sets to maintain statistical rigor.
- ✅ Trained models on realistic, manageable data volumes to simulate practical machine learning pipelines.

## Dataset
- **Source:** IDC Breast Cancer Histopathology Dataset (publicly available).
- **Total Samples Used for Training:** 60,000 carefully curated and balanced patches.

## Key Techniques
- Fusion of multiple CNN backbones for stronger predictive power.
- Real-time data augmentation during training.
- Strategic class balancing with computed class weights.
- Visualization of model attention using explainable AI techniques.

## Future Work
- Expand training on a larger image pool.
- Enhance model interpretability with additional XAI techniques.
- Explore patient-level prediction approaches beyond patch-level analysis.

## Acknowledgements
Special thanks to the researchers and institutions behind the IDC dataset for enabling accessible research in medical AI.

---

> 📢 **Note:** This repository is part of my ongoing AI in Healthcare portfolio projects. Follow for more upcoming innovations at the intersection of deep learning and medicine!
