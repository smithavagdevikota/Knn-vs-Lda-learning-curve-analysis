# Learning-Curve Analysis of k-NN vs LDA

## 1. Project Overview

This project compares the performance of two supervised machine learning classification algorithms:

- **k-Nearest Neighbours (k-NN)**
- **Linear Discriminant Analysis (LDA)**

The main aim is to study how different training-set sizes and noise levels affect the classification performance of these algorithms.

Experiments are performed on three datasets to understand their learning behaviour, accuracy and robustness under different conditions.

## 2. Datasets Used

The project uses the following three datasets:

1. **Iris Dataset** – Contains flower measurements used to classify three Iris species.
2. **Wine Recognition Dataset** – Contains chemical measurements used to classify wine categories.
3. **Breast Cancer Wisconsin (Diagnostic) Dataset** – Contains cell-nucleus measurements used to classify benign and malignant cases.

## 3. Project Objectives

- Compare k-NN and LDA classification algorithms.
- Study the effect of different training-set sizes on model performance.
- Analyze how noise affects classification results.
- Evaluate models using multiple performance metrics.
- Use cross-validation and repeated experiments for more reliable comparisons.
- Visualize the performance of both algorithms using graphs.

## 4. Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## 5. Evaluation Metrics

The following metrics are used to evaluate the models:

| Metric | Purpose |
|---|---|
| Accuracy | Measures the overall correct predictions. |
| Precision | Measures how reliable positive predictions are. |
| Recall | Measures how many actual positive cases are correctly identified. |
| F1-score | Balances precision and recall. |

## 6. Methodology

The project follows these steps:

1. **Data Collection:** Load the Iris, Wine and Breast Cancer datasets.
2. **Data Preprocessing:** Check missing values, duplicates and unnecessary columns.
3. **Feature Scaling:** Apply StandardScaler through a machine learning pipeline.
4. **Baseline Comparison:** Train and evaluate k-NN and LDA using a train-test split.
5. **Training-Size Experiments:** Compare model performance using 20%, 40%, 60%, 80% and 100% of the available training pool.
6. **Noise Experiments:** Add different levels of Gaussian noise (0%, 5%, 10% and 20%) to the numerical features and evaluate performance.
7. **Cross-Validation:** Evaluate the algorithms across multiple validation splits.
8. **Repeated Experiments:** Repeat noise experiments and calculate mean and standard deviation.
9. **Visualization:** Generate graphs to compare the performance of both algorithms.

## 7. Project Structure

```text
Knn-vs-Lda-learning-curve-analysis/
│
├── ML_Project.ipynb
├── README.md
│
├── datasets/
│   ├── Iris.csv
│   ├── Wine dataset.csv
│   └── Breast Cancer.csv
│
├── results/
│   ├── Baseline_Results.csv
│   ├── Training_Size_Results.csv
│   ├── Cross_Validation_Results.csv
│   └── Repeated_Noise_Summary.csv
│
├── graphs/
│   └── Comparison and analysis graphs
│
└── ML_Project_Graphs.zip
```

*The structure above represents the intended organization of the repository. Update filenames if your uploaded files have different names.*

## 8. How to Run the Project

1. Clone or download this GitHub repository.
2. Open `ML_Project.ipynb` using Google Colab.
3. Upload the datasets or update the notebook paths to use the files in the `datasets` folder.
4. Run all notebook cells sequentially.
5. View the generated results and graphs.

## 9. Results and Analysis

The experiments compare k-NN and LDA in terms of:

- Performance at different training-set sizes.
- Accuracy under different noise levels.
- Accuracy, precision, recall and F1-score.
- Cross-validation performance.
- Mean and standard deviation from repeated experiments.

The detailed experimental results are available in the `results/` folder, while the generated comparison graphs are available in the `graphs/` folder.

## 10. Conclusion

This project provides a comparative study of k-NN and LDA using three different classification datasets.

By varying training-set sizes and noise levels, the study examines how the algorithms respond to changes in the training data and feature quality.

Cross-validation and repeated experiments provide additional insight into the consistency of their performance.

The study helps us understand the strengths and limitations of both algorithms and how dataset characteristics can influence classification performance.

## 11. Contributors

- **Smitha Vagdevi Kota**
- **Adyasha Mishra**


**Domain:** Classical Machine Learning – Supervised Classification
