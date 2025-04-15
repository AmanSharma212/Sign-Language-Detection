# SignLanguageDetectionUsingMachineLearning

This project aims to bridge the communication gap between deaf/mute individuals and those who can hear and speak. By leveraging machine learning, it translates sign language gestures into text and speech, facilitating two-way communication.​

Features
Real-Time Sign Language Detection: Utilizes a trained machine learning model to recognize and interpret sign language gestures captured via webcam.

Text Formation: Converts recognized gestures into coherent text, allowing users to read the interpreted message.

Text-to-Speech Conversion: Transforms the generated text into audible speech, enabling verbal communication.

User-Friendly Interface: Designed with simplicity in mind to ensure accessibility for users of all backgrounds.​

Installation
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/AmanSharma212/Sign-Language-Detection.git
cd Sign-Language-Detection
Install Dependencies: Ensure you have Python installed. Then, install the required packages:

bash
Copy
Edit
pip install -r requirements.txt
Run the Application:

bash
Copy
Edit
python app.py
Usage
Upon running the application, your webcam will activate to capture hand gestures.

Perform sign language gestures in front of the camera.

The application will display the interpreted text on the screen.

The text-to-speech feature will vocalize the interpreted message.​

Project Structure
app.py: Main application script to run the sign language detection interface.

collectdata.py: Script to collect gesture data for training.

trainmodel.py: Script to train the machine learning model with collected data.

model.h5 & model.json: Pre-trained model files for gesture recognition.

function.py: Contains helper functions used across the application.​

Contributing
Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.​

License
This project is licensed under the GNU General Public License v3.0.​

