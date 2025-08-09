# **K-Means Clustering with Random Data Generation**

---

## **1. Project Title**

**K-Means Clustering with Random Data Generation**

---

## **2. Problem Statement and Goal of Project**

The goal of this project is to demonstrate the **K-Means clustering** algorithm by applying it to **synthetically generated data**. The dataset is created randomly with multiple centers, and the project aims to:

* Illustrate the effectiveness of K-Means in clustering random data.
* Visualize the results and understand how the algorithm clusters the data.
* Experiment with the impact of different configurations of the K-Means algorithm.

The focus is on understanding the clustering mechanism in a controlled setting using artificial data, allowing for easy visualization and evaluation.

---

## **3. Solution Approach**

The notebook follows an end-to-end workflow:

* **Data Generation**: Using the `make_blobs` function from `sklearn.datasets`, random data with multiple centers is created.
* **Clustering**: K-Means clustering is applied to the generated data with various numbers of clusters.
* **Visualization**: The data and the results of clustering are visualized using **matplotlib**.
* **Evaluation**: Although no explicit evaluation metric is mentioned, the visual separation of clusters provides insight into the performance of the algorithm.

---

## **4. Technologies & Libraries**

* **Python** – Programming language used
* **NumPy** – Numerical computation
* **Matplotlib** – Data visualization
* **Scikit-learn** – Machine learning library (KMeans, make\_blobs)
* **Random** – Python standard library for generating random numbers

---

## **5. Description about Dataset**

* **Source**: Generated using `make_blobs` from **scikit-learn**.
* **Data Structure**:

  * **n\_samples=5000**: Total number of data points.
  * **n\_features=2**: Each data point has 2 features (2D).
  * **centers**: Randomly placed at multiple centers: `[[2,3],[5,6],[6,-2],[-3,6],[8,9]]`.
  * **cluster\_std=1**: Standard deviation for the clusters.
  * **random\_state=101**: Ensures reproducibility of the random data generation.

---

## **6. Installation & Execution Guide**

**Prerequisites**:

* Python 3.x
* Jupyter Notebook or JupyterLab

### **Clone the repository**:

```
git clone <repository_url>
cd <repository_directory>
```

### **Install required dependencies**:

```
pip install numpy matplotlib scikit-learn
```

### **Run the notebook**:

```
jupyter notebook K-Means_random.ipynb
```

---

## **7. Key Results / Performance**

* The project explores how the **K-Means** algorithm clusters randomly generated data into distinct groups.
* The results can be visualized through **scatter plots** where each cluster is color-coded.
* The performance of the algorithm is primarily assessed through visual inspection, highlighting the ability of **K-Means** to identify and separate clusters based on the data.

---

## **8. Screenshots / Sample Outputs**

* **Cluster Visualization**: Scatter plots showing the data points and their corresponding cluster assignments.
* **Centroid Markers**: The centers of each cluster are marked using a red "X" to visualize the clustering result.

> 💡 *Some interactive outputs (e.g., plots, widgets) may not display correctly on GitHub. If so, please view this notebook via [nbviewer.org](https://nbviewer.org) for full rendering.*

---

## **9. Additional Learnings / Reflections**

* Experimented with the **K-Means algorithm** using random data, gaining an understanding of its behavior with different numbers of clusters.
* The **visualization** approach is key for assessing clustering performance when the data is generated synthetically.
* The project also highlights the importance of tuning **K-Means parameters** like `n_init`, which controls the number of initializations for finding the best clustering solution.

---

## **👤 Author**

**Mehran Asgari**
**Email:** [imehranasgari@gmail.com](mailto:imehranasgari@gmail.com)
**GitHub:** [https://github.com/imehranasgari](https://github.com/imehranasgari)

---

## **📄 License**

This project is licensed under the **MIT License** – see the `LICENSE` file for details.

---

> 💡 *Some interactive outputs (e.g., plots, widgets) may not display correctly on GitHub. If so, please view this notebook via [nbviewer.org](https://nbviewer.org) for full rendering.*

---

