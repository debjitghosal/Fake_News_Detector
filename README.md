# VeriFY
VeriFY is a machine learning project to classify news as real or fake by training BERT model. Includes real-time news scraping (Al Jazeera RSS) using feedparser and BeautifulSoup, TF-IDF vectorization, and performance evaluation with precision



# 📰 Fake News Detection Web App

A web-based application that uses a fine-tuned BERT model to classify news articles or headlines as **Real** or **Fake**. Built using Python, Flask, Hugging Face Transformers, and modern NLP techniques.

## 🚀 Demo
🎥 [Click here to watch the demo video](https://drive.google.com/file/d/1u7aO4ZXliC9JtExZQ5YVoHOghyUp_y-p/view)

## 🧠 Motivation
In the era of digital media, misinformation spreads faster than facts. This project aims to provide a tool that can assist users in identifying fake news based on natural language understanding rather than simple keyword filtering.

---

## 🛠️ Tech Stack

| Area        | Tool/Tech                     |
|-------------|-------------------------------|
| Language    | Python                        |
| Backend     | Flask                         |
| Frontend    | HTML5, JavaScript             |
| NLP Model   | BERT (`jy46604790/Fake-News-Bert-Detect`) |
| Libraries   | transformers, flask, sklearn, joblib, numpy, json |

---

## ⚙️ Features

- 🔎 Takes any news input text and classifies it as Fake or Real.
- 🧠 Uses BERT transformer model for contextual understanding.
- 🧪 Interactive UI for users to test headlines or full articles.
- 🌐 Can be deployed locally or on the cloud.

---

## 📂 Project Structure

```

pds\_project\_new/
├── app.py                    # Flask application
├── templates/
│   └── index.html            # Frontend interface
├── static/
│   └── favicon.ico           # Optional assets
├── fake\_news\_model.pkl       # (Optional) ML model if not using BERT API
├── tfidf\_vectorizer.pkl      # (Optional) Vectorizer for traditional model
├── requirements.txt
└── README.md

````

---

## 💻 Local Setup Instructions

### 1. 🔧 Clone the repository
```bash
git clone https://github.com/debjitghosal/Fake_News_Detector.git
cd Fake_News_Detector
````

### 2. 🐍 Create & Activate Virtual Environment (Optional but Recommended)

```bash
conda create -n fake_news_env python=3.10
conda activate fake_news_env
```

### 3. 📦 Install Dependencies

```bash
pip install -r requirements.txt
```

If using BERT from HuggingFace:

```bash
pip install transformers
```

### 4. ▶️ Run the Flask App

```bash
python app.py
```

### 5. 🌐 Open in Browser

Go to `http://127.0.0.1:5000/` in your browser to interact with the app.

---

## 📊 Model Details

* **Model**: BERT (`jy46604790/Fake-News-Bert-Detect`)
* **Prediction Labels**:

  * `LABEL_0` → **Fake News**
  * `LABEL_1` → **Real News**

---

## 🙌 Team

* **Debjit Ghosal** *(Team Leader)*
* **Vanshi Gathani**
* **Heer Gandhi**
* **Tanishq Dutta**

### 🧑‍🏫 Mentors

* **Dr. Nikita Mishra**
* **Abhijeet Salunke**

---

## 📌 Future Improvements

* Add user feedback loop
* Support multi-language input
* Host live version on Render or Hugging Face Spaces

---

## 📎 License

This project is for academic use. Feel free to fork, modify, and improve it for educational or research purposes.

## 🔗 GitHub

Explore the code: [https://github.com/debjitghosal/Fake\_News\_Detector](https://github.com/debjitghosal/Fake_News_Detector)
