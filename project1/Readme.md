# 🚢 Titanic Survival Prediction

Welcome to the **Titanic Survival Prediction** project! 🎉  
This project brings a thrilling and historical journey aboard the Titanic, using data science and machine learning to predict the survival chances of passengers. Can we predict who survives based on various factors like age, gender, class, and more? Let’s dive into this fascinating analysis!


[Dataset]
---

## 🌟 Project Overview

In this project, we tackle one of the most famous tragedies in history—the sinking of the Titanic. The main objective is to build a machine learning model that predicts whether a passenger survived or not based on key factors such as their age, gender, class, ticket fare, and other attributes. It’s a deep dive into data exploration, feature engineering, and predictive modeling!

**Key Steps:**
1. **Exploring the Data**: Uncover the patterns in the Titanic dataset that can influence survival chances.
2. **Cleaning and Preparing Data**: Handle missing values, encode categorical data, and prepare the data for analysis.
3. **Feature Engineering**: Create new features that can enhance the predictive model's accuracy.
4. **Model Building and Evaluation**: Apply machine learning algorithms to predict survival and assess model performance.

---

## 🔍 Project Workflow

1. **Exploratory Data Analysis (EDA)**  
   Dive deep into the dataset, understand trends, and uncover insights about the passengers.  
   - How did **gender**, **age**, and **class** affect survival rates?
   - What were the common characteristics of those who survived versus those who didn’t?

2. **Data Cleaning**  
   - Handle missing values (e.g., impute missing **age** or **embarked** data).
   - Convert **categorical variables** like `Sex`, `Embarked`, and `Pclass` to numerical values so we can feed them into machine learning models.

3. **Feature Engineering**  
   - Create new features like **family size** (combining `SibSp` and `Parch`), which could play a significant role in survival.
   - Normalize continuous variables to improve model performance.

4. **Building Predictive Models**  
   We build models and evaluate their accuracy using:
   - **Logistic Regression** for basic classification.
   - **Decision Trees** for intuitive decision rules.
   - **Random Forests** to improve performance and handle overfitting.
   
   We also evaluate the models' performance using **accuracy**, **precision**, **recall**, and **F1-score**.

---

## 🔥 Key Insights from the Analysis

- **Gender Impact**: Female passengers had a **significantly higher survival rate**—the **"women and children first"** principle holds true here!
- **Class Impact**: First-class passengers were more likely to survive than those traveling in third class, highlighting the disparity in treatment during the disaster.
- **Family Size**: Passengers traveling alone had a lower survival rate. **Families** had a better chance of survival—surviving together was key!

---

## 🛠️ Technologies Used

- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Development Environment**: Jupyter Notebook

These tools are used to clean, analyze, and build machine learning models that predict the survival of Titanic passengers.

---

## 🚀 How to Run the Project

Ready to explore the Titanic disaster data and test the models? Follow these steps:

1. **Clone the Repository**  
   Clone this repository to your local machine:  
   ```bash
   git clone https://github.com/Srabani13/Afame-Technologies.git
```
```
## 🎯 Conclusion

In this project, we applied linear regression to predict the survival of passengers aboard the Titanic. We analyzed various features such as passenger demographics, class, and family size to understand how these factors influenced survival chances.

### Model Performance:
- The **Linear Regression** model was used to predict survival as a continuous outcome. Although **Linear Regression** is traditionally used for regression tasks, it allowed us to gain an understanding of the relationships within the data.
- The model achieved an **accuracy of 72%**, which is a solid starting point for a basic linear model. While **Linear Regression** isn’t ideally suited for classification tasks, it still provides valuable insights into the data.

### Key Takeaways:
- **Linear Regression** is more appropriate for continuous outcomes, but it helped us explore the data and understand trends.
- For a binary classification task like predicting survival, **Linear Regression** may not be the most optimal model compared to other classification models like **Logistic Regression**. However, it still serves as an excellent tool for understanding relationships between variables.

This project demonstrates the potential of using **Linear Regression** to explore and understand data, but it also highlights the importance of choosing the right model for the task at hand. In the future, more advanced techniques could be explored to enhance prediction accuracy.

We hope this analysis sparks further curiosity and exploration into the world of machine learning and data science! 🚀📊

It would be great if you could let me know if you feel any changes need to be made. I am always willing to receive feedback and suggestions.
