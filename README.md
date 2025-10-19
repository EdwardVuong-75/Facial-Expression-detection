# Facial-Expression-detection

This project is a Real time Facial-Expression-detection using Computer Vision and Deep Learning:
• Convolutional neural network (CNN) - PyTorch: focusses on deep learning and machine learning tasks such as training model to learn from input facial image data to classify human emotions. 
•	OpenCV: focuses on traditional computer vision tasks such as image processing, object detection and feature matching. In this study, OpenCV plays big role in facial detection
 to recognize facial expressions of seven different emotions: angry, disgust, fear, happy, neutral, sad, and surprise. The model is trained on the Face expression recognition dataset (FER2013). 
Dataset E-link: https://www.kaggle.com/datasets/msambare/fer2013.


<img width="603" height="439" alt="Screenshot 2025-10-19 020608" src="https://github.com/user-attachments/assets/6c88dcd1-bb56-407f-9365-fa4d65ac9958" />

<img width="1108" height="816" alt="Screenshot 2025-10-14 160403" src="https://github.com/user-attachments/assets/78f31cf6-4690-4193-b15f-81d3ea66a868" />


Requirements:-
Python 3.11,
PyTorch 2.8.0+cu126,
os,
numpy,
matplotlib,
pandas,
seaborn,
cv2


Installation:-
1. First install the python.
2. After installing python. Install PyTorch version '2.8.0+cu126' with CUDA, PyTorch can perform faster. Use the command pip install: pip3 install torch torchvision --index-url https://download.pytorch.org/whl/cu126 


Usage:-
1. Clone or download the repository.
2. Install the requirements on "Installation"
2. Run the main.py script using the following command:
   python main.py
3. The script will launch the webcam and start detecting emotions in real-time.


Files:-
1. main.py: This file is the entry point of the application. It loads the trained model and uses it to predict the emotions of faces in real-time using a webcam. This file contains the Python code for building and training the CNN.
3. HaarcascadeclassifierCascadeClassifier.xml: The pre-trained Haar Cascade Classifier for detecting faces in images.
4. emotion_model4.pth: The final pre-trained PyToech model with the highest accuracy compare to other for emotion detection.


