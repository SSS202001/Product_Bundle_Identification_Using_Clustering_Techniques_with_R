
# Product Bundle Identification using Clustering Algorithms

This project focuses on identifying product bundles using clustering algorithms in R. It involves data preprocessing, Principal Component Analysis (PCA), and implementing K-means, Hierarchical Clustering, and DBSCAN algorithms to cluster products based on sales data. The project aims to optimize marketing strategies by grouping products that are frequently purchased together.


## Project Structure
### 1. Data Preprocessing
Libraries Used:
tidyverse, lubridate, arules, cluster, factoextra, FactoMineR
Dataset Inspection:
Loaded and explored weekly sales dataset.
Performed data cleaning, outlier detection, and normalization.

### 2. Principal Component Analysis (PCA)
Applied PCA to reduce dimensionality and extract key features.
Interpreted PCA results to understand variance explained and principal components.
Calculated silhouette width to evaluate initial clustering potential.

### 3. Clustering Algorithms
K-means Clustering:
Determined optimal clusters using the Elbow method.
Implemented K-means clustering and evaluated results using silhouette analysis.
Hierarchical Clustering:
Performed hierarchical clustering and visualized clusters using a dendrogram.
Selected clusters based on maximum distance threshold and evaluated clustering quality.
DBSCAN Clustering:
Implemented DBSCAN to identify clusters based on density.
Handled noise points and evaluated clustering quality using silhouette analysis.

### 4. Conclusion and Results
Summarized findings from each clustering algorithm.
Compared clustering methods to determine effectiveness for product bundle identification.
Selected DBSCAN as the final clustering model based on performance metrics.
## Authors

This project was developed by Siddhant Sarnobat for educational purpose.

Contact: siddhantsarnobat20@gmail.com


## Contributing

Contributions are always welcome!

I welcome contributions from the community to enhance and expand the analysis of the tourism industry in Europe. Please feel free to submit pull requests or raise issues if you have any suggestions or improvements.

## Deployment

Deployment
This project does not require deployment. Run locally following the instructions in the Run Locally section.

## Documentation

Project documentation is included within the code files and this README.


## FAQ

#### Q: What clustering algorithms are implemented?
A: K-means, Hierarchical Clustering, and DBSCAN.

#### Q: How to interpret PCA results?
A: PCA helps reduce dimensionality and visualize data patterns.


## Features

- Data preprocessing
- Principal Component Analysis (PCA)
- K-means, Hierarchical Clustering, DBSCAN clustering algorithms
- Evaluation metrics (Silhouette analysis)
- Visualization of clusters


## Feedback

I value your feedback! If you have any comments, suggestions, or questions regarding this project, please feel free to reach out to us at siddhantsarnobat20@gmail.com


## 🚀 About Me
Passionate data science student with a focus interested in data analysis and machine learning.


# Github Profile - Introduction

Welcome to my GitHub profile! Here you'll find various data science projects showcasing my skills and interests.
## 🔗 Links
LinkedIn - www.linkedin.com/in/siddhant-sarnobat


## Other Common Github Profile Sections
Feel free to check out my other projects on GitHub

## 🛠 Skills
- R Programming
- Data Analysis
- Machine Learning

## Installation

1. Install Jupyter Notebook: Follow official Jupyter installation instructions.

2. Install R Kernel: Install the R kernel for Jupyter Notebook using the following command in your R console:

R
Copy code:

install.packages('IRkernel')

IRkernel::installspec()

3. Clone the Repository: Clone this repository to your local machine:

bash

git clone https://github.com/your_username/your_repository.git
cd your_repository

4. Open Jupyter Notebook: Launch Jupyter Notebook and open the project's notebook:

bash

jupyter notebook
## Lessons Learned

Learned effective data preprocessing techniques and advanced clustering algorithms.
## Tech 

- R Programming Language
- Libraries: Tidyverse, Lubridate, arules, Cluster, Factoextra, FactoMineR


## Run Locally

To run this project locally:

1. Ensure R, Jupyter Notebook and RStudio are installed.
2. Clone the repository.
3. Follow installation steps.
4. Run scripts in Jupyter Notebook.


