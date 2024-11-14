# Street Flood Prediction Modelling

**Course**: CE784A - Machine Learning and Data Analytics for Civil Engineering Applications  
**Instructor**: Prof. Pranamesh Chakraborty  
**Semester**: 2024-25 (I)  
**Group Name**: Fluvial Prognosticators  

**Authors**:  
- Aman Kumar Singh  
- Om Jee  
- Khushbu  

## Project Overview

This project applies machine learning to predict street-level flooding in urban areas using a Random Forest regression model. The model leverages key topographic and environmental features to forecast hourly water depth during storm events, aiming for real-time flood management support.

**Key Features Used**:
- Topographic: Elevation, Depth to Water (DTW), Topographic Wetness Index (TWI)
- Environmental: Cumulative rainfall metrics and temporal rainfall intensity

The model demonstrates high predictive accuracy with training R² = 0.9977 and testing R² = 0.9463, showing potential as an efficient alternative to traditional hydrodynamic flood models.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/amanks-20/Street-Flood-Prediction.git
   cd Street-Flood-Prediction

2. **Install dependencies:**

pip install -r requirements.txt


Usage

1.	Run the Jupyter Notebook:
Open main.ipynb to see the complete workflow, including data loading, preprocessing, model training, and evaluation.
2.	Evaluate Results:
The model outputs R² and RMSE scores and provides feature importance rankings, demonstrating the influence of topographic and environmental factors on flood predictions.

Results

•	Training R²: 0.9977
•	Testing R²: 0.9463

These metrics confirm the model’s robustness and suitability for urban flood prediction, offering a practical tool for real-time applications.

Contribution

This project was collaboratively developed by Aman Kumar Singh, Om Jee, and Khushbu as part of the CE784A course.
