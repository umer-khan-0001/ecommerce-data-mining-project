# E-commerce Data Mining Project

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A comprehensive data mining project analyzing UCI Online Retail dataset to extract customer behavior insights and build predictive models using Python and machine learning algorithms.

## 📊 Project Overview

This project implements various data mining techniques on real-world e-commerce transaction data to:
- Analyze customer purchasing patterns
- Segment customers using clustering algorithms
- Discover association rules for market basket analysis
- Build predictive models for customer behavior classification

## 🎯 Key Features

- **Data Preprocessing**: Comprehensive data cleaning and feature engineering
- **Customer Segmentation**: K-means and hierarchical clustering analysis
- **Market Basket Analysis**: Association rule mining using Apriori algorithm
- **Predictive Modeling**: Naive Bayes and Support Vector Machine classifiers
- **Statistical Analysis**: Similarity and dissimilarity matrices
- **Visualization**: Interactive plots and charts for data insights

## 📁 Dataset

**Source**: [UCI Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail)

**Description**: Real-world retail transaction data containing:
- **Records**: 541,909 transactions
- **Attributes**: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country
- **Time Period**: December 2010 - December 2011
- **Geography**: UK-based online retail store

## 🛠️ Technologies Used

- **Programming Language**: Python 3.8+
- **Data Analysis**: Pandas, NumPy
- **Machine Learning**: Scikit-learn
- **Visualization**: Matplotlib, Seaborn
- **Association Rules**: mlxtend
- **Development Environment**: Jupyter Notebook

## 📋 Project Structure

```
├── Smart_Retail_Analytics.ipynb    # Main analysis notebook
├── Online Retail.xlsx              # Dataset file
├── Smart_Retail_Analytics.html     # HTML export of notebook
├── DM_finalproject_FA21-BDS-020.pdf # Project report
├── final lab project.txt           # Project requirements
├── README.md                       # Project documentation
├── LICENSE                         # MIT License
└── .gitignore                      # Git ignore rules
```

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.8 or higher
Jupyter Notebook
Required Python packages (see requirements below)
```

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/umer-khan-0001/ecommerce-data-mining-project.git
   cd ecommerce-data-mining-project
   ```

2. **Install required packages**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter mlxtend openpyxl
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open the main notebook**
   - Navigate to `Smart_Retail_Analytics.ipynb`
   - Run all cells to reproduce the analysis

## 📈 Analysis Workflow

### 1. Data Ingestion & Preprocessing
- Load and explore the dataset
- Handle missing values and outliers
- Remove cancelled transactions
- Engineer new features (TotalAmount, Recency, Frequency, Monetary)

### 2. Similarity & Dissimilarity Analysis
- Calculate customer similarity matrices
- Implement distance metrics
- Visualize customer relationships

### 3. Clustering Analysis
- K-means clustering for customer segmentation
- Hierarchical clustering analysis
- Cluster validation and interpretation

### 4. Association Rule Mining
- Market basket analysis
- Frequent itemset generation
- Rule extraction and evaluation (support, confidence, lift)

### 5. Classification Models
- **Naive Bayes**: Customer behavior prediction
- **Support Vector Machine**: Advanced classification
- Model evaluation and comparison

### 6. Results & Business Insights
- Customer segment profiles
- Product recommendation strategies
- Business recommendations

## 📊 Key Results

- **Customer Segments**: Identified 4 distinct customer groups
- **Association Rules**: Discovered 50+ meaningful product associations
- **Model Performance**: Achieved 85%+ accuracy in customer classification
- **Business Value**: Actionable insights for marketing strategies

## 👨‍💻 Author

**Umer Ahmed**


## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

- GitHub: [@umer-khan-0001](https://github.com/umer-khan-0001)
- Project Link: [https://github.com/umer-khan-0001/ecommerce-data-mining-project](https://github.com/umer-khan-0001/ecommerce-data-mining-project)

## 🙏 Acknowledgments

- UCI Machine Learning Repository for the dataset
- Scikit-learn community for machine learning tools
- Python data science community for excellent libraries

---

⭐ **If you found this project helpful, please consider giving it a star!** ⭐
