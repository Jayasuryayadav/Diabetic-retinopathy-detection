# Classification of Diabetic Retinopathy with CNN, Transfer Learning & Ensemble ML Models

This project deals with **automatic diagnosis of Diabetic Retinopathy (DR)** with **deep learning** and **machine learning** ensemble models. The objective is to classify retinal fundus images into five levels of severity of DR employing sophisticated preprocessing, CNN models, and ensemble classifiers.

---

Diabetic Retinopathy (DR) is a major cause of blindness globally. Early and precise diagnosis is important in patient management.
This project uses **Computer Vision + Machine Learning** to classify fundus images automatically into five stages of DR:

1. **No_DR**
2. **Mild**
3. **Moderate**
4. **Severe**
5. **Proliferate_DR**

The pipeline combines:
- Handcrafted **CNN models**
- **Transfer Learning (ResNet50)** for feature extraction
- **Classical ML models** (SVM, Random Forest, KNN)
- **Boosting models** (AdaBoost, XGBoost, CatBoost)
- **Voting Ensembles** for ultimate hybrid assessment

---

Dataset Structure

Your dataset directory should be structured like this:

data/
│
├── train.csv # Contains image IDs and labels
├── colored_images/
│ ├── No_DR/
│ ├── Mild/
│ ├── Moderate/
│ ├── Severe/
│ └── Proliferate_DR/
