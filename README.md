# **NFT Sales Analysis & Forecasting**  

## **Overview**  
This project focuses on analyzing and forecasting **NFT sales trends** using time-series analysis techniques. The dataset is sourced from **OpenSea NFT Sales (2019-2021)** and includes various attributes related to NFT transactions. The project involves:  

- **Handling missing values** using different techniques.  
- **Exploratory Data Analysis (EDA)** to identify patterns and trends.  
- **Time-series forecasting** using **AutoCorrelation Function (ACF)** and other methods.  

## **Dataset**  
The dataset used in this project is **OpenSea NFT Sales (2019-2021)**, obtained from **Kaggle**. It includes transaction details such as:  
- **NFT name**  
- **Sale price**  
- **Transaction date**  
- **Seller & buyer information**  

## **Technologies Used**  
🔹 **Python**  
🔹 **Pandas & NumPy** (Data handling)  
🔹 **Matplotlib & Seaborn** (Data visualization)  
🔹 **Statsmodels** (Time-series analysis)  
🔹 **ACF (AutoCorrelation Function)**  

## **Installation & Setup**  

### **Step 1: Clone the Repository**  
```bash
git clone https://github.com/yourusername/NFT-Sales-Analysis.git
cd NFT-Sales-Analysis
```

### **Step 2: Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **Step 3: Download Dataset from Kaggle**  
```bash
! pip install kaggle
! mkdir ~/.kaggle
! cp kaggle.json ~/.kaggle/
! chmod 600 ~/.kaggle/kaggle.json
! kaggle datasets download -d bryanw26/opensea-nft-sales-2019-2021
! unzip opensea-nft-sales-2019-2021.zip
```

## **How to Run**  
1. Open the **FM_proj.ipynb** notebook in **Jupyter Notebook** or **Kaggle**.  
2. Execute the cells to clean, analyze, and visualize the dataset.  
3. Apply **time-series forecasting** methods to predict NFT sales trends.  

## **Results & Insights**  
📌 Identified missing data patterns and handled them effectively.  
📌 Visualized **historical NFT sales trends** from 2019-2021.  
📌 Used **AutoCorrelation Function (ACF)** to analyze time-series dependencies.  

## **Future Work**  
🚀 Implement **advanced forecasting models** (e.g., ARIMA, LSTM).  
🚀 Expand analysis to **NFT metadata** for deeper insights.  
🚀 Deploy findings as an **interactive dashboard**.  

## **Acknowledgments**  
📌 Dataset sourced from **Kaggle (OpenSea NFT Sales 2019-2021)**.  
📌 Inspired by **blockchain and NFT market trends**.  

---
