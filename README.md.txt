# Maternal Health Data Analysis
This project analyzes maternal health data based on clinical visits.
The aim of this project is to analyze data to gain insights and predict maternal death category prediction.

## Project Structure
The project structure is described below:
data/:This folder contains dataset. It was manually collected from a public website.
notebooks/:This contains .ipynb files.

## Project Environment
The project uses numpy, pandas, matplotlib, seaborn, ipykernel packages.

## Results
- The distribution of most of the variables are right tailed. 
- Weak correlation.
- Class imbalance present.
- RandomForestClassifier, KNeighborsClassifier and xgboost were used to model data.
- Accuracy,precision, recall and f1-score of RandomForestClassifier are 0.68, 0.75, 0.76 and 0.75 respectively,for K nearest neighobres      these metrics are 0.71, 0.70, 0.67 and 0.67 respectively and for XGBoost the value of these metrics are 0.73, 0.77, 0.44 and 0.56          respectively. 
- XGBoost is the best model in terms of accuracy and precision. However, it's recall and f1-score are too poor. 
- RandomForestClassifier the best model in terms of recall and f1-score.
- Though RandomForestClassifier model was tuned(poor performance on recall and f1-score), default model performed better than that.
- Taking account into all metrics, RandomForestClassifier is the best model.


# Summary Points
1. Clone the repository
```bash
git clone https://github.com/sanjida-akhtar/maternal-health-analysis
cd maternal-health-analysis
2. Install dependencies
pip install -r requirement.txt
This will install numpy, pandas, matplotlib, seaborn, jupyter, ipykernel
3. Launch the notebook
jupyter notebook notebooks/maternal_health_analysis.ipynb
or just run jupyter notebook
Then open the notebook file from the UI.

## License & Usage
This project is provided for **educational and demonstration purposes only**.
**© 2025 Sanjida Akhtar. All rights reserved.**
> This repository is not open source. No license is provided.
> A license may be added in the future after the modificaiton of the project.
