# Bone Fracture Detection 🦴

## **Project Overview**
This project is a deep learning-based system designed to detect bone fractures from X-ray images. The model utilizes the **ResNet18** architecture to classify X-rays as either **fractured** or **not fractured**, assisting healthcare professionals in making quick and accurate diagnoses.

---

## **Key Features**
- **Deep Learning Model**: Built on **ResNet18**, a pre-trained Convolutional Neural Network.
- **Binary Classification**: Detects whether an X-ray image shows a **fractured** or **not fractured** bone.
- **User-Friendly Interface**: Provides drag-and-drop functionality along with a "Choose File" option.
- **Advanced Visualizations**: Includes performance metrics such as ROC curve, confusion matrix, and training history plots.
- **Real-Time Predictions**: Quickly processes uploaded images and provides confidence scores.

---

## **Technologies Used**

| **Technology**       | **Description**                                                               |
|-----------------------|------------------------------------------------------------------------------|
| **Python**           | Core programming language for model training and application development      |
| **PyTorch**          | Framework used for building and training the ResNet18 model                   |
| **Flask**            | Lightweight web framework for backend development                             |
| **HTML/CSS**         | Frontend for the application with animations and modern design                |
| **Bootstrap**        | CSS framework for styling and responsive design                               |
| **Matplotlib/Seaborn**| Libraries for visualizing metrics such as confusion matrix and ROC curve     |

---

## **Project Structure**

```plaintext
.
├── app.py                 # Flask backend for handling predictions
├── templates/             # Folder containing HTML templates
│   └── index.html         # Main frontend file
├── bone_fracture_resnet18.pth # Trained PyTorch model
├── requirements.txt       # List of dependencies for the project
├── README.md              # Project documentation
├── static/                # Static files for CSS and JavaScript (if any)
└── dataset/               # Dataset used for training and testing

```


---

## 🚀 **How to Run This Project**
1. Clone the repository:
   ```bash
   git clone https://github.com/thilak-r/Bone-fracture-detection.git
   cd Bone-fracture-detection

2. Install Dependencies: 
Run the following command to install all required dependencies:
   ```bash 
   pip install -r requirements.txt

3. Run the Flask App
Start the Flask application by running:
   ```bash
   python app.py

4. Open Your Browser
Navigate to the following address in your web browser to access the application:
   ```bash
   http://127.0.0.1:5000

<br>

## ❤️ Thank You!
Thank you for checking out our project! We hope this inspires you to explore the intersection of AI and healthcare. Feel free to reach out for questions, suggestions, or collaborations.

---

<br><br>
under guidance of [Dr Agughasi Victor Ikechukwu](https://github.com/Victor-Ikechukwu)
