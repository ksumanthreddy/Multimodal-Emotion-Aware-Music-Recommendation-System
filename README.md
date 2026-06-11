# Multimodal-Emotion-Aware-Music-Recommendation-System

An AI-powered Python application that detects a user's facial emotion through a webcam and automatically plays songs matching the detected mood.

## Features

-  Real-time facial emotion detection
-  Webcam-based face capture
-  Automatic song recommendation
-  Mood-based music playback
-  Interactive user experience
-  Organized song library

##  Technologies Used

- Python
- OpenCV
- NumPy
- TensorFlow / Keras
- DeepFace 
- Pygame (for music playback)
- OS and File Handling Modules

##  Project Structure

```text
Emotion-Based-Music-Player/
│
├── emotion.py          # Emotion detection logic
├── facecapture.py      # Webcam and face capture module
├── interaction.py      # User interaction handling
├── songs.py            # Song selection and playback
├── test.py             # Main application entry point
│
├── songs/              # Music library
│   ├── happy/
│   ├── sad/
│   ├── angry/
│   ├── neutral/
│   └── surprise/
│
├── .gitignore
├── README.md
└── venv/
```

##  Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/emotion-based-music-player.git
cd emotion-based-music-player
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

### 3. Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

If you don't have a requirements file:

```bash
pip install opencv-python numpy pygame
```

Install any additional libraries required by your project.

##  Running the Project

Run the main file:

```bash
python test.py
```

The application will:

1. Open the webcam.
2. Detect the user's face.
3. Analyze facial emotion.
4. Select an appropriate song.
5. Play music according to the detected mood.

##  Supported Emotions

- Happy 
- Sad 
- Angry 
- Neutral 
- Surprise 
- Fear 
- Disgust 

##  How It Works

1. Webcam captures the user's face.
2. Emotion recognition model predicts the emotion.
3. Corresponding music category is selected.
4. A song from that category is played automatically.

##  Future Improvements

- Spotify integration
- Better emotion recognition accuracy
- Playlist generation
- GUI using Tkinter or PyQt
- Voice command support
- Multi-user detection
 
Built with Python, Computer Vision, and AI to create a personalized music experience based on human emotions.

### Still Working For Further Improvements...
