# Rainfall Prediction Classifier

**Final Exam Project for Machine Learning Certification**

A machine learning project that builds and evaluates classifiers to predict tomorrow's rainfall using Australian weather data from 2008-2017.

## 📌 About This Project

**`main.ipynb`** contains my complete machine learning analysis for my final certification exam, including:
- Data exploration and analysis
- Feature engineering and preprocessing
- Building and comparing multiple classifiers
- Hyperparameter tuning with GridSearchCV
- Model evaluation and performance metrics

The repository structure and supporting files (like this README, requirements.txt, etc.) are organized to present this work professionally on GitHub.

## 🎯 My Analysis

The notebook demonstrates:
- Real-world data exploration using Pandas
- Feature engineering techniques
- Pipeline creation with Scikit-learn
- Cross-validation and hyperparameter optimization
- Classification model evaluation (Logistic Regression, Random Forest)
- Performance visualization and interpretation

## Dataset

- **Source**: [Kaggle - Weather Dataset (Rattle Package)](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package/)
- **Original Data**: Australian Government's Bureau of Meteorology
- **Time Period**: 2008-2017
- **Features**: 22 weather observations
- **Target**: RainTomorrow (binary classification)

## Getting Started

### Requirements
- Python 3.7+
- Jupyter Notebook

### Installation

```bash
pip install -r requirements.txt
```

### Running the Analysis

```bash
jupyter notebook main.ipynb
```

## Project Structure

```
weathering-with-you/
├── main.ipynb              # My complete analysis and models
├── data/
│   ├── raw/               # Original dataset location
│   └── processed/         # Processed data
├── outputs/               # Generated visualizations and results
├── src/                   # Custom utilities (if developed)
├── README.md              # This file
├── requirements.txt       # Python dependencies
└── LICENSE                # MIT License
```

## Technologies Used

- **Data**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn  
- **Machine Learning**: Scikit-learn
- **Notebook**: Jupyter

## Key Learnings

This project showcases my ability to:
- Work with real-world, messy datasets
- Build end-to-end machine learning pipelines
- Implement model selection and validation strategies
- Interpret and communicate results effectively

## License

MIT License - See LICENSE file for details

---

**This is my final exam work demonstrating ML skills.**
