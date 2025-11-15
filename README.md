# Hand Number Recognition

This project uses a Teachable Machine image model to recognize numbers from 1 to 5 shown with a hand in real-time.

## Objective
The goal of this project is to demonstrate hand gesture recognition using a webcam and a pre-trained machine learning model.

## Usage
1. Clone or download this repository.
2. Open `index.html` using a **local server** (recommended) or deploy via **GitHub Pages**.
3. Allow access to your webcam.
4. Show your hand in front of the camera to display numbers.
5. The predicted number and confidence percentage will appear on the screen.

## Project structure
hand-number-recognition/
│── index.html ← Main webpage
│── script.js ← Script to load the model and handle webcam
│── model/ ← Model files exported from Teachable Machine
│ ├── model.json
│ ├── metadata.json
│ └── weights.bin
│── README.md ← Project description

## Limitations
- Works better with the right hand.
- Sensitive to lighting and background changes, use preferably a white background.
- Only recognizes numbers 1–5.
- Model performance may decrease if the camera quality is low.

## Credits
- Model trained with [Teachable Machine](https://teachablemachine.withgoogle.com/)

## License
MIT License