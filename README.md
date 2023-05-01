# Song-Recommendation-System-using-Spotify-Audio-Features
The project is designed to generate a playlist of recommended songs based on a given track using machine learning techniques.
```
pip install spotipy
pip install pandas
pip install scikit-learn
```

After installing the libraries, you need to create a **vars.py** file with your Spotify API credentials. In this file, create two variables **stored_client_id** and **stored_client_secret** with your credentials, like this:

```
stored_client_id = 'your_client_id_here'
stored_client_secret = 'your_client_secret_here'
```
You can obtain your credentials by creating a Spotify developer account and creating a new app.

Next, download the model from [here](https://www.kaggle.com/general/153757) and place it in the root directory of the project.

First, write the Spotify url of your base track in the **song_url** variable to get its audio features, then run the script.py file to start the program. You should now be able to use the Spotify Playlist Recommender.

# Contributing
Please feel free to fork this repository and contribute by submitting a pull request to enhance the functionality.

# Presentation
[Here](https://docs.google.com/presentation/d/1juQ_OosCh2R01swql2PKf-_r5L0mXQgUzVuCTZcdEKA/edit?usp=sharing) you can find an overview of this project.

# License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
