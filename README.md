# CS274_project
Improving the scalability of collaborative Recommender System

# Movie Genre Preferences Analysis

This repository contains Python code for analyzing movie genre preferences based on user ratings. The code segments user ratings into low and high categories, computes genre preferences for each category, and performs KMeans clustering to identify similar user preferences.

## Getting Started

To run this analysis, you need to have Python installed on your system along with the required libraries: `pandas`, `sklearn`,'surprise','numpy'.

### Installation

You can install the required libraries using pip:

```bash
pip install pandas scikit-learn


Steps for running the code:
Before running the code add the two dataset files in your DRIVE under dataset folder. The path to DRIVE should look like this: '/content/drive/MyDrive/dataset/ratings.dat'
1. For seeing the results of baseline implementations,execute the code from Step 1 to Step 10.By default the number of clusters is set to 25.
2. For changing number of clusters in baseline implementation change number of clusters present in line kmeans = KMeans(n_clusters=25, random_state=42,n_init = 100) to desired value in Step 4.
3. For getting results for Hierarchical clustering execute step 1 to 3,then Step 11 and then steps 5 to 10.
4.  For getting results for GMM clustering execute step 1 to 3,then Step 12 but results and not good enough in step 12.
5. For creating genre vector without filtering execute step 1 to 10 and before executing change 







