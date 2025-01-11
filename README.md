# Human Activity Recognition from Sensors Data  
## 📖 Overview

This project implements **Human Activity Recognition (HAR)** using sensor data collected from smartphones. The dataset contains data from accelerometers and gyroscopes, and the goal is to classify activities such as walking, sitting, standing, etc., using machine learning and deep learning models.  The dataset used is the **UCI HAR Dataset**, a widely recognized benchmark for HAR tasks.  ---  
## 📂 Project Structure 
```rust
├── Notebooks/
│   └── Human_Activity_Recognition_from_Sensors_Data.ipynb
│       - The main notebook documenting the full project workflow:
│         - Exploratory Data Analysis (EDA) and visualization
│         - Feature engineering for enhanced model performance
│         - Model training, evaluation, and insights
│
├── Datasets/
│   ├── Raw/
│   │   - Contains the unaltered UCI HAR Dataset files, as originally provided.
│   │
│   ├── Preprocessed_Dataset/
│   │   - Includes cleaned and standardized data, ready for exploratory analysis and baseline modeling.
│   │
│   ├── Engineered_Features_Dataset/
│       - Features datasets with additional engineered attributes for improved classification accuracy.
│
├── README.md
│   - A comprehensive guide to the project, including structure, usage instructions, and methodology.

```
The dataset can be found on the UCI Machine Learning Repository : https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. A Public Domain Dataset for Human Activity Recognition Using Smartphones. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013

Feature extraction was based on distribution analysis of features during the EDA phase across multiple activities. This approach aims to help the model converge faster by identifying potential label inference from one or more features. For example, the feature tBodyAccMag-mean() can distinguish between static and dynamic activities.

![tBodyAccMag-mean](https://github.com/Warzn/Human-Activity-Recognition/blob/main/EDA_Visualizations/Probability%20Density%20of%20tBodyAccMag-mean()%20by%20Activity.png)

