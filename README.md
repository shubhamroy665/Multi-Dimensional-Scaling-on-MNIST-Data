
# Multi-Dimensional Scaling on MNIST Data

## Overview

In this project, we implement the Multi-Dimensional Scaling (MDS) algorithm from scratch to visualize high-dimensional data from the MNIST dataset in a lower-dimensional space. MDS is a technique used for visualizing the similarity or dissimilarity of data points while preserving their pairwise distances as much as possible.

## Dataset

We utilized the MNIST dataset, a widely used benchmark dataset in machine learning and computer vision. It consists of 28x28 pixel grayscale images of handwritten digits (0-9) along with their corresponding labels. The dataset is included in the `data/` directory of this repository.

## Implementation

Our implementation of the Multi-Dimensional Scaling (MDS) algorithm can be found in the Jupyter Notebook `mds_algorithm.ipynb`. Key components of our implementation include:
- Computing pairwise distances or dissimilarities between data points.
- Applying MDS to transform high-dimensional data into a lower-dimensional representation.
- Visualizing the lower-dimensional representation to understand the structure and relationships between data points.

## Repository Structure

- **data/:** Directory containing the MNIST dataset used for MDS analysis.
- **mds_algorithm.ipynb:** Jupyter Notebook containing the code for implementing the Multi-Dimensional Scaling (MDS) algorithm.

## Running the Notebook

To run the notebook:
1. Ensure Python and Jupyter Notebook are installed.
2. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Multi-Dimensional-Scaling-on-MNIST-data.git
   cd Multi-Dimensional-Scaling-on-MNIST-data
