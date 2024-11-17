# Bank Marketing Predictive Model & Power BI Dashboard  

This repository contains a comprehensive project that combines predictive analytics and interactive visualization to provide insights into a bank's marketing campaign performance. The project includes machine learning models for predicting customer subscription to term deposits and a Power BI dashboard for visualizing key trends and patterns.



## **Project Overview**  

The goal of this project is to predict whether a customer will subscribe to a term deposit based on demographic, economic, and previous campaign-related features. Additionally, an interactive Power BI dashboard is developed to visualize insights, helping stakeholders make data-driven decisions.  



## **Key Features**  

### **Power BI Dashboard**  
The dashboard offers:  
- **Customer Demographics**: Insights into age, education, marital status, and other demographic factors.  
- **Feature Analysis**: Key factors influencing deposit subscription decisions.  
- **Trend Analysis**: Visual representation of patterns from the marketing dataset.  

### **Machine Learning Models**  
The following algorithms were implemented to predict customer behavior:  
- Logistic Regression  
- Random Forest  
- Decision Tree  
- XGBoost  
- Support Vector Machine (SVM)  

The models are evaluated using metrics such as accuracy, precision, recall, and F1-score. **XGBoost** and **Random Forest** emerged as the top-performing models with the highest prediction accuracy.



## **Dataset**  

The dataset used is the [Bank Marketing Dataset](https://www.kaggle.com/datasets/krantiswalke/bankfullcsv) from the UCI Machine Learning Repository.  

### **Features**  
Key attributes include:  
- **Demographics**: Age, job, marital status, education, etc.  
- **Financial Status**: Loan, housing, and balance details.  
- **Campaign Information**: Contact type, day, and duration of the previous campaign.  
- **Outcome of Previous Campaign**: Indicators of past interactions with the customer.  

The target variable is **'y'**, indicating whether the customer subscribed to a term deposit (yes/no).  


## **Project Structure**  

```
.
├── data/                    # Dataset files  
├── models/                  # Saved model files  
├── notebooks/               # Jupyter notebooks for analysis and model training  
├── dashboard/               # Power BI dashboard file (.pbix)  
├── src/                     # Python scripts for data preprocessing and modeling  
├── README.md                # Project documentation  
└── LICENSE                  # MIT License  
```


## **Results**  

| **Model**                | **Accuracy** | **Precision** | **Recall** | **F1-Score** |  
|--------------------------|--------------|---------------|------------|--------------|  
| Logistic Regression      | XX%          | XX%           | XX%        | XX%          |  
| Decision Tree            | XX%          | XX%           | XX%        | XX%          |  
| Random Forest            | **YY%**      | **YY%**       | **YY%**    | **YY%**      |  
| XGBoost                  | **YY%**      | **YY%**       | **YY%**    | **YY%**      |  
| Support Vector Machine   | XX%          | XX%           | XX%        | XX%          |  

**Random Forest** and **XGBoost** outperformed other models, demonstrating strong predictive capabilities.  


## **Getting Started**  

### **Prerequisites**  
- Python 3.8 or higher  
- Power BI Desktop  
- Libraries: `pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`  

### **Installation**  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/bank-marketing-model  
   cd bank-marketing-model  
   ```  
2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Load the Power BI dashboard using Power BI Desktop.  

### **Usage**  
- Run the Python scripts in the `src/` folder for data preprocessing, model training, and evaluation.  
- Open the `.pbix` file in the `dashboard/` folder to interact with the Power BI dashboard.  


## **License**  

This project is licensed under the [MIT License](LICENSE).  


## **Contributing**  

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/your-username/bank-marketing-model/issues).  


## **Contact**  

For questions or feedback, please contact:  
**Youssef Moustafa**  
- [LinkedIn](https://www.linkedin.com/in/youssef-moustafa-b60807225)  
- [Portfolio](https://youssefmoustafa172.wixsite.com/youssef-moustafa)  
