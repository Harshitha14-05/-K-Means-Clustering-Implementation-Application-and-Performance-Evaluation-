# K-Means Clustering on the Iris Dataset

## Overview
This project demonstrates the implementation of the **K-Means clustering algorithm** on the **Iris dataset**. The performance of the algorithm is evaluated by measuring the sum of squared Euclidean distances (inertia) from each example to its assigned cluster centroid. The impact of different values of **K** (number of clusters) on performance is analyzed.

## Dataset
The dataset used is the **Iris dataset**, which contains four numerical features:
- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`

Ensure that the dataset (`IRIS.csv`) is available in the same directory as the script.

## Installation & Requirements
To run this project, install the necessary dependencies:

```bash
pip install numpy pandas scikit-learn matplotlib
```

## Usage
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. **Run the script**:
   ```bash
   python kmeans_clustering.py
   ```

## How It Works
1. The dataset is loaded using **Pandas**.
2. Numerical features are extracted for clustering.
3. The features are standardized using **StandardScaler** to improve clustering performance.
4. The **K-Means algorithm** is applied for different values of **K** (from 2 to 10), and the **inertia (sum of squared distances)** is recorded.
5. An **elbow plot** is generated to determine the optimal value of **K**.
6. The dataset is clustered using the chosen **K** (default: **K=3**).
7. Cluster labels and centroids are visualized using **Matplotlib**.

## Output
- **Inertia values plotted against K** to identify the best number of clusters.
- **Cluster assignments** added to the dataset.
- **Scatter plot of clustered data** (first two features used for visualization).
- **Centroids of clusters** plotted in red.

## Example Visualization
The output scatter plot represents clusters based on `sepal_length` and `sepal_width`:

![K-Means Clustering Visualization](example_plot.png)

## License
This project is licensed under the MIT License.

## Author
Lukka Harshitha - [Your GitHub Profile("https://github.com/Harshitha14-05")]

