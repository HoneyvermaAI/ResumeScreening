# ResumeScreening
# 📄 AI Resume Screening using Machine Learning

An intelligent Resume Screening System that automatically classifies resumes into different job categories using **Natural Language Processing (NLP)** and **Machine Learning**.

This project demonstrates how recruiters can automate the initial resume screening process by analyzing resume text and predicting the most suitable job category.

---

## 🚀 Features

* 🧹 Resume text preprocessing and cleaning
* 📊 Exploratory Data Analysis (EDA)
* 📝 TF-IDF Vectorization for feature extraction
* 🤖 Machine Learning-based resume classification
* 📈 Performance evaluation using Accuracy, Confusion Matrix, and Classification Report
* ⚡ Easy to extend with additional ML models

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Regular Expressions (Regex)

---

## 📂 Dataset

The project uses the **Updated Resume Dataset**, which contains resumes from multiple professional domains such as:

* Data Science
* Python Developer
* Java Developer
* Web Designing
* HR
* Testing
* DevOps
* Blockchain
* Mechanical Engineer
* Civil Engineer
* Business Analyst
* Network Security Engineer
* And many more...

### Dataset Columns

| Column     | Description                     |
| ---------- | ------------------------------- |
| `Category` | Job role/category of the resume |
| `Resume`   | Resume text                     |

---

## 📊 Project Workflow

```text
Dataset
    │
    ▼
Data Cleaning
    │
    ▼
Text Preprocessing
(Remove URLs, Symbols, Punctuation, etc.)
    │
    ▼
Label Encoding
    │
    ▼
TF-IDF Vectorization
    │
    ▼
Train-Test Split
    │
    ▼
Machine Learning Model
(K-Nearest Neighbors + OneVsRestClassifier)
    │
    ▼
Prediction
    │
    ▼
Evaluation
```

---

## 🧹 Text Preprocessing

The resume text is cleaned by:

* Removing URLs
* Removing mentions (@username)
* Removing hashtags
* Removing punctuation
* Removing special characters
* Removing extra whitespace

This improves the quality of features extracted from the resumes.

---

## 🤖 Machine Learning Model

The project uses:

* **TF-IDF Vectorizer** for converting text into numerical features.
* **OneVsRestClassifier**
* **KNeighborsClassifier (KNN)**

---

## 📈 Model Evaluation

The model is evaluated using:

* ✅ Accuracy Score
* ✅ Confusion Matrix
* ✅ Classification Report

  * Precision
  * Recall
  * F1-Score

---

## 📁 Project Structure

```
Resume-Screening/
│
├── ResumeScreening.ipynb
├── UpdatedResumeDataSet.csv
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Resume-Screening.git
```

Move into the project directory:

```bash
cd Resume-Screening
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📦 Required Libraries

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

Install them using:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

---

## 🎯 Future Improvements

* Add Support Vector Machine (SVM)
* Compare multiple machine learning algorithms
* Hyperparameter tuning
* Deep Learning (LSTM/BERT)
* Deploy using FastAPI or Flask
* Build a modern web interface with React

---

## 📚 Learning Outcomes

This project covers:

* Natural Language Processing (NLP)
* Text Cleaning
* TF-IDF Vectorization
* Label Encoding
* Machine Learning Classification
* Model Evaluation
* Resume Classification Pipeline

---

## 🤝 Contributing

Contributions are welcome!

Feel free to fork this repository, create a new branch, and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Honey Verma**

AI & Machine Learning Enthusiast | Python Developer | Aspiring AI Engineer

If you found this project helpful, don't forget to ⭐ star the repository!
