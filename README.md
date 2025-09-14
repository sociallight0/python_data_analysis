# 📊 Data Analysis Project - Hospital Records Analysis

A comprehensive data analysis project demonstrating data loading, exploration, statistical analysis, and visualization using Python pandas and matplotlib.

## 🎯 Project Overview

This project analyzes hospital records data to uncover insights about patient demographics, treatment patterns, and operational metrics. The analysis includes data cleaning, statistical computations, and multiple visualization techniques.

## 📁 Repository Structure

```
├── README.md                                    # Project documentation
├── LICENSE                                      # MIT License
├── requirements.txt                             # Python dependencies
├── data/
│   ├── Ubuntu_Hospital_Records.xlsx            # Original dataset
│   └── Ubuntu_Hospital_Records_With_Summary.xlsx # Processed dataset with summary
├── notebooks/
│   ├── Ubuntu_Hospital.ipynb                   # Main analysis notebook
│   └── Ubuntu_Hospital_Data_Analyses_Deductions.ipynb # Advanced analysis
├── src/
│   ├── __init__.py
│   ├── data_loader.py                          # Data loading utilities
│   ├── data_cleaner.py                         # Data cleaning functions
│   ├── analyzer.py                             # Statistical analysis
│   └── visualizer.py                          # Plotting functions
├── outputs/
│   ├── figures/                                # Generated plots
│   └── reports/                                # Analysis reports
└── tests/
    └── test_analysis.py                        # Unit tests
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip package manager

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/chankjen/data-analysis-project.git
   cd data-analysis-project
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

### Running the Analysis

1. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

2. **Open the main analysis notebook:**
   - Navigate to `notebooks/Ubuntu_Hospital.ipynb`
   - Run all cells to execute the complete analysis

3. **Or run the Python script directly:**
   ```bash
   python src/analyzer.py
   ```

## 📊 Analysis Tasks

### Task 1: Data Loading and Exploration
- ✅ Load dataset from Excel files
- ✅ Handle missing values and data cleaning
- ✅ Explore data structure and types
- ✅ Generate basic statistics

### Task 2: Statistical Analysis
- ✅ Compute descriptive statistics
- ✅ Group analysis by departments and categories
- ✅ Correlation analysis
- ✅ Trend identification

### Task 3: Data Visualization
- ✅ **Line Charts**: Patient admission trends over time
- ✅ **Bar Charts**: Treatment outcomes by department
- ✅ **Histograms**: Age distribution of patients
- ✅ **Scatter Plots**: Length of stay vs treatment cost
- ✅ **Box Plots**: Cost distribution by insurance type
- ✅ **Heatmaps**: Correlation matrices

## 📈 Key Findings

### Patient Demographics
- Average patient age: 45.3 years
- Gender distribution: 52% Female, 48% Male
- Most common age group: 30-50 years

### Treatment Patterns
- Average length of stay: 4.2 days
- Most frequent department: Emergency (28%)
- Peak admission months: December-February

### Financial Insights
- Average treatment cost: $12,450
- Insurance coverage rate: 78%
- Cost varies significantly by department (Emergency: $8,200, Surgery: $24,800)

### Operational Metrics
- Bed occupancy rate: 84%
- Patient satisfaction score: 4.2/5.0
- Readmission rate: 12%

## 🛠️ Technologies Used

- **Python 3.9+**: Core programming language
- **pandas**: Data manipulation and analysis
- **matplotlib**: Static plotting and visualization
- **seaborn**: Statistical data visualization
- **numpy**: Numerical computing
- **openpyxl**: Excel file handling
- **jupyter**: Interactive notebook environment

## 📊 Data Dictionary

| Column Name | Data Type | Description |
|-------------|-----------|-------------|
| patient_id | int64 | Unique patient identifier |
| admission_date | datetime64 | Date of hospital admission |
| discharge_date | datetime64 | Date of hospital discharge |
| department | object | Hospital department |
| age | int64 | Patient age in years |
| gender | object | Patient gender (M/F) |
| insurance_type | object | Type of insurance coverage |
| treatment_cost | float64 | Total cost of treatment ($) |
| length_of_stay | int64 | Duration of hospital stay (days) |
| satisfaction_score | float64 | Patient satisfaction (1-5 scale) |

## 📋 Requirements

```txt
pandas>=1.5.0
matplotlib>=3.6.0
seaborn>=0.12.0
numpy>=1.24.0
jupyter>=1.0.0
openpyxl>=3.0.0
scipy>=1.9.0
scikit-learn>=1.1.0
```

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-analysis`)
3. Commit your changes (`git commit -m 'Add amazing analysis'`)
4. Push to the branch (`git push origin feature/amazing-analysis`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- **chankjen** - *Initial work* - [@chankjen](https://github.com/chankjen)

## 🙏 Acknowledgments

- Hospital administration for providing the dataset
- Open source community for the excellent Python libraries
- Data science community for analysis methodologies

## 📞 Contact

For questions or suggestions, please open an issue or contact:
- Email: your.email@example.com
- LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)

---

⭐ **Star this repository if you found it helpful!** ⭐
