# ML-Project
ML-Project (Supervoised Learning)
# 🌱 Soil-Based Crop Prediction using Machine Learning

## 🏆 Single Feature Evaluation

We trained a separate Logistic Regression model for each feature (`N`, `P`, `K`, `ph`) to measure its individual ability to predict the crop.

### 📈 F1 Scores by Feature:
- Nitrogen (N): *0.09149868209906838*
- Phosphorous (P): *0.14761942909728204*
- Potassium (K): *0.23896974566001802* 
- pH: *0.04532731061152114*

➡️ **Result:** The feature **Potassium (K)** achieved the **highest F1 score**, meaning it is the **most important single feature** for predicting the best crop to plant.

*This insight helps farmers focus on measuring Potassium when testing resources are limited.*
