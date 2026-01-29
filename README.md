# Building And Deploying A Netflix Recommender System
Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API.

We use web scraping to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.

---

### Installation
Clone the repository and install dependencies:

1. Clone this repository to your local machine using the following command:
```bash
git clone https://github.com/lnghi2710/End-to-end-Netflix-Recommendation-System-and-Deployment.git
```
2. Navigate to the project directory:
```bash
cd End-to-end-Netflix-Recommendation-System-and-Deployment
```
3. Install the required packages:
```bash
pip install -r requirements.txt
```

---

## Usage
To run a Flask deployment tests, run the following command
```bash
  python main.py
```

Or I have deployed it on Heroku

To run a Heroku deployment tests, click on the following link:
[Netflix.Recommendation.website](https://netflix-recommendation-system-e6c7a25b175b.herokuapp.com/)


---

## Deployment
Steps To Deploy The App:

Prepare your dataset:
```bash
    1. Data Extraction
    2. Exploratory Data Analysis(EDA)
    3. Feature Engineering
    4. Model Building and Tuning
    5. Building Flask API
    6. Pushing code to Github
    7. Connecting to your Heroku account 
    8. Deploy App
```

---


## Demo

<img width="1439" height="776" alt="image" src="https://github.com/user-attachments/assets/66d8adbf-182d-4325-abb7-98fd48db49c1" />


