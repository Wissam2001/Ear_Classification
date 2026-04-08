# Ear Classification using Machine Learning & Deep Learning 👂
This project is a comprehensive Machine Learning lab assignment focused on classifying ear images to identify different individuals. The notebook implements and compares multiple approaches for feature extraction and classification, including:
- K-Nearest Neighbors (KNN) with raw pixel data
- Principal Component Analysis (PCA) for dimensionality reduction
- Artificial Neural Networks (ANN) from scratch and using TensorFlow/Keras
- Feature extraction techniques: BSIF (Binarized Statistical Image Features) and LBP (Local Binary Patterns)

# Dataset 📊
- **Type:** Ear images (.bmp format)
- **Total samples:** 493 images
- **Image dimensions:** 180×50 pixels (RGB)
- **Classes:** Multiple individuals (labeled by participant IDs like 001, 002, etc.)
- **Data split:** 67% training, 33% testing (stratified by class)

# Key Findings 📈 
- BSIF features achieved the highest accuracy (~95% with ANN)
- PCA successfully reduced dimensionality while preserving ~98% variance
- LBP alone showed poor performance with ANN (likely due to histogram features not being suitable for this network architecture)
- ANN with PCA significantly outperformed raw pixel ANN (84.7% vs 72.4%)

# Lessons Learned 🧠
- Feature extraction techniques (BSIF, LBP) can dramatically impact classification performance
- PCA is effective for reducing dimensionality while preserving information
- ANN architecture must be tailored to the feature representation (pixel vs. histogram data)
- Stratified sampling is essential for imbalanced multi-class problems

 # License 📝
  This project is for educational purposes as part of a Master's lab assignment.

# Contact ✉️
 • **Email:** wissambadia4@gmail.com
 • **LinkedIn:** [Badia Ouissam Lakas](linkedin.com/in/badia-ouissam-lakas-a66a28214)  




