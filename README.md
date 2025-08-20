# 🎬 Movie Recommender Web Application

This is a Flask-based web application that recommends movies based on your selection using a pre-trained content-based similarity model. It leverages the TMDb API to fetch movie posters and display recommendations with a clean UI.

---

## 🚀 Features

- Recommend top 20 similar movies based on the selected movie.
- Fetch and display posters via TMDb API.
- Flask-based backend with HTML templating.
- Dockerized for easy deployment and portability.

---

## 🧾 Requirements

- Docker installed on your machine
- 

---

## 🐳 Run with Docker

### 1. Pull the Docker image


```bash
docker pull damton/movie-recommender





2.Run the container locally

docker run -p 5000:5000 damton/movie-recommender

Then open your browser to:

3.
http://localhost:5000




 Run Locally (Without Docker)
1. Clone the repository

git clone https://github.com/Dammyjosh/Personalised-Movie-Recommender.git

cd movie-recommender


2. Install dependencies

pip install -r requirements.txt


3. Run the Flask app

python app.py

