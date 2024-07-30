## Exploring Dimensionality, Clustering, and Shape Analysis

This repository contains the code and analysis for an assignment exploring different data analysis techniques, including dimensionality reduction, clustering, and shape analysis. The project aims to demonstrate the application and effectiveness of these techniques in understanding data patterns and relationships.

**Project Structure:**

* **`PCA.ipynb`**: Jupyter Notebook containing the implementation of Principal Component Analysis (PCA) for dimensionality reduction on two datasets: IIIT-CFW and Pictionary. 
* **`EM-GMM.ipynb`**: Jupyter Notebook containing the implementation of the Expectation-Maximization (EM) algorithm for Gaussian Mixture Models (GMM) and clustering on the wine dataset.
* **`Hierarchical-Clustering.ipynb`**: Jupyter Notebook containing the implementation of Hierarchical Clustering with various linkage methods on two datasets: a generic dataset and a gene expression dataset. 
* **`misc.ipynb`**: Jupyter Notebook containing implementations for:
    * **Problem 4.1**: Shape alignment using a given template shape from the KIMIA-99 dataset.
    * **Problem 4.2**: Finding optimal horizontal and vertical distance thresholds for connecting bounding boxes containing words in a document.
    * **Problem 4.3**: Identifying color components in a 2D color space dataset generated from Gaussian color components.
* **`datasets/`**: Folder containing the datasets used for the assignment:
    * `IIIT-CFW`: Dataset for PCA dimensionality reduction.
    * `pictionary.npy`: Dataset for PCA dimensionality reduction.
    * `wine.csv`: Dataset for GMM and K-Means clustering.
    * `gene_expression.csv`: Dataset for Hierarchical Clustering.
    * `KIMIA-99`: Dataset for shape alignment.
    * `document_data.csv`: Dataset for bounding box connection analysis.
    * `color_dataset.npy`: Dataset for color component identification.

**Instructions:**

1. **Install Required Libraries:**
   ```bash
   pip install numpy pandas matplotlib scikit-learn plotly
   ```
2. **Run the Jupyter Notebooks:**
   ```bash
   jupyter notebook PCA.ipynb 
   jupyter notebook EM-GMM.ipynb 
   jupyter notebook Hierarchical-Clustering.ipynb
   jupyter notebook misc.ipynb
   ```
3. **Explore the code:**
   Each notebook provides detailed explanations and code comments, guiding you through the implementation and analysis of each technique. 

**Key Concepts:**

* **Dimensionality Reduction:** Techniques for reducing the number of features in a dataset while preserving important information.
* **Principal Component Analysis (PCA):** A widely used technique for linear dimensionality reduction.
* **Clustering:** Algorithms for grouping similar data points into clusters based on their features.
* **Gaussian Mixture Models (GMM):** A probabilistic model used for clustering, assuming data points are generated from a mixture of Gaussian distributions.
* **Expectation-Maximization (EM) Algorithm:** An iterative algorithm for finding maximum likelihood estimates of parameters in models with latent variables.
* **Hierarchical Clustering:** A method for creating a hierarchical tree of clusters, grouping data points based on their similarity.
* **Shape Analysis:** Techniques for analyzing and comparing geometric shapes, including shape alignment.

**This project provides a comprehensive exploration of various data analysis techniques, demonstrating their application in diverse scenarios. You can use this repository as a foundation for further learning and experimentation with these techniques.**

**Note:** 

This project is for educational purposes and serves as a starting point for further exploration. Feel free to experiment with the code, explore different hyperparameter values, and apply these techniques to different datasets. 
