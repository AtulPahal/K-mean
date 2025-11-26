# K-Means Customer Segmentation

A machine learning project that performs customer segmentation using K-Means clustering on mall customer data. This project analyzes customer behavior patterns based on annual income and spending scores to identify distinct customer groups.

## 📋 Project Overview

This project uses unsupervised learning (K-Means clustering) to segment mall customers into different groups based on their purchasing behavior. The analysis helps identify customer segments that can be targeted with specific marketing strategies.

## 🎯 Features

- **Data Analysis**: Exploratory data analysis of customer demographics and spending patterns
- **K-Means Clustering**: Implementation of K-Means algorithm to identify customer segments
- **Elbow Method**: Optimal cluster number selection using the elbow method
- **Data Visualization**: 
  - Distribution plots for key features
  - Pair plots showing relationships between variables
  - Scatter plots for cluster visualization
  - Cluster centroids visualization

## 📊 Dataset

The project uses the **Mall Customers Dataset** which contains:
- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## 🛠️ Requirements

### Python Libraries

- `numpy` - Numerical computing
- `pandas` - Data manipulation and analysis
- `matplotlib` - Data visualization
- `seaborn` - Statistical data visualization
- `plotly` - Interactive visualizations
- `scikit-learn` - Machine learning algorithms
- `xlrd` - Excel file reading support

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/AtulPahal/K-mean.git
   cd k-mean
   ```

2. **Install required packages**
   ```bash
   pip install numpy pandas matplotlib seaborn plotly scikit-learn xlrd
   ```

   Or install from requirements file (if available):
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage

### Running the Notebook

1. Open `main.ipynb` in Jupyter Notebook or JupyterLab
   ```bash
   jupyter notebook main.ipynb
   ```

2. Run all cells sequentially to:
   - Load and explore the dataset
   - Perform data analysis and visualization
   - Apply K-Means clustering
   - Visualize the results

### Running on Google Colab

1. Upload the notebook to Google Colab
2. Upload the `Data_Set/Mall_Customers.xls` file to your Colab session
3. Update the file path in the notebook if needed
4. Run all cells

### Running on GitHub

You can view and run this notebook directly on GitHub using:
- **Jupyter Notebook Viewer**: Paste the GitHub raw URL
- **nbviewer**: `https://nbviewer.org/github/<your-username>/<repo-name>/blob/main/main.ipynb`
- **Binder**: Create a `requirements.txt` and add a Binder badge (see below)

## 📈 Results

The K-Means algorithm identifies **5 distinct customer clusters**:
- **Cluster 1**: Low income, low spending
- **Cluster 2**: Low income, high spending
- **Cluster 3**: Medium income, medium spending
- **Cluster 4**: High income, low spending
- **Cluster 5**: High income, high spending

## 📁 Project Structure

```
k-mean/
│
├── main.ipynb              # Main Jupyter notebook with analysis
├── Data_Set/
│   └── Mall_Customers.xls  # Customer dataset
└── README.md               # Project documentation
```

## 🔧 Configuration

The notebook uses the following K-Means parameters:
- **Number of clusters**: 5 (determined by elbow method)
- **Initialization**: k-means++
- **Random state**: 42 (for reproducibility)

## 📝 Notes

- The dataset file (`Mall_Customers.xls`) needs to be in the `Data_Set/` directory
- Make sure to install `xlrd` package to read Excel files
- The random state is set to 42 for reproducible results

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

Atul

---

⭐ If you find this project helpful, please give it a star!

