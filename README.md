# 4.-Movie-Recommendation-System-
Content-Based-Movie-Recommender-System-with-sentiment-analysis
Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

Note: The application has been updated to a newer version. Get the source code of the newer version here
GIF

Check out the youtube video if the above preview is not visible: https://www.youtube.com/watch?v=muPDsWgMkpc

Check out the live demo: https://mrswsa.herokuapp.com/

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.

How to get the API key?
Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. You will see the API key in your API sidebar once your request is approved.

How to run the project?
Install all the libraries mentioned in the requirements.txt file.
Clone this repository in your local system.
Replace YOUR_API_KEY in the main.py file.
Open the command prompt from your project directory and run the command python main.py.
Go to your browser and type http://127.0.0.1:5000/ in the address bar.
Hurray! That's it.
