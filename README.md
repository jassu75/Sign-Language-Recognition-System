# Sign-Language-Recognition-System

## Demo Link
[Visit Youtube](https://youtu.be/MP3bIqmON_k?si=UmykhsyY2FekzWft)

This project was made by Ruchi, Sameer Kumar Singh, Tejas V Kangod, Saurav Kumar. The 5 signs which can be recognised using this model are:
- Thumbs Up
- OK
- Pease
- No Hand
- Open Hand.

The Sign Language Recognition System consists of 2 applications.

1) **The Xception Architecture** : This model has a minimalistic website for the front end through which the user can login. The user will have to upload an image of a sign gesture. The model will guess the guesture and give output. This model was trained using transferable training architecture. First the layers were trained with vgg_16 model and then the MobileNet model. After that the Xception model was added.

    Technologies Used : Flask, Xception Model, HTML, CSS, Javascript, Bootstrap

3) **Open CV Model** : This model is used for real time recognition of sign language. The user will make a sign in front of the webcamera. This is taken as input by OpenCV. It is passed on to MediaPipe.Hands function which creates a pattern on the hand (Hand has fixed set of nodes. based on pattern some are hidden and rest are shown. The ones that are shown are connected to make pattern). The gesture is then described as text.

    Technologies Used: OpenCV, Mediapipe, Python

## Real-time Sign Language Recognition Model

[Visit repository](https://github.com/jassu75/Real-Time-Hand-Gesture-Recognition)

## Web-based Sign Language Recognition Model

[Visit repository](https://github.com/jassu75/Web-based-Hand-Gesture-Recognition)


