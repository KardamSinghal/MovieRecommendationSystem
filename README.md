# 🎬 Movie Recommendation System

A content-based and collaborative filtering recommendation engine built using Python and machine learning. This project suggests movies to users based on their preferences and past interactions.

## 📌 Overview

This Movie Recommendation System leverages both **content-based filtering** (based on metadata like genres, cast, keywords) and optionally **collaborative filtering** (based on user interactions/ratings) to suggest movies that users are likely to enjoy.

The dataset is sourced from the [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata) on Kaggle.

## 🚀 Features

- 🔍 Content-based filtering using movie metadata
- 🤝 Optional collaborative filtering using user ratings
- 🧠 Cosine similarity to calculate movie similarity scores
- 📊 Data preprocessing and cleaning using Pandas
- 🌐 Streamlit web app for user interaction (optional)
- 🔎 Searchable movie list with ranked recommendations

## 🛠️ Tech Stack

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- NLTK (for optional text cleaning)
- Streamlit (for web app interface)
- Jupyter Notebook (for development)

## 📂 Project Structure

```
MovieRecommendationSystem/
│
├── data/                     # Raw and processed datasets
├── notebooks/                # Jupyter Notebooks for EDA and model development
├── app/                      # Streamlit app files (optional)
├── recommender.py            # Core recommendation logic
├── preprocess.py             # Data cleaning and feature extraction
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

## 🧪 Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/KardamSinghal/MovieRecommendationSystem.git
cd MovieRecommendationSystem
```

2. **Create and activate a virtual environment**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run the Jupyter notebook or Streamlit app**

- To run notebook:
  ```bash
  jupyter notebook
  ```

- To run Streamlit app (if available):
  ```bash
  streamlit run app/app.py
  ```

## 📈 Example Usage

In the notebook or app, just enter a movie name, and the system will return the top 5 similar movies based on content similarity.

```python
recommend('Inception')
```

✅ Output:

```
1. Interstellar  
2. The Prestige  
3. The Matrix  
4. Shutter Island  
5. The Dark Knight
```

## 📊 Dataset

- **TMDB 5000 Movies Dataset**
- Includes metadata such as genres, keywords, cast, crew, and user ratings.

📎 [Download from Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

## 📌 Future Enhancements

- Hybrid model combining collaborative + content-based filtering
- User login and watch history
- Personalized recommendations
- Cloud deployment (Heroku, AWS, etc.)

## 🤝 Contributing

Pull requests are welcome! Feel free to fork the repo and submit a PR with improvements.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙋‍♂️ Author

Kardam Singhal  
🔗 [LinkedIn](https://www.linkedin.com/in/kardamsinghal)  
📫 Email: kardamsinghalllll@gmail.com

---

⭐️ If you like this project, give it a star on [GitHub](https://github.com/KardamSinghal/MovieRecommendationSystem)!
