# Airlines On-time Performance Data Preparation for Tableau Visualization

## 📌 Project Overview
ThisThis project features a Python script designed to prepare a large Airlines On-time Performance dataset for visualization in Tableau Desktop (free version). The script concatenates multiple monthly CSV files into a unified dataset, samples it from over 14 million rows down to 1 million rows to fit Tableau’s non-subscription constraints, and exports the result as a CSV file. Additionally, it enriches the data by adding longitude and latitude coordinates for origin and destination cities, enabling geographical visualizations such as flight route maps.

- **Source:** [ U.S. Department of Transportation's On-Time Performance Data](https://transtats.bts.gov/Tables.asp?QO_VQ=EFD&QO_anzr=Nv4yv0r%FDb0-gvzr%FDcr4s14zn0pr%FDQn6n&QO_fu146_anzr=b0-gvzr)
## Features
- Concatenates monthly CSV files into a single dataset.
- Handles large datasets efficiently with pandas.
- Uploads the unified dataset to PostgreSQL using SQLAlchemy.
- Prepares data for downstream analysis - Concatenates monthly Airlines On-time Performance CSV files into a single dataset.
- Samples the dataset from 14+ million rows to 1 million rows for compatibility with Tableau Desktop.
- Adds geographical coordinates (longitude and latitude) for origin and destination cities.
- Exports the processed data as a CSV file for Tableau visualization.
## 🛠️ Technologies used
- **Programming Language:** Python.
- **Libraries:** Pandas,sklearn.model_selection
  Before running the script, ensure you have the following installed:
- Python 3.8+
- pandas (`pip install pandas`)
- Tableau Desktop (free version, no subscription required)
- Airlines On-time Performance dataset files (e.g., CSV format) with over 14 million rows
- (Optional) A CSV file or API with city coordinates for latitude/longitude mapping
## 🔧 Installation & Setup

### **Step 1: Clone the Repository**
```
git clone https://github.com/anieze-gad/airlines-performance-tableau
```

### **Step 2: Install Dependencies**
```
pip install -r requirements.txt
```

### **Step 3: Open the Jupyter Notebook**
```
jupyter notebook
```
Open prepare_tableau_airlines_data.py.ipynb to explore the analysis and forecasting results.

# Contributing
Feel free to fork this repository, submit pull requests, or suggest improvements via issues. Contributions to enhance functionality (e.g., error handling, additional file formats) are welcome!

# 👨‍💻 Author
### **Anieze Ifesinachi Gad**
📧 Email: aniezegad7@gmail.com 
🔗 GitHub: [anieze-gad](https://github.com/anieze-gad)

# 📜 License
This project is licensed under the MIT License.
