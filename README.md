# 📰 Fake News Detection App  


An advanced AI-powered application to detect **Fake vs Real News** using **Machine Learning (Logistic Regression)** and **TF-IDF Vectorization**.  
Built with ❤️ using **Python** and **Streamlit**, this project provides a clean, interactive interface to classify news articles with high accuracy.  

---

## ✨ Features  
- 🧹 **Text Preprocessing**: Cleans and normalizes raw news text  
- 🔠 **TF-IDF Vectorization**: Converts text into meaningful numerical features  
- 🤖 **Logistic Regression Model**: Classifies Fake vs Real news  
- 📊 **Prediction Confidence**: Displays probability score for predictions  
- 🖥️ **Streamlit Web App**: User-friendly and interactive interface  

---

## 📂 Project Structure  
```
📁 Fake-News-Detector  
│── 📄 app.ipynb          # Script to train and save model  
│── 📄 app.py             # Streamlit app to predict Fake/Real  
│── 📄 Fake.csv           # Dataset (Fake news samples)  
│── 📄 True.csv           # Dataset (Real news samples)  
│── 📄 vectorizer.jb      # Saved TF-IDF vectorizer  
│── 📄 lr_model.jb        # Saved Logistic Regression model  
└── 📄 README.md          # Project documentation  
```

---

## ⚙️ Installation & Setup  

1️⃣ **Clone the Repository**  
```bash
git clone https://github.com/IRFAN2O999/FAKE-NEWS-DETECTION.git
cd FAKE-NEWS-DETECTION
```

2️⃣ **Install Dependencies**  
```bash
pip install -r requirements.txt
```

3️⃣ **Run the App**  
```bash
streamlit run app.py
```

---

## 📚 Dataset  
- [Fake.csv](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset) – Fake news samples  
- [True.csv](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset) – Real news samples  

---

## 📝 License  
This project is licensed under the **MIT License**.  

---

## 👨‍💻 Author  
Developed with ❤️ by **[IRFAN2099](https://github.com/IRFAN2O999)**  

