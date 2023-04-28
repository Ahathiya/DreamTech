DreamTech is a Facial Emotion detection-based movie and music recommendation website that cheers up users and saves time while searching for a movie or song that matches their mood.

It Detect the Facial Emotion based on the 7 categories angry, sad, fear, happy, disgust, surprise, and neutral.Based on the emotion it gives the user two choices either suggesting movies or songs.If a user wishes to watch movies/songs then a list of movies/songs matching their mood are suggested with a movie/songs poster.

When a user clicks on the movie that he / she wishes to watch, they will be redirected to the IMDB website and for songs, it redirects them to the Spotify website.

How we built it ?

     Python is the programming language used to create the emotion detection model and deploy it on the web application using flask, CV2, TensorFlow, Keras NumPy, matplotlib, and other libraries are also utilized. 
     The model is built using the transfer learning approach for which the MobileNet model is used.
     The FER-2013 dataset from Kaggle, which comprises around 35000 photos, was utilized for model training and validation.
     This model is deployed on a website created with HTML and CSS using the flask framework. 
     Based on the seven emotions, a new dataset of movies and music was constructed.The data from movies and songs were utilized to create the various templates that  correlate to various emotions.
    
What's next for DreamTech ?
     The next step is to improve the model's accuracy. We are also going to introduce an AI-based chatbot with which users may express their problems and, based on the same, the Bot will recommend some remedies as well as the most suitable movie or song in that case.

Built With :-
  html
  css
  python
  flask
  keras
  numpy
  opencv
  tensorflow
  jupyter-notebook
  transfer-learning
  machine-learning
  IDE Used is Pycharm
  

     
