# Real-Time Hand Number Recognition

Simple browser-based hand gesture recognition project built with Google Teachable Machine.

The model recognizes hand numbers from 1 to 5 in real time using a webcam.

---

## How It Works

- The webcam captures live video from the browser.
- A Teachable Machine image classification model processes each frame.
- Displays the percentage of confidence for each of the possible numbers.

The model runs entirely in the browser.

---

## Technologies Used

- Google Teachable Machine
- Auto-generated web deployment (HTML + JavaScript export)

---

## Limitations

- Works best under controlled lighting conditions directly from the front
- Requires a plain white background for more accurate prediction
- Performance is very sensitive to shadows and lighting
- Sensitive to hand position and distance from the camera
- Only supports numbers 1–5
- Bias towards class 3 when confidence is low. This is likely due to similarity between classes

This is a limited model that is trained with approximately 350 images per class. 

Performance would improve with larger and more diverse amounts of data.

---

## Project Structure

```text
hand-number-recognition/
├── index.html
├── model/
│   ├── model.json
│   ├── metadata.json
│   └── weights.bin
└── README.md
```

---

## Running the Project

### Live demo with GitHub Pages
https://pablopul-portfolio.github.io/hand-number-recognition/


### Clone the repository:

```bash
git clone https://github.com/pablopul-portfolio/hand-number-recognition.git
cd hand-number-recognition
```

---

## About
This project was built as an introduction to real-time machine learning in the browser using supervised learning for image classification.

The model performs well in the controlled conditions it was trained on, but degrades significantly in real world environments.