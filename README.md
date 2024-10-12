# Medi-Hub - Medical Records and AI-Powered Skin Disease Detection

Medi-Hub is a web-based platform that serves as a centralized hub for storing and managing medical records, with additional features to assist caregivers and healthcare professionals. The system also includes an AI-powered tool for detecting skin diseases and offering treatment suggestions. The application is designed with user-friendly functionality, allowing both patients and medical practitioners to maintain accurate medical histories and ensure emergency notifications are sent when needed.

## Features
- **Medical Record Storage:** Secure storage of patient medical histories, diagnoses, prescriptions, and other medical documents.
- **AI-Powered Skin Disease Detection:** A machine learning tool that helps users identify skin conditions from images and provides treatment suggestions.
- **Emergency Notification System:** Automatically sends notifications to caregivers in case of a medical emergency, based on stored health information.
- **User Roles:** Provides separate access for patients, doctors, and caregivers with customized features.
- **Responsive Design:** Fully responsive UI for mobile and desktop devices.

## Prerequisites
- XAMPP (or any local server environment like MAMP or WAMP)
- Web browser (Google Chrome, Mozilla Firefox, etc.)

### Technologies Used
- **HTML5:** For structuring web pages.
- **CSS3 & Bootstrap:** For styling and creating a responsive design.
- **PHP:** For backend server-side scripting.
- **MySQL:** For managing user and medical data.
- **JavaScript & jQuery:** For client-side interactions.
- **Python:** For AI-based skin disease detection using a machine learning model.
- **TensorFlow:** For the machine learning model used in skin disease detection.

## Installation

### Step 1: Set Up XAMPP
1. [Download XAMPP](https://www.apachefriends.org/index.html) and install it on your local machine.
2. Start **Apache** and **MySQL** services from the XAMPP control panel.

### Step 2: Clone or Download the Project
1. Clone this repository or download the project files.
```bash
   git clone https://github.com/SARATH-ANSIL/MEDI-HUB.git
```
2. Copy the project folder into the htdocs directory of your XAMPP installation.
`C:/xampp/htdocs/MEDI-HUB/`

### Step 3: Set Up the MySQL Database
Open phpMyAdmin by navigating to `http://localhost/phpmyadmin/` in your browser.
Create a new database called medihub_db.

### Step 4: Update Database Configuration
Update the database credentials if necessary (default settings for XAMPP should work fine).
```bash
<?php
$host = 'localhost';
$user = 'root';
$password = '';
$dbname = 'medihub_db';
?>
```
### Step 5: Set Up AI Model for Skin Disease Detection 
Install Python and required libraries such as TensorFlow for the AI-powered skin disease detection tool.
Add the trained machine learning model for skin disease detection.
Ensure Python scripts are integrated with the PHP backend to trigger AI predictions from image inputs.

### Step 6: Run the Application
Open your browser and go to `http://localhost/MEDI-HUB/`.
You should now be able to log in and access the various features of the Medi-Hub platform.

## Usage
1. Medical Record Management:
Users (patients and doctors) can securely store and manage their medical records, which are stored in the MySQL database.
2. AI Skin Disease Detection:
Users can upload an image of their skin condition. The AI model processes the image and provides possible skin disease diagnoses and treatment options.
3. Emergency Notifications:
Caregivers will receive notifications in case of emergencies. The system automatically checks the patient’s stored information for potential alerts.

## Screenshots
![6](https://github.com/user-attachments/assets/40669f2d-6ff6-4869-a923-bc09892e5f7b)
![7](https://github.com/user-attachments/assets/8871634e-8b42-48ec-8637-1edd03b8adcc)
![8](https://github.com/user-attachments/assets/7daef41a-637b-467f-871c-4df66e63daeb)

## Contributing
Contributions are welcome! If you have suggestions or encounter issues, feel free to open a pull request or issue on this GitHub repository.

## License
This project is licensed under the MIT License.

## Acknowledgments
- XAMPP for providing an easy-to-use local server environment.
- TensorFlow/Keras for machine learning support.
- Bootstrap for responsive UI design.
