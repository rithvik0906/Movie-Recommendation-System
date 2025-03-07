# Movie Recommendation System 🎬

## 📌 Overview
This is a **Movie Recommendation System** built using **Machine Learning** and deployed as a web app using **Streamlit**. The system suggests similar movies based on a selected movie title using **cosine similarity**.

## ✨ Features
- 📌 Select a movie from the dropdown.
- 🎭 Get 5 similar movie recommendations.
- 🖼️ Fetches movie posters using **TMDb API**.
- 🔥 Interactive & user-friendly UI with **Streamlit**.

## 🛠️ Tech Stack
- **Python** 🐍
- **Streamlit** (for UI) 🎨
- **pandas & numpy** (for data processing) 📊
- **Scikit-Learn** (for similarity calculation) 🤖
- **TMDb API** (for fetching movie posters) 🎞️

## 📂 Project Structure
```
📁 Movie-Recommendation-System
│── 📂 artifacts
│   ├── movie_list.pkl
│   ├── similarity.pkl
│── 📄 app.py
│── 📄 README.md
│── 📄 requirements.txt
```

## 🚀 Installation & Setup
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/rithvik0906/Movie-Recommendation-System.git
cd Movie-Recommendation-System
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the App
```sh
streamlit run app.py
```

### 4️⃣ Open in Browser
Once the server starts, open the URL shown in the terminal, usually:
```
http://localhost:8501
```

## 🔍 How It Works
1. Loads pre-trained **movie similarity data** from `movie_list.pkl` and `similarity.pkl`.
2. Uses **cosine similarity** to find the closest movies to the selected one.
3. Fetches **movie posters** via **TMDb API**.
4. Displays **recommended movies** along with posters in a grid layout.

## 🛠️ Troubleshooting
### ⚠️ `requests.exceptions.ConnectTimeout`
If TMDb API fails, try:
- Checking **internet connection**.
- Setting a **timeout** in `requests.get()`.
- Getting a **new API key** from [TMDb](https://www.themoviedb.org/settings/api).

## 📜 License
This project is open-source under the **MIT License**.

## 📩 Contact
For queries, reach out via [LinkedIn](https://www.linkedin.com/in/rithvik-goud/)

---
### 🌟 If you like this project, give it a ⭐ on GitHub! Happy Coding! 🚀
