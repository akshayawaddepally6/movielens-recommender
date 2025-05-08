
# 🎬 MovieLens Recommender

**MovieLens Recommender** is a scalable movie recommendation system built using Apache Spark and Flask. It uses collaborative filtering via the ALS (Alternating Least Squares) algorithm to generate personalized movie recommendations based on the MovieLens dataset.

---

## 🚀 Features

* 🔍 **Collaborative Filtering with Spark ALS**
* 🧠 **User-Based Movie Recommendations**
* 🌐 **REST API Built with Flask**
* 📊 **Efficient Large-Scale Data Processing Using Spark**

---

## 🛠 Tech Stack

* Python 3
* Apache Spark
* Flask + CherryPy
* MovieLens Dataset (100k)

---

## 📦 Project Structure

```
movielens-recommender/
├── engine.py               # Spark-based recommendation logic
├── app.py                  # Flask app exposing the API
├── server.py               # CherryPy wrapper to serve the API
├── notebooks/              # Notebooks for exploration and training
├── download_dataset.sh     # Script to fetch the MovieLens dataset
├── start_server.sh         # Script to start the Flask server
├── requirements.txt
└── README.md
```


## 📡 API Endpoints

* `GET /recommendations/<user_id>`
  Returns a list of movie recommendations for the given user.

* `POST /ratings`
  Accepts a new user rating to update the model input.

---

