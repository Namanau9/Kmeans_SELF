# K-Means Clustering on the Iris Dataset (Flask Web App)

CHECK THE PROJECT ON :
https://kmeans-self.onrender.com/

This project is a Flask web application that performs **K-Means clustering** on the famous **Iris dataset** and visualizes the results using **2D and 3D scatter plots**. The app allows users to view the clustering results interactively.

## 🚀 Features

- Uses **K-Means clustering** to classify iris flowers into three clusters.
- **2D scatter plot** visualization using Matplotlib & Seaborn.
- **3D interactive scatter plot** using Plotly.
- Simple **Flask web interface** to display results.

---

## 📂 Project Structure

```
/your_project
│── app.py               # Flask application
│── kmeans_iris.py       # K-Means clustering logic & plotting functions
│── requirements.txt     # Dependencies for the project
│── README.md            # Project documentation
│── templates/
│   └── index.html       # HTML file for rendering the web page
│── static/
│   ├── plot_2d.png      # 2D scatter plot (generated)
│   └── plot_3d.html     # 3D interactive plot (generated)
```

---

## Explanation
###🔷 What is K-Means?
K-Means is a popular unsupervised machine learning algorithm used for clustering data into groups based on similarity.

###🔹 How It Works:
Choose the number of clusters k.

Randomly initialize k cluster centroids.

Assign each data point to the nearest centroid.

Recalculate centroids as the mean of all points assigned to that cluster.

Repeat steps 3–4 until centroids stop changing significantly (i.e., convergence).

###🔷 What is Clustering?
Clustering is a technique used to group similar data points together without using any predefined labels.

Real-life Examples:
Grouping customers based on buying behavior.

Image segmentation.

Document categorization.

###🔷 Iris Dataset
A famous dataset used for classification and clustering tasks.

Features:
Sepal length (cm)

Sepal width (cm)

Petal length (cm)

Petal width (cm)

Target (for reference):
Setosa

Versicolor

Virginica

###🔷 Standardization / Feature Scaling
The StandardScaler standardizes features by removing the mean and scaling to unit variance. It helps K-Means work better because clustering is distance-based (Euclidean), and scale matters.


###🔷 Data Visualization
📊 matplotlib & seaborn:
Used for static plots like 2D scatter plots.

🌐 plotly:
Used for interactive 3D plots.


## 🖼️ Screenshots

### **2D Scatter Plot**
![plot_2d](https://github.com/user-attachments/assets/ddb1e775-4946-4880-a850-3ba9cd58d8de)




### **3D Scatter Plot (Interactive)**
![newplot](https://github.com/user-attachments/assets/f3b12e6d-2ec2-494d-9186-d488b27a5906)


---

## 🛠️ Technologies Used

- **Flask** - Web framework
- **NumPy & Pandas** - Data processing
- **Matplotlib & Seaborn** - 2D visualization
- **Plotly** - 3D interactive visualization
- **Scikit-learn** - Machine learning (K-Means clustering)

---

## 🤝 Contributing

Feel free to **fork this repo**, make improvements, and submit a **pull request**!

---

## 📝 License

This project is open-source and available under the **MIT License**.

---

## ⭐ Star This Repo!

If you found this project useful, **give it a star ⭐** to show your support! 😊

