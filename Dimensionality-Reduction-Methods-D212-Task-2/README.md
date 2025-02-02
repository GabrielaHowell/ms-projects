# 🔬 Principal Component Analysis (PCA) for Medical Data

## 📌 Project Overview  
This project demonstrates the application of **Principal Component Analysis (PCA)** to identify key features in a medical dataset. The goal is to simplify complex data while retaining critical information. It includes:  
✅ A structured dataset 📊  
✅ An **interactive analysis** using PCA 🧠  
✅ A **comprehensive report** on data insights 📝  

---

<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:828/1*uSQooRdyLd2aZsadN9Sb0w.gif" alt="PCA Animation">
</p>

---

## 📂 Contents  
📄 **Written Report** – Detailed analysis and insights from the PCA process.  
📊 **PCA Results** – Key findings from the analysis, including variance explained by components.  
🗂️ **Dataset** – The cleaned dataset used for PCA (`PCA_medical.csv`).  

---

## 🗃️ Data Sources  
📌 **medical_clean** (provided by WGU)  
📌 **CDC_Dataset** (publicly available from the CDC)  

---

## ⚙️ Setup Instructions  

### 🧹 Data Preparation  
1️⃣ **Standardization:** The continuous variables used for PCA, such as **Age**, **Income**, **VitD_levels**, and **TotalCharge**, were standardized to ensure equal weight during analysis.  
2️⃣ **Data Set:** The cleaned data is available in the `PCA_medical.csv` file.

### 🔬 PCA Analysis  
1️⃣ Apply PCA to the standardized dataset using Python or R.  
2️⃣ Use the **Elbow Rule** and **Kaiser Criterion** to determine the number of components to retain.  

---

## 🎯 Analysis Insights  

### 🧮 Principal Components  
- **PC1**: 25.85% variance  
- **PC2**: 25.05% variance  

These two components capture **50.89%** of the total variance, providing a simplified view of the dataset.

### 📊 Scree Plot  
The **Elbow Rule** and **Kaiser Criterion** both suggest retaining the first two components.

---

## 📈 How PCA Helps Healthcare Decisions  
- PCA simplifies the dataset by reducing dimensionality while retaining crucial features.
- These findings can help healthcare organizations identify key factors affecting patient care and outcomes, guiding data-driven decision-making.

---

## 🎓 References  
- **Jolliffe, I. T., & Cadima, J.** (2016). Principal component analysis: A review and recent developments. Philosophical Transactions of the Royal Society A: Mathematical, Physical and Engineering Sciences, 374(2065), 20150202. DOI: 10.1098/rsta.2015.0202  
- **Shlens, J.** (2014). A tutorial on principal component analysis. arXiv preprint arXiv:1404.1100. Available at:

