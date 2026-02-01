# 🎓 Smart Student Performance Optimizer

A hybrid Machine Learning + Reinforcement Learning + Unsupervised Learning project that predicts student performance, clusters students by performance, and learns optimal study hours to maximize scores.

---

## 🚀 Features

- **Supervised Learning:** Linear Regression to predict final scores  
- **Unsupervised Learning:** K-Means clustering to categorize students  
- **Reinforcement Learning:** Q-Learning agent to optimize study hours  
- **Visualizations:** Seaborn and Matplotlib plots for EDA, clusters, and RL  
- **Dataset:** Synthetic student performance CSV generated for experimentation  

---

## 🧠 How It Works

1. **Dataset Generation** – 600 synthetic student records with study hours, sleep hours, attendance, previous grade, and final score  
2. **Exploratory Data Analysis (EDA)** – Visualizations to understand correlations and distributions  
3. **Unsupervised Learning (K-Means)** – Clusters students into performance groups (low, medium, high)  
4. **Supervised Learning (Linear Regression)** – Predicts final score from features  
5. **Reinforcement Learning (Q-Learning)** – Optimizes daily study hours to maximize predicted final score  
6. **Visualization of Results** – Q-table heatmap, RL optimization curve, cluster scatterplots  

---

## 📁 Project Structure

| File / Folder | Description |
|---------------|-------------|
| `student_performance.csv` | Synthetic dataset of student performance |
| `main.ipynb` | Colab/Jupyter notebook with ML, RL, and clustering code |
| `README.md` | Project documentation |

---

## ⚙️ Requirements

```bash
pip install pandas numpy scikit-learn seaborn matplotlib
