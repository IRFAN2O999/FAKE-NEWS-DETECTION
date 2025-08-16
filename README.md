# 📰 Fake News Detector

A **Machine Learning + Streamlit** project that detects whether a news article is **Fake** or **Real**.  
This project uses **TF-IDF vectorization** and a **Logistic Regression model** trained on the popular Fake & True News dataset.  

---

## ✨ Features  
- 🧹 **Text Preprocessing**: Cleans and normalizes news text  
- 🔠 **TF-IDF Vectorization**: Converts text into numerical features  
- 🤖 **Logistic Regression Model**: Trained to classify Fake vs Real  
- 📊 **Prediction Confidence**: Displays probability score  
- 🖥️ **Streamlit Web App**: User-friendly interface  

---

## 📂 Project Structure  

📁 Fake-News-Detector
│
├── 📄 app.ipynb # Script to train and save model
├── 📄 app.py # Streamlit app to predict Fake/Real
├── 📄 Fake.csv # Dataset (Fake news samples)
├── 📄 True.csv # Dataset (Real news samples)
├── 📄 vectorizer.jb # Saved TF-IDF vectorizer
├── 📄 lr_model.jb # Saved Logistic Regression model
└── 📄 README.md # Project documentation


---





## ⚙️ Installation & Setup  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/IRFAN2099/Fake-News-Detector.git
cd FAKE-NEWS-DETECTION

2️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the App
Launch the Streamlit app:

streamlit run app.py

📚 Dataset
•	Fake.csv https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset
•	True.csv https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset



📝 License
This project is licensed under the MIT License.
________________________________________
👨‍💻 Author
Developed with ❤️ by [IRFAN2099]


