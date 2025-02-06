## DocSage: AI-Powered Skin Condition Diagnosis

## About DocSage
DocSage is an AI-powered skin condition diagnosis platform using the Swin Transformer model. Built with PyTorch, it offers high-accuracy classification of 24 skin conditions, providing healthcare professionals and patients with a fast, reliable, and user-friendly diagnostic tool for early detection.


Completed at GIFT University
Supervisor: Dr. Fouqia Zafeer
Project Leader: Muhammad Umar
Collaboration with:

Dr. Muhammad Faheem (HOD, CS Department)
Jameel Ahmad
Usama
Nouman Shahid
Usama
Project Introduction
DocSage is an AI-powered platform designed for diagnosing skin conditions using the Swin Transformer model. The project aims to automate the skin condition classification process with high accuracy, providing a fast and reliable diagnosis method. Built using PyTorch, the platform enables healthcare professionals and patients to get real-time diagnostic results with ease, enhancing medical decision-making and supporting early detection of skin-related health issues.

Project Features
High Diagnostic Accuracy: Achieved a remarkable 97% accuracy in diagnosing 24 different skin conditions.
State-of-the-Art Model: Utilizes the Swin Transformer, a cutting-edge deep learning model for image classification.
User-Friendly Interface: Designed to be intuitive and easy to use for healthcare professionals and patients.
Real-Time Results: Instant skin condition classification based on image input.
Scalable Solution: Can be deployed to large-scale healthcare settings for efficient diagnosis.
Technology Stack
PyTorch: A deep learning framework used for implementing the Swin Transformer model and training the neural network.
Swin Transformer: A state-of-the-art transformer-based model for image classification, known for its high performance in computer vision tasks.
Python: Programming language used for the implementation and training of the model.
Flask (Optional for deployment): Can be used for creating a web-based interface to interact with the model.
Files Details
Here’s a breakdown of the key files in the project:

file_1.py:
Functionality: Contains the image preprocessing pipeline, including image resizing, normalization, and dataset splitting into training, validation, and test sets. It ensures the input data is ready for model training.

file_2.py:
Functionality: Defines the architecture of the Swin Transformer model. This file contains the layers, loss functions, and optimizers needed to train the model effectively.

file_3.py:
Functionality: Implements the training loop, where the model is trained using the training data. It tracks the loss and accuracy during each epoch and saves the best-performing model for evaluation.

file_4.py:
Functionality: Handles model evaluation, testing the trained model on unseen test data. It calculates key performance metrics like accuracy, precision, recall, and generates confusion matrices.

file_5.py:
Functionality: Provides visualization tools for the model's predictions. It generates plots, including confusion matrices and accuracy curves, to help understand model performance.

requirements.txt:
Functionality: Lists all the required Python packages for the project, including PyTorch, NumPy, Matplotlib, and any other dependencies that need to be installed.

README.md:
Functionality: This file, which contains all relevant information about the project, including setup instructions, file descriptions, and contact information.

Setup Instructions
To set up and run the DocSage project locally, follow these steps:

Clone the Repository
Clone the repository to your local machine:

bash
Copy
Edit
git clone https://github.com/your-repo-link.git
Create a Virtual Environment
It’s recommended to set up a virtual environment to manage dependencies:

bash
Copy
Edit
python3 -m venv docsage-env
source docsage-env/bin/activate  # For Windows use: docsage-env\Scripts\activate
Install Dependencies
Install the required Python packages:

bash
Copy
Edit
pip install -r requirements.txt
Run the Training Script
Once dependencies are installed, you can train the model by running:

bash
Copy
Edit
python file_3.py
Evaluate the Model
After training, evaluate the model's performance using:

bash
Copy
Edit
python file_4.py
Contact Email
For any inquiries or further details, please contact:
Email: umarbytesoflife@gmail.com

Responsible: Muhammad Umar Farooq

