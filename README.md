🔬 Data Analysis Project: Breast Cancer Data Clustering and Diagnosis (WDBC)
This is a comprehensive data analysis project developed as part of the Machine Learning coursework for my Data Engineering B.Sc. at Bar-Ilan University. The project's objective is to evaluate the effectiveness of unsupervised machine learning algorithms in identifying patterns and efficiently clustering medical observations.
The project is implemented using a Jupyter Notebook and presents complete analytical results.

🎯 Methodology and Analysis Stages
The project is divided into three main stages:

1. Data Preprocessing:

Loading the dataset (breast_cancer.csv).

Normalizing the data using StandardScaler to ensure equal weight across all features.

Converting diagnostic labels (M/B) into numerical values (1/0) for performance evaluation purposes.

2. Dimensionality Reduction:

Applying Principal Component Analysis (PCA) to reduce the complex feature space into two principal components (n_components=2).

3. Clustering & Evaluation:

The project examined several clustering algorithms, including K-Means, Agglomerative Clustering, and DBSCAN.

Key Achievement: The K-Means algorithm provided the clearest visual clustering. The highest score achieved on the Silhouette Score metric was 0.5369, indicating highly effective cluster separation.

The final evaluation was conducted using Accuracy metrics and a Confusion Matrix to compare the model's clusters against the original diagnostic labels.

📁 Repository Structure
ProjectCancer_New.ipynb: The Jupyter Notebook containing the code, data analysis, and visual results.

breast_cancer.csv: The original dataset (WDBC).

wdbc.data / wdbc.names: Auxiliary files describing the dataset variables.

🛠️ System Requirements
To run the code, a Python 3 environment is required along with the following libraries. You can install them using:

Bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
