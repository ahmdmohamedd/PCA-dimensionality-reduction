# Dimensionality reduction using PCA on Iris Dataset

## Overview
This project demonstrates the application of Principal Component Analysis (PCA) for dimensionality reduction using the Iris dataset. The Iris dataset contains measurements of different features of iris flowers, which are categorized into three species. The goal of this project is to visualize the data in a lower-dimensional space while retaining as much variance as possible.

## Table of Contents
- [Dataset](#dataset)
- [PCA Explanation](#pca-explanation)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)

## Dataset
The Iris dataset consists of 150 samples from three species of iris flowers:
- Iris Setosa
- Iris Versicolor
- Iris Virginica

Each sample has four features:
1. Sepal Length (cm)
2. Sepal Width (cm)
3. Petal Length (cm)
4. Petal Width (cm)

## PCA Explanation
Principal Component Analysis is a technique used to reduce the dimensionality of a dataset while preserving as much variance as possible. By transforming the original features into principal components, PCA helps visualize the data and can improve model performance in machine learning tasks.

## Installation
To run this project, you need to have Python installed along with the following libraries:
- NumPy
- Matplotlib
- Scikit-learn

You can install the required libraries using pip:

```bash
pip install numpy matplotlib scikit-learn
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/ahmdmohamedd/PCA-dimensionality-reduction.git
   cd PCA-dimensionality-reduction
   ```

2. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook PCA_Iris.ipynb
   ```

3. The notebook contains explanations, code, and visualizations of PCA applied to the Iris dataset.

## Results
The resulting PCA plot visualizes the three species of iris flowers in a two-dimensional space defined by the first two principal components. The clear separation of species indicates the effectiveness of PCA in revealing the underlying structure of the data.

## Contributing
Contributions are welcome! Please feel free to open an issue or submit a pull request if you have suggestions for improvements.
