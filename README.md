# imageClassification# Image Classification Web App

This is a Flask-based web application that classifies images into categories using a trained deep learning model.

## Features
- Upload an image via a web interface
- Preprocess the image and make predictions using a deep learning model
- Displays the uploaded image along with the predicted class

## Project Structure
```
├── static/
├── templates/
│   ├── index.html
├── models/
│   ├── image_classifier_models.h5
├── app.py
├── requirements.txt
├── README.md
```

## Installation
### Prerequisites
- Python 3.x
- Flask
- TensorFlow & Keras
- NumPy
- Pillow

### Setup
1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Flask app:
   ```sh
   python app.py
   ```
4. Open your browser and go to:
   ```
   http://127.0.0.1:5000/
   ```

## Model Details
- The model is a deep learning classifier trained using TensorFlow/Keras.
- The trained model is stored in `image_classifier_models.h5`.
- It takes an image as input and classifies it into predefined categories.

## Usage
1. Open the web app.
2. Upload an image (JPEG, PNG, etc.).
3. The app will process the image and display the prediction.

## Deployment on AWS EC2 (Optional)
To deploy this project on AWS EC2:
1. Launch an EC2 instance with Amazon Linux.
2. Install necessary dependencies:
   ```sh
   sudo dnf update -y
   sudo dnf install python3 python3-pip -y
   pip install -r requirements.txt
   ```
3. Run the Flask app and expose it on port 80:
   ```sh
   sudo python3 app.py
   ```
4. Configure security groups to allow inbound traffic on port 80.
5. Access the application via the public IP of the EC2 instance.



## Contributions
Contributions are welcome! Feel free to open an issue or submit a pull request.

## Author
AdhilAbu9072

