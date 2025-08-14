#  Football Player Detection & Information Retrieval

This is an **AI-powered Streamlit web app** that detects **professional football (soccer) players** from uploaded images, retrieves detailed information using **Google Gemini API**, and provides **voice output** using `gTTS`.

The project combines **computer vision**, **generative AI**, and **text-to-speech** technologies for a smooth, interactive experience.

---

##  Features

-  **Face Detection** using OpenCV's Haar cascade (largest face selection).
-  **Player Identification & Info Retrieval** using Google Gemini AI.
-  **Detailed Player Info** including:
  - Full Name
  - Nationality
  - Club
  - Position
  - Achievements
-  **Voice Output** of player details using Google Text-to-Speech (`gTTS`).
-  **Streamlit Web UI** for easy interaction.
-  **Bounding Box Visualization** around detected player face.

---

##  Tech Stack

- **Python 3.8+**
- [Streamlit](https://streamlit.io/) – Web app framework
- [Google Gemini API](https://ai.google.dev/) – AI model for player recognition
- [OpenCV](https://opencv.org/) – Face detection
- [NumPy](https://numpy.org/) – Image array processing
- [Pillow (PIL)](https://pillow.readthedocs.io/en/stable/) – Image manipulation
- [gTTS](https://pypi.org/project/gTTS/) – Google Text-to-Speech for audio output

---

##  Project Structure

football-player-detection/
│
├── app.py # Main Streamlit application file<br>
├── requirements.txt # Python dependencies<br>
├── README.md # Project documentation<br>
└── assets/ # (Optional) Store sample images here<br>

---

## Install Dependencies

streamlit
google-generativeai
opencv-python
numpy
Pillow
gTTS


---

## Running the App

Run the Streamlit app locally:
streamlit run app.py

---

## How It Works

Upload Player Image → User uploads a football player's image.

Face Detection → OpenCV detects the largest face.

AI Recognition → Google Gemini analyzes the image and retrieves player details.

Bounding Box → A green rectangle is drawn around the detected player's face.

Voice Output → gTTS generates an MP3 audio of the details.

Display Output → Image, text, and audio are displayed in the Streamlit app.


---


## Possible Improvements

Add multi-face detection for group photos.

Integrate live webcam support for real-time detection.

Improve name accuracy with fine-tuned AI prompts.

Save detected results in a database for history tracking.

---

## Contributing

Pull requests are welcome!
If you find a bug or have suggestions, please open an issue.


---

## Author

Varnit Chauhan
B.Tech CSE Student | AI & Web Development Enthusiast<br>
Contact: varnitchauhan97@gmail.com<br>
GitHub:  https://github.com/VarnitChauhan
