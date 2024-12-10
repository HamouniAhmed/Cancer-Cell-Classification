# Cancer-Cell-Classification
Cancer Cell Classification Using Support Vector Machines (SVM)

## Project Overview
This project aims to classify cancer cell samples as either **benign** or **malignant** using a dataset derived from cytological observations. The classification is achieved using a machine learning algorithm, specifically a Support Vector Machine (SVM).

## Dataset Description
The dataset contains the following attributes:
- **ID**: Unique sample identifier.
- **Clump**: Clump thickness.
- **UnifSize**: Uniformity of cell size.
- **UnifShape**: Uniformity of cell shape.
- **MargAdh**: Marginal adhesion.
- **SingEpiSize**: Single epithelial cell size.
- **BareNuc**: Presence of bare nuclei.
- **BlandChrom**: Bland chromatin texture.
- **NormNucl**: Normal nucleoli.
- **Mit**: Mitoses.
- **Class**: Target variable indicating:
  - **2**: Benign.
  - **4**: Malignant.

## Methodology
1. **Data Preprocessing**:
   - Handled missing or non-numeric values in the `BareNuc` column.
   - Converted data types where necessary for numerical operations.
   - Split the dataset into training and testing sets (80/20 split).

2. **Visualization**:
   - Scatter plots were used to visualize the distribution of features for benign and malignant cases.
   - A confusion matrix was plotted to evaluate the performance of the classifier.

3. **Modeling**:
   - A Support Vector Machine (SVM) classifier was implemented with a linear kernel.

4. **Evaluation**:
   - The model was evaluated using precision, recall, F1-score, and accuracy metrics.
   - The confusion matrix was visualized to analyze classification errors.

## Results
- The SVM classifier achieved promising results, accurately classifying the majority of the samples.
- The confusion matrix provided insights into true positives, true negatives, and misclassifications.

## Requirements
The following Python libraries are required:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Install them using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

