
# Recognize Dog, Cat, and Horse Tool

## 📜 Overview
The Recognize Dog, Cat, and Horse tool is a machine learning-based application designed to classify images into three categories: Dog, Cat, or Horse. It supports real-time image classification from user-uploaded images. This project demonstrates:

- Convolutional Neural Network (CNN) Model
- User-friendly Web Interface
- Scalable Backend with Flask Framework

## 🖼️ Demo Screenshot:
![Demo Screenshot](https://github.com/TuyenTrungLe/Recognize-Dog-Cat-and-Horse-using-Deep-Learning-model/blob/main/demo-image.jpg "Demo Screenshot of the Application")

## 📂 Project Structure
```plaintext
Recognize_Dog_Cat_Horse/
├── app.py                        # Main Python file
├── model.h5                      # Pre-trained CNN model for classification
├── static/                       # Folder for static assets (e.g., images, CSS)
│   ├── uploads/                  # Stores uploaded images
├── templates/                    # Folder for HTML files
│   ├── index.html                # Main web interface
├── requirements.txt              # Dependencies for the project
├── README.md                     # Documentation for the project
```

## 🛠️ Features

### Image Classification:
- Classifies uploaded images into:
  - **Dog**
  - **Cat**
  - **Horse**

### User-Friendly Interface:
- Upload an image directly from your device.
- Real-time classification and results display.

### Accurate Model:
- Deep learning model (CNN) trained on a robust dataset to ensure high accuracy.

## 💻 Requirements
Ensure the following are installed:

1. **Python 3.8 or higher**
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Libraries included:
   - Flask
   - TensorFlow/Keras
   - OpenCV
   - numpy
   - pandas

## 🚀 How to Run

1. **Clone this repository**:
   ```bash
   git clone https://github.com/TuyenTrungLe/Recognize-Dog-Cat-and-Horse-using-Deep-Learning-model.git
   cd Recognize-Dog-Cat-and-Horse-using-Deep-Learning-model
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Flask app**:
   ```bash
   python app.py
   ```

4. **Access the application**:
   Open your browser and navigate to:
   ```
   http://127.0.0.1:5000
   ```

## 📊 Output
When you run the project:
- The system classifies uploaded images into **Dog**, **Cat**, or **Horse**.
- Displays the results on the web interface.

## 📧 Contact
- **Author:** Le Tuyen  
- **Email:** trungtuyenlevn@gmail.com  
- **GitHub:** [TuyenTrungLe](https://github.com/TuyenTrungLe)

## 🤝 Contributions
Contributions are welcome! Feel free to:
- Fork this repository
- Open an issue
- Submit a pull request
