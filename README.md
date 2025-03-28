# Music Clustering and Classification

## Description
This project focuses on clustering music data using KMeans and DBSCAN algorithms. After clustering, the data is labeled accordingly, and a classification model is built using Logistic Regression and Random Forest to predict cluster membership.

## Dependencies
The following libraries are used in this project:
- **pandas**: Data manipulation and analysis.
- **matplotlib.pyplot**: Visualization of graphs and clustering results.
- **sklearn.preprocessing.MinMaxScaler**: Feature scaling.
- **yellowbrick.cluster.KElbowVisualizer**: Determining the optimal number of clusters using the Elbow method.
- **sklearn.cluster.KMeans**, **sklearn.cluster.DBSCAN**: Clustering algorithms.
- **sklearn.metrics.silhouette_score**: Evaluating clustering performance.
- **sklearn.ensemble.RandomForestClassifier**: Classification model using Random Forest.
- **sklearn.linear_model.LogisticRegression**: Classification model using Logistic Regression.

## Workflow
1. **Data Preprocessing**: Prepare and scale the dataset if necessary.
2. **Clustering**:
   - Use **KMeans** and **DBSCAN** to identify clusters.
   - Determine the optimal number of clusters using the **Elbow method**.
   - Evaluate clustering using the **silhouette score**.
3. **Labeling**: Assign cluster labels to the dataset.
4. **Classification Models**:
   - Train a **Logistic Regression** model to predict cluster membership.
   - Train a **Random Forest** model for classification.
5. **Evaluation**: Assess model performance using metrics such as **accuracy**, **precision**, and **recall**.

## Installation
To install the required dependencies, run:
```sh
pip install pandas matplotlib scikit-learn yellowbrick
```

## Usage
Run the main script to perform clustering and classification:
```sh
python main.py
```
Modify the dataset or model parameters as needed within the script.

## License
This project is open-source and available under the [MIT License](LICENSE).

## Author
Josephine Diva Ayurveda Verol
