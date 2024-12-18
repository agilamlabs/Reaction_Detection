# 😀 Facial Emotion Detection with Streamlit 😄

This repository contains a simple web application that detects facial emotions from uploaded images using Streamlit and the Facial Emotion Recognition (FER) library.

## 📚 Table of Contents

- [✨ Features](#features)
- [🚀 Demo](#demo)
- [🛠️ Installation](#installation)
- [📝 Usage](#usage)
- [🧰 Technologies Used](#technologies-used)
- [🙏 Acknowledgments](#acknowledgments)
- [🤝 Connect with Me](#connect-with-me)

---

## ✨ Features

- 📷 Upload images in **JPG, JPEG, PNG, BMP, or TIFF** formats.
- 🧠 Detects emotions such as **happy, angry, disgust, sad, neutral, surprise, and fear**.
- 📊 Displays the dominant emotion with its confidence level.
- 🖼️ Draws bounding boxes around detected faces with emotion annotations.
- 💻 Simple and interactive web interface built with **Streamlit**.

## 🚀 Demo

You can try a live demo of the application by uploading an image and seeing the detected emotions.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Streamlit%20App-ff4b4b?style=flat&logo=streamlit)](https://facial-reaction-detection.streamlit.app/)

## 🛠️ Installation

To run this application locally, follow these steps:

### Prerequisites

Make sure you have the following installed:

**Python 3.8 or higher**

### Steps

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/facial-emotion-detection.git
    cd facial-emotion-detection
    ```

2. **Create a virtual environment:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # For macOS and Linux
    venv\Scripts\activate    # For Windows
    ```

3. **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Streamlit app:**

    ```bash
    streamlit run app.py
    ```

5. Open the application in your browser:

    ```
    http://localhost:8501
    ```

## 📝 Usage

1. Open the app in your browser.
2. 📤 Upload an image using the "Choose an image..." button.
3. 🖼️ The app will display the processed image with detected emotions and bounding boxes.

## 🧰 Technologies Used

- **🖥️ Streamlit** - For building the web application interface.
- **📸 OpenCV (cv2)** - For image processing and annotation.
- **🧠 FER Library** - For facial emotion detection.
- **🔢 NumPy** - For handling image arrays.
- **🖼️ PIL (Pillow)** - For image file handling.
- **📊 Matplotlib** - For image display (if needed for debugging).

## 🙏 Acknowledgments

This project uses the **FER** library for detecting emotions and the **MTCNN** model for accurate face detection.

## 🤝 Connect with Me

- [![YouTube](https://img.shields.io/badge/YouTube-Channel-red?style=flat&logo=youtube)](https://www.youtube.com/@agilamlabs)
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/gn-raavanan)

## Thank You
