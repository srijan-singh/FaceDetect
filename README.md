<h1> FaceDetect</h1>

<h2>Face Detection Model Using Google Colab</h2>

It uses face recognition library, which has face encodings to detect and recognize different faces. 
<br>
Created a class where we can initialize it with an image path and label which save it's encoding then from predict function it checks whether the encodings are same or not!
<br>
<br>
<b>If</b> the encodings is same we return the image with label name.
<br>
<br>
<b>Else</b> we return the image with default label Unknown.
<br>
<br>
Blog explaining Model: https://srijanverse-ml.blogspot.com/2021/05/face-detection-and-recognition-model.html 

<h2>Face Detection and Recognition API. </h2>
I've used the above model and used FastAPI framework to create the API and Uvicorn for the server to run it on Google Colab. 

<h3>The API has four request:</h3>

<b>Index (GET) :</b> Homepage of API

<b>Upload (POST) :</b> User can upload the image and label to be used as dataset.

<b>Target (POST) :</b> Target image on which prediction has to be done. 

<b>Prediction (GET) :</b> Get the prediction.

<h3>***The purpose of this project was to understand the creation of a ML API and how to use it and it's use is restricted for educational purpose only.***</h3>


Blog explaining API: https://srijanverse-ml.blogspot.com/2021/06/face-detection-and-recognition-api.html
