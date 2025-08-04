# 🎬 Netflix Content Classification

Ever wondered what makes a Netflix title a *Movie* or a *TV Show*?  
In this project, we dive into Netflix’s dataset and build a machine learning model that classifies titles using only their descriptions.

---

## 📌 Objective

The goal is to automatically classify whether a title is a **Movie** or a **TV Show** based on its textual **description**, using natural language processing and logistic regression.

---

## 🚀 Tech Stack

- **Python**
- **Pandas** for data manipulation  
- **Seaborn & Matplotlib** for visualization  
- **Scikit-learn** for machine learning & TF-IDF  
- **Google Colab** for development  

---

## 🧠 Approach

1. **Data Cleaning**  
   Cleaned missing values in key columns like `type`, `country`, and `duration`.

2. **Exploratory Data Analysis**  
   Visualized content types to understand the dataset better.

3. **Text Vectorization (TF-IDF)**  
   Converted the `description` column into numerical form using TF-IDF.

4. **Model Building**  
   Trained a **Logistic Regression** model to classify content.

5. **Evaluation**  
   Evaluated model accuracy and displayed a confusion matrix for performance insights.

---

## 📊 Sample Results

- Achieved solid accuracy in identifying whether a title is a Movie or TV Show
- Simple model, yet effective using just the description

---

## 📁 Files Included

| File Name                    | Description                                    |
|-----------------------------|------------------------------------------------|
| `Netflix_Classification.ipynb` | The main notebook with code & explanations     |
| `netflix_titles.csv`        | Netflix content dataset (from Kaggle)         |
| `README.md`                 | You're reading it 😊                            |

---

## 📷 Screenshots

Here’s a quick peek at the visuals in the notebook:

- 📈 Bar charts of content type distribution  
- 📘 Confusion Matrix of predictions  
- 📋 Classification report with precision/recall

(You can add actual screenshots in an `/assets` folder if needed.)

---

## 🙌 Acknowledgements

Thanks to the open dataset community — especially Kaggle — for providing publicly available data that powers fun and useful ML projects like this one.

---

## 🔗 Run It Yourself

You can run this notebook directly in **Google Colab**. Just upload the dataset and follow along!

---

## 💡 Future Work

- Try using deep learning or transformer models like BERT for better classification
- Add more features like cast, director, or genre
- Deploy the model using Streamlit or Flask

---


