# 🧠 Sign Language Recognition System

## 📽️ Demo Link  
[Watch on YouTube](https://youtu.be/MP3bIqmON_k?si=UmykhsyY2FekzWft)

This project was developed by **Tejas Vinayaka Rao Kangod**, **Ruchi**, **Sameer Kumar Singh**, and **Saurav Kumar**.

The model is capable of recognizing the following 5 hand gestures:
- 👍 Thumbs Up  
- 👌 OK  
- ✌️ Peace  
- ✋ Open Hand  
- 🚫 No Hand 

---

## 🧩 Project Overview

The **Sign Language Recognition System** consists of **two applications**:

---

### 1️⃣ Web-Based Image Classification Model (Xception Architecture)

This application provides a **minimalistic web interface** where users can:
- Upload an image of a hand gesture  
- Receive a prediction of the gesture made

#### 🧪 Model Architecture:
- Initially trained using **VGG-16**
- Then refined with **MobileNet**
- Final training done using the **Xception model**

#### 🛠️ Technologies Used:
- Flask  
- Xception Model  
- HTML, CSS  
- JavaScript  
- Bootstrap

---

### 2️⃣ Real-Time Sign Detection Using OpenCV

This model recognizes signs **in real time** using your webcam.  
The process involves:
- Capturing live video feed via webcam  
- Detecting hand landmarks using **MediaPipe.Hands**  
- Identifying gestures based on the visible joint patterns  
- Displaying the recognized sign as text

#### 🛠️ Technologies Used:
- Python  
- OpenCV  
- MediaPipe  

---

## 🔗 Repositories

### 📦 Real-time Sign Language Recognition Model  
[View Repository](https://github.com/jassu75/Real-Time-Hand-Gesture-Recognition)

### 🌐 Web-based Sign Language Recognition Model  
[View Repository](https://github.com/jassu75/Web-based-Hand-Gesture-Recognition)
