# 🙋 Introducing Myself

Hello, I'm **Yusuf Maryam Adeshewa**, passionate about **Data Science, Machine Learning, Data Analysis, Software Engineering, Artificial Intelligence, and Generative AI**.

## 👨‍🎓 About Me 💼🎒

I hold a **First Class Bachelor's Degree in Computer Science** from [Kwara State University](https://portal.kwasu.edu.ng/).

I have practical experience in **data analysis, business intelligence, machine learning, artificial intelligence, and software development** through professional internships, volunteer work, and personal projects.

I enjoy solving real-world problems with data and technology, learning new tools, and building practical solutions.

### 💼 Professional Experience

* [International Institute of Tropical Agriculture (IITA)](https://www.iita.org/) | **Business Intelligence & Data Intern**
* [Dala Innovation](https://dalainnovation.com/) | **Machine Learning Intern**
* [Kwara Tech](https://www.kwaratech.ng/) | **Frontend Developer Intern**

### 🤝 Volunteer Experience

* [Sec Concepts Network](https://trainwithsec.com/) | **Brand Manager**

📄 **[View My Resume/CV](https://drive.google.com/file/d/1N-kHSf8A33UtUSIF52satgSpcadetTqU/view?usp=sharing)**

---

# 📚 Projects

Below are some of my projects across **Machine Learning, Deep Learning, Natural Language Processing, Data Science, and Software Development**.

---

## 🧠 Deep Learning & Artificial Intelligence

### 🧠 Brain Tumor MRI Classification

A deep learning project focused on classifying brain MRI images into four categories:

* Glioma
* Meningioma
* Pituitary Tumor
* No Tumor

I compared three different approaches:

* **MobileNetV2 Transfer Learning**
* **Custom Convolutional Neural Network (CNN)**
* **SVM using MobileNetV2-extracted features**

### 📊 Results

| Model                         | Test Accuracy |
| ----------------------------- | ------------: |
| 🥇 SVM + MobileNetV2 Features |    **92.50%** |
| 🥈 MobileNetV2                |    **88.75%** |
| 🥉 Custom CNN                 |    **66.25%** |

One of the key findings was that combining **deep feature extraction with a traditional SVM classifier** produced better results than using MobileNetV2 or the custom CNN alone.

🔗 **[View Brain Tumor MRI Classification Project](https://github.com/Heryourmeekun/brain-tumor-mri-classification)**

**Tools:** `Python` `TensorFlow` `Keras` `MobileNetV2` `CNN` `Scikit-learn` `SVM` `NumPy` `Matplotlib`

---

### 📰 BBC News Text Classification

A Natural Language Processing project focused on automatically classifying BBC news articles into five categories:

* Business
* Entertainment
* Politics
* Sport
* Technology

I compared two deep learning approaches:

* **LSTM**
* **Transformer/BERT**

### 📊 Results

| Model | Test Accuracy |
| ----- | ------------: |
| BERT  |       **36%** |
| LSTM  |       **25%** |

Although the results were lower than expected, the project provided valuable insight into **NLP model behavior, class bias, fine-tuning, computational limitations, and model evaluation**.

🔗 **[View BBC News Text Classification Project](https://github.com/Heryourmeekun/BBC-News-Text-Classification)**

**Tools:** `Python` `TensorFlow` `Keras` `LSTM` `BERT` `NLP` `Scikit-learn`

### 📊 IITA Financial Analysis Dashboard – Power BI

An interactive Power BI dashboard developed during my Business Intelligence work at the International Institute of Tropical Agriculture (IITA).

The project analyses financial performance, revenue trends, customer behaviour, sales performance, and order activity through an interactive multi-page Power BI report.

**Key areas covered:**
- Financial and revenue analysis
- Customer insights and purchasing behaviour
- Order and sales analysis
- Monthly and daily sales trends
- Customer revenue and order analysis
- Payment status analysis
- Month-over-month growth analysis
- Interactive year and month filtering
- Customer search functionality
- KPI-driven dashboard design
- Interactive insights and recommendations
- Built-in report navigation and user instructions
- Reset filters functionality

**Tools & Technologies:**
`Power BI` `DAX` `Power Query` `Data Modelling` `Data Visualization` `Business Intelligence`

🔗 **[View Project on GitHub](https://github.com/Heryourmeekun/IITA-Financial-Analysis-PowerBI)**

---

# 🤖 Machine Learning & Data Science

### 🚢 Titanic Survival Prediction

A machine learning classification project that predicts passenger survival using the Titanic dataset.

The project involved:

* Data cleaning
* Feature engineering
* Exploratory data analysis
* Model training
* Model evaluation
* CatBoost classification

🏆 **Kaggle Score: 0.82057**

🔗 **[View Project](https://github.com/Heryourmeekun/Titanic_Survival_Prediction)**

**Tools:** `Python` `Pandas` `Scikit-learn` `CatBoost` `Jupyter Notebook`

---

# 🍳 Recipe Traffic Prediction

A machine-learning project that predicts whether a recipe is likely to generate high website traffic based on its nutritional information, category, and serving size.Goal: when the model predicts that a recipe will be high-traffic, it should be right at least 80% of the time (precision of 80% or more), while keeping low-traffic recipes off the featured spot.

## 🎯 Project Objectives

- Predict whether a recipe will generate high or low website traffic.
- Identify recipe characteristics associated with higher traffic.
- Compare multiple classification algorithms.
- Improve model precision through hyperparameter tuning.
- Translate model results into actionable business recommendations.

## 🛠️ Technologies Used

- **Python** — model development and data analysis
- **Pandas & NumPy** — data cleaning and manipulation
- **SciPy** — Yeo-Johnson transformation
- **Matplotlib & Seaborn** — exploratory data analysis and visualisation
- **Scikit-learn** — preprocessing, classification, evaluation, cross-validation, and hyperparameter tuning
- **LightGBM & XGBoost** — gradient-boosting classifiers

## 📊 Data Preparation and Exploration

The dataset initially contained 947 recipe records and eight columns, including nutritional information, recipe category, serving size, and the traffic label.

The preprocessing workflow included:

- Inspecting data types, missing values, and category distributions.
- Standardising recipe categories and cleaning serving-size values.
- Converting the target variable into a binary classification label.
- Handling missing nutritional values.
- Exploring numerical features and recipe categories to identify patterns associated with traffic.
- Applying the Yeo-Johnson transformation to address skewed numerical features.

After removing records with missing nutritional values, 895 records remained for modelling.

## 🤖 Machine-Learning Models

I implemented and compared seven classification algorithms:

1. Gaussian Naive Bayes
2. Logistic Regression
3. Decision Tree
4. Random Forest
5. Support Vector Machine (SVM)
6. LightGBM
7. XGBoost

The models were evaluated using an 80/20 train-test split. Evaluation metrics included accuracy, precision, recall, F1-score, and confusion matrices.

## 🔬 Hyperparameter Tuning and Results

Gaussian Naive Bayes was selected for further optimisation. I used `GridSearchCV` with three-fold cross-validation to tune its `var_smoothing` parameter, using precision as the optimisation metric.

**Key result:** Test precision improved from **0.88 to approximately 0.905** after tuning, with the best parameter value of `var_smoothing = 1e-11`.

This experiment demonstrated the value of systematic hyperparameter tuning and selecting evaluation metrics according to the project's business objectives.

## 💡 Business Insights

The exploratory analysis suggested that recipe category can help inform content decisions. The project identified Vegetable, Potato, and Pork recipes as categories associated with higher traffic, while Beverages tended to attract lower traffic in the analysed dataset.

These findings can help guide decisions about recipe promotion, although they should be validated against future website traffic data before being used as production rules.

## 📚 What I Learned

- Preparing real-world data for machine-learning workflows.
- Comparing multiple classification algorithms using consistent evaluation metrics.
- Applying cross-validation and hyperparameter optimisation.
- Interpreting confusion matrices and the trade-offs between precision and recall.
- Translating predictive results into practical business recommendations.

## 🔗 Project Repository

[**View the complete project on GitHub**](https://github.com/Heryourmeekun/Recipe_Traffic_Prediction)



🔗 **[View Project](https://github.com/Heryourmeekun/Recipe_Traffic_Prediction)**

**Tools:** `Python` `Pandas` `NumPy` `Scikit-learn` `XGBoost` `LightGBM` `CatBoost` `Matplotlib`

---

### 🚗 Don't Get Kicked

A machine learning classification project focused on predicting whether a vehicle purchase is likely to result in a problematic outcome.

The project involved data preprocessing, exploratory analysis, feature engineering, model training, and evaluation.

🔗 **[View Project](https://github.com/Heryourmeekun/Dont_Get_Kicked)**

**Tools:** `Python` `Pandas` `Scikit-learn` `LightGBM` `XGBoost` `Machine Learning`

---

# 💻 Software Development

### 🏡 Villa Agency

A frontend web development project for a real estate agency website.

The project demonstrates practical experience with:

* Responsive web design
* Website layouts
* User interfaces
* Frontend development
* HTML, CSS, and JavaScript

🔗 **[View Project](https://github.com/Heryourmeekun/Villa_Agency)**

**Tools:** `HTML` `CSS` `JavaScript`

---

### 📱 USSD Transaction

A JavaScript project that simulates a basic USSD transaction system.

The project demonstrates programming logic, user interaction, and transaction flow implementation.

🔗 **[View Project](https://github.com/Heryourmeekun/Ussd_Transaction)**

**Tools:** `HTML` `JavaScript`

---

# 📊 Business Intelligence & Data Analysis

I also have practical experience working with **Power BI, Microsoft Excel, data cleaning, data transformation, data visualization, and dashboard development**.

During my experience at **IITA**, I worked with agricultural and institutional datasets to create reports and dashboards that support data-driven decision-making.

### Areas of Experience

* Data cleaning and transformation
* Data analysis
* Power BI dashboard development
* KPI development
* Data visualization
* Business intelligence reporting
* Working with agricultural datasets

🔗 **Power BI projects and dashboards will be added here.**

---

# 🛠️ Technical Skills

### Programming

`Python` `C#` `SQL` `HTML` `CSS` `JavaScript`

### Machine Learning & AI

`Scikit-learn` `XGBoost` `LightGBM` `CatBoost` `TensorFlow` `Keras` `NLP` `LSTM` `BERT` `CNN` `MobileNetV2`

### Data Science

`Pandas` `NumPy` `SciPy` `Matplotlib` `Seaborn` `Plotly`

### Business Intelligence

`Power BI` `Microsoft Excel` `Power Query` `DAX`

### Databases

`MySQL` `PostgreSQL`

### Tools & Platforms

`Git` `GitHub` `Jupyter Notebook` `Google Colab` `Conda`

---

# 🎓 Education

### Kwara State University (KWASU)

**B.Sc. Computer Science — First Class Honours**

---

# 📜 Certifications

* **Data Scientist Professional** — DataCamp
* **Data Scientist Associate** — DataCamp
* **Intro to Machine Learning** — Kaggle

---

# 🌱 Currently Learning

I am continuously developing my skills in:

* Machine Learning
* Artificial Intelligence
* Natural Language Processing
* Data Science
* Data Analysis
* Power BI
* C#
* ASP.NET Core
* Database Development

I believe in **learning by building**, so I regularly work on practical projects to strengthen my skills and understanding.

---

# 👋 Connect With Me

### 💼 LinkedIn

[Connect with me on LinkedIn](https://linkedin.com/in/yusuf-maryam-0b8912273)

### 🐦 X

[Follow me on X](https://x.com/YusufMaryam495)

### 💻 GitHub

[Explore my GitHub repositories](https://github.com/Heryourmeekun)

---

⭐ **Thanks for visiting my portfolio!**

I'm always learning, building, and looking for opportunities to apply **data, AI, and software engineering** to real-world problems.
