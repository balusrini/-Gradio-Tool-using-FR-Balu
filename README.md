Table of Contents
Project Overview
Features
Technologies Used
Installation
Usage
Contributing
License
Contact
Project Overview
The Face Recognition Attendance System is designed to streamline attendance tracking using two methods: face recognition and card-based attendance. This project utilizes the ArcFace model for face recognition and employs OCR to extract registration or roll numbers from cards. This dual approach enhances flexibility and accuracy in attendance management.

Attendance System

Features
Dual-Mode Attendance: Use face recognition or card-based methods.
High Accuracy: Leverages ArcFace for reliable face detection.
User-Friendly Interface: Built with Gradio for easy interaction.
Data Management: Utilizes Pandas for effective data handling.
Real-Time Processing: Fast and efficient attendance marking.
Easy Setup: Simple installation and configuration.
Technologies Used
This project incorporates several key technologies:

Face Recognition: ArcFace, InsightFace
OCR: Tesseract OCR for card number extraction
Data Handling: Pandas DataFrame for data management
Image Processing: PIL for image manipulation
Machine Learning: Scikit-learn for classification
Deep Learning: PyTorch and torchvision for model training
Web Interface: Gradio for a user-friendly interface
Installation
To set up the Face Recognition Attendance System, follow these steps:

Clone the Repository:

git clone https://github.com/Jawerchy/Face-Recognition-Attendance-System.git
cd Face-Recognition-Attendance-System
Install Dependencies: Make sure you have Python installed. Then, install the required packages:

pip install -r requirements.txt
Download Pre-trained Models: You can find the necessary models in the Releases section. Download the files and place them in the appropriate directories.

Run the Application: Launch the application using:

python app.py
Usage
Once the application is running, you can access it through your web browser. The interface allows you to choose between face recognition and card-based attendance.

Face Recognition Mode
Upload a photo of the participant.
The system will process the image and mark attendance if the face is recognized.
Card-Based Attendance Mode
Scan the card with the registration number.
The system will extract the number using OCR and mark attendance.
Usage Example

Contributing
Contributions are welcome! If you would like to contribute to the project, please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Commit your changes.
Push to your branch.
Create a pull request.
