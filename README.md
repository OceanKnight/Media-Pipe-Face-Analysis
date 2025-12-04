<h1>**Emotion Recognition**<br></h1>
It's a two hour project. <br>
The initial idea of this project is simply make emotion recognition using deepface. But I found about a few pre-trained libraries like mediapipe, deepface, and opencv. So I used openCV for facial recognition and mesh based analysis. So it is catagorized into three different parts. <br>
1.Mesh Analysis.<br>
2.Node Analysis.<br>
3.Picture Analysis.<br>
Both 1,2 works with live camera access. 1 shows what portion of face is measured and 2 shows the nodes responsible for emotion analysis.<br>
3 is a preloaded image in jpg or png format from your file directory, shows exact measurments of every emotion out of 100%<br>
Sample output for 3. <br>{'emotion': {'angry': 0.0005588207629937141, 'disgust': 1.1566329847306532e-07, 'fear': 6.17287591841153e-08, 'happy': 99.84946252710074, 'sad': 0.00019885385330401526, 'surprise': 5.194142452017659e-06, 'neutral': 0.14977269417522024}, 'dominant_emotion': 'happy', 'region': {'x': 779, 'y': 266, 'w': 523, 'h': 523, 'left_eye': None, 'right_eye': None}, 'face_confidence': 0.91}<br>
