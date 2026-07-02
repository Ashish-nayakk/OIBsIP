# 🌟 Oasis Infobyte – Data Science Internship

## 👋 Welcome to My Internship Portfolio!

> *"Learning is the only thing the mind never exhausts, never fears, and never regrets."* — Leonardo da Vinci

This repository contains all the projects I completed during my **Data Science Internship** at **Oasis Infobyte**. Each task is organized in its own folder with complete code, documentation, and visualizations.

---

## 📋 About This Internship

| Detail | Information |
|--------|-------------|
| **Intern** | Ashish Kumar Nayak |
| **Track** | Data Science |
| **Duration** | 1 Month (June 2026) |
| **Organization** | Oasis Infobyte |
| **Offer Letter** | OIB/J2/IP3357 |
| **Minimum Requirements** | Complete at least 3 tasks |

---

## 🚀 Completed Tasks

I successfully completed **3 Data Science projects** during this internship:

| # | Task | Folder | Tech Stack |
|---|------|--------|------------|
| **1** | Iris Flower Classification | [📁 View](DataScience-Task1-IrisClassification/) | Python, scikit-learn, pandas, seaborn |
| **2** | Car Price Prediction | [📁 View](DataScience-Task3-CarPricePrediction/) | Python, scikit-learn, pandas, feature engineering |
| **3** | Email Spam Detection | [📁 View](DataScience-Task4-SpamDetection/) | Python, NLTK, scikit-learn, NLP |

---

## 📊 Skills Demonstrated

| Skill Area | Technologies |
|------------|--------------|
| **Machine Learning** | Classification, Regression, NLP |
| **Data Analysis** | EDA, Feature Engineering, Data Visualization |
| **Model Evaluation** | Accuracy, Precision, Recall, F1-Score, Confusion Matrix |
| **Programming** | Python, Jupyter Notebook, pandas, numpy |
| **Version Control** | Git, GitHub |
| **NLP** | Text Preprocessing, TF-IDF, WordCloud |

---

## 🗂️ Repository Structure
OIBsIP/
├── DataScience-Task1-IrisClassification/
│ ├── iris_classification.ipynb
│ ├── README.md
│ ├── results_summary.txt
│ └── visualizations/
│
├── DataScience-Task3-CarPricePrediction/
│ ├── car_price_prediction.ipynb
│ ├── README.md
│ ├── car_data.csv
│ ├── results_summary.txt
│ └── visualizations/
│
├── DataScience-Task4-SpamDetection/
│ ├── spam_detection.ipynb
│ ├── README.md
│ ├── spam.csv
│ ├── results_summary.txt
│ └── visualizations/
│
├── README.md # This file
├── requirements.txt # Python dependencies
└── .gitignore # Git ignore rules

text

---

## 📊 Task 1 – Iris Flower Classification

### Project Overview
Build a machine learning model to classify iris flowers into three species (Setosa, Versicolor, Virginica) based on their physical measurements.

**Best Model:** Logistic Regression (100% accuracy)

### Visualizations

#### Pairplot – Feature Relationships
![Pairplot](DataScience-Task1-IrisClassification/visualizations/pairplot.png)

#### Boxplots – Feature Distribution by Species
![Boxplots](DataScience-Task1-IrisClassification/visualizations/boxplots.png)

#### Confusion Matrices – All Models
![Confusion Matrices](DataScience-Task1-IrisClassification/visualizations/confusion_matrices.png)

[📂 View Full Project →](DataScience-Task1-IrisClassification/)

---

## 🚗 Task 3 – Car Price Prediction

### Project Overview
Build a regression model to predict the selling price of used cars based on features like brand, fuel type, transmission, and car age.

**Best Model:** Random Forest Regressor

### Visualizations

#### Price Distribution
![Price Distribution](DataScience-Task3-CarPricePrediction/visualizations/price_distribution.png)

#### Price vs Fuel Type
![Price vs Fuel](DataScience-Task3-CarPricePrediction/visualizations/price_vs_fuel.png)

#### Price vs Transmission
![Price vs Transmission](DataScience-Task3-CarPricePrediction/visualizations/price_vs_transmission.png)

#### Price vs Car Age
![Price vs Car Age](DataScience-Task3-CarPricePrediction/visualizations/price_vs_age.png)

#### Price vs Kilometers Driven
![Price vs KM](DataScience-Task3-CarPricePrediction/visualizations/price_vs_km.png)

#### Correlation Heatmap
![Correlation Heatmap](DataScience-Task3-CarPricePrediction/visualizations/correlation_heatmap.png)

#### Predictions vs Actual
![Predictions vs Actual](DataScience-Task3-CarPricePrediction/visualizations/predictions_vs_actual.png)

#### Feature Importance
![Feature Importance](DataScience-Task3-CarPricePrediction/visualizations/feature_importance.png)

