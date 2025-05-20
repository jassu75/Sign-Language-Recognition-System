# Sign-Language-Recognition-System

This project was made by Ruchi, Sameer Kumar Singh, Tejas V Kangod, Saurav Kumar. It was developed using Python, HTML, CSS. 5 signs can be developed using this model - Thumbs Up, OK, Pease, No Hand, Open Hand.
The Sign Language Recognition System consists of 2 models.

1) **The Xception Architecture** : This model has a minimalistic website for the front end through which the user can login. The user will have to upload an image of a sign gesture. The model will guess the guesture and give output. It also shows the performance analysis. This model was trained using transferable training architecture. Fiest the layers were trained with vgg_16 model and then the MobileNet model. After that the Xception model was added.

2) **Open CV Model** : This model is used for real time recognition of sign language. 5 signs can be detected. The user will make a sign in front of the webcamera. This is taken as input by OpenCV. It is passed on to MediaPipe.Hands function which creates a pattern on the hand (Hand has fixed set of nodes. based on pattern some are hidden and rest are shown. The ones that are shown are connected to make pattern). The gesture is then described as text.

3) The report of the project work is attached. Please refer it to view the screenshots of the successful demo of the project along with other information.


## Web based Sign Language Recognition Model

[Visit repository](https://github.com/jassu75/Web-based-Hand-Gesture-Recognition)

## Realtime Sign Language Recognition Model

[Visit repository](https://github.com/jassu75/Real-Time-Hand-Gesture-Recognition)
