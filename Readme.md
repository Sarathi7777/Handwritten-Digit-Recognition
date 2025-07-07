# Handwritten Digit Recognition

A web application that recognizes handwritten digits using a deep learning model built with Keras and TensorFlow. Users can upload an image of a handwritten digit, and the app predicts the digit using a pre-trained model.

## Features
- Upload an image of a handwritten digit (0-9)
- Predicts the digit using a trained neural network
- Attractive, modern web UI
- Built with Flask, Keras, and TensorFlow

## Demo
![Demo Screenshot](demo_screenshot.png)

## Getting Started

### Prerequisites
- Python 3.8+
- pip

### Installation
1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd Handwritten-Model
   ```
2. **Create and activate a virtual environment (recommended):**
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

### Running the App
1. **Start the Flask server:**
   ```bash
   python app.py
   ```
2. **Open your browser and go to:**
   [http://127.0.0.1:5000](http://127.0.0.1:5000)

### Usage
- On the home page, upload an image file containing a handwritten digit.
- Click "Predict" to see the predicted digit.

## Project Structure
```
Handwritten Model/
├── app.py                # Main Flask application
├── handwritten_model.hdf5 # Pre-trained Keras model
├── requirements.txt      # Python dependencies
├── templates/            # HTML templates
│   ├── index.html
│   └── result.html
├── static/
│   └── style.css         # CSS styles
└── README.md             # Project documentation
```

## Credits
- [Flask](https://flask.palletsprojects.com/)
- [Keras](https://keras.io/)
- [TensorFlow](https://www.tensorflow.org/)

## License
This project is licensed under the MIT License.