[📂 View Full Project →](DataScience-Task3-CarPricePrediction/)

---

## 📧 Task 4 – Email Spam Detection

### Project Overview
Build an NLP-based classifier to distinguish spam messages from legitimate (ham) messages using the SMS Spam Collection dataset.

**Best Model:** Logistic Regression

### Visualizations

#### Class Distribution
![Class Distribution](DataScience-Task4-SpamDetection/visualizations/class_distribution.png)

#### Class Distribution Pie Chart
![Class Distribution Pie](DataScience-Task4-SpamDetection/visualizations/class_distribution_pie.png)

#### Spam WordCloud
![Spam WordCloud](DataScience-Task4-SpamDetection/visualizations/spam_wordcloud.png)

#### Ham WordCloud
![Ham WordCloud](DataScience-Task4-SpamDetection/visualizations/ham_wordcloud.png)

#### Confusion Matrices – All Models
![Confusion Matrices](DataScience-Task4-SpamDetection/visualizations/confusion_matrices.png)

[📂 View Full Project →](DataScience-Task4-SpamDetection/)

---

## 📈 Model Performance Summary

| Task | Best Model | Accuracy | Key Metric |
|------|------------|----------|------------|
| **Iris Classification** | Logistic Regression | 100% | Accuracy |
| **Car Price Prediction** | Random Forest | - | R² Score |
| **Spam Detection** | Logistic Regression | ~98% | F1-Score |

---

## 🎯 Key Learnings

During this internship, I learned and applied:

1. **End-to-End Data Science Workflow** – From data cleaning to model deployment
2. **Feature Engineering** – Extracting meaningful features from raw data
3. **Natural Language Processing** – Text preprocessing and classification
4. **Model Evaluation** – Understanding when to use accuracy vs. precision vs. recall
5. **Git & GitHub** – Version control for collaborative projects
6. **Documentation** – Writing clear READMEs and project summaries

---

## 🛠️ How to Run These Projects

### Prerequisites
- Python 3.7+
- pip (Python package manager)

### Setup Instructions

1. **Clone the repository:**
```bash
git clone https://github.com/Ashish-nayakk/OIBsIP.git
cd OIBsIP
Create a virtual environment:

bash
python -m venv venv
source venv/bin/activate  # On Windows: .\venv\Scripts\Activate.ps1
Install dependencies:

bash
pip install -r requirements.txt
Navigate to any task folder:

bash
cd DataScience-Task1-IrisClassification/
Run Jupyter Notebook:

bash
jupyter notebook
📦 Dependencies
All projects share these dependencies:

text
numpy>=1.21.0
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=1.0.0
jupyter>=1.0.0
nltk>=3.6.0
wordcloud>=1.8.0
Install all with: pip install -r requirements.txt

🔗 Useful Links
Resource	Link
Internship Portal	taplink.cc/oasisinfobyte.com
Oasis Infobyte	Website
Oasis Infobyte on LinkedIn	LinkedIn
My GitHub	github.com/Ashish-nayakk
My LinkedIn	linkedin.com/in/ashish-kumar-nayak-2ba779385
📸 Demo Videos
Each task has a corresponding demo video posted on LinkedIn. Watch the walkthroughs to see the projects in action:

Task	LinkedIn Post	Status
Task 1 – Iris Classification	[🔗 Watch Demo]	(Add your LinkedIn link here)
Task 3 – Car Price Prediction	[🔗 Watch Demo]	(Add your LinkedIn link here)
Task 4 – Email Spam Detection	[🔗 Watch Demo]	(Add your LinkedIn link here)
🏆 Acknowledgments
I would like to express my sincere gratitude to:

Oasis Infobyte – For providing this valuable learning opportunity

The Evaluation Team – For their guidance and feedback

The Open-Source Community – For the amazing libraries and tools used in these projects

📜 License
This repository is for educational purposes as part of the Oasis Infobyte Internship Program. All code and documentation are shared to demonstrate my learning journey.

👨‍💻 Author
Ashish Kumar Nayak
Data Science Intern – Oasis Infobyte
GitHub | LinkedIn

🌟 Final Thoughts
This internship has been an incredible journey of learning, building, and growing as a data scientist. From classification to regression to natural language processing, I've gained hands-on experience with real-world datasets and machine learning workflows.

Thank you for visiting my portfolio! 🚀

Happy Learning! 📊

text

---

## 📝 Quick Steps to Update

1. **Copy** everything inside the code block above
2. **Open** your root `README.md` file in VS Code
3. **Select all** (`Ctrl + A`) and **paste** (`Ctrl + V`)
4. **Save** (`Ctrl + S`)
5. **Commit and push**:

```powershell
git add README.md
git commit -m "Updated main README with all task visualizations"
git push
