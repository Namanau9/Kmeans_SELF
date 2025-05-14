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

## 📚 Key Concepts

### 🔷 What is K-Means?

**K-Means** is a popular **unsupervised machine learning algorithm** used to group data into clusters based on similarity.

#### 🔹 How It Works:
1. Choose the number of clusters `k`.
2. Randomly initialize `k` cluster centroids.
3. Assign each data point to the nearest centroid.
4. Recalculate centroids based on current cluster members.
5. Repeat steps 3–4 until convergence.

---

### 🔷 What is Clustering?

Clustering is a technique used to **group similar data points** without predefined labels.

**Real-life examples:**
- Grouping customers by purchase patterns
- Image segmentation
- Document categorization

---

### 🔷 Iris Dataset

A well-known dataset in machine learning, consisting of measurements for 150 iris flowers from 3 species.

**Features:**
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

**Target Classes (for reference only):**
- Setosa
- Versicolor
- Virginica

---

### 🔷 Standardization / Feature Scaling

We use `StandardScaler` to scale features by removing the mean and scaling to unit variance.  
This is crucial for distance-based models like K-Means to ensure fair clustering.

---

### 🔷 Data Visualization

- 📊 **Matplotlib & Seaborn**: For static 2D scatter plots.
- 🌐 **Plotly**: For dynamic and interactive 3D plots.

---


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

