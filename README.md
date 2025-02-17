Automation of Garbage Detection
Images of Frontend
Replace with images of frontend for the garbage detection system.

<img width="500" alt="Screenshot 2023-05-04 at 2 10 46 PM" src="https://user-images.githubusercontent.com/132324275/236158607-dfbe6d16-ecb2-46ba-83ee-a36da83e9b3e.png"> <img width="500" alt="Screenshot 2023-05-04 at 2 13 17 PM" src="https://user-images.githubusercontent.com/132324275/236158649-5da4c770-a59d-407a-8567-5b96798ba8f1.png"> <img width="500" alt="Screenshot 2023-05-04 at 2 13 27 PM" src="https://user-images.githubusercontent.com/132324275/236158642-16567aa5-bc9f-4a40-ba9c-8a6f911ee0b5.png"> <img width="500" alt="Screenshot 2023-05-04 at 2 14 06 PM" src="https://user-images.githubusercontent.com/132324275/236158985-efc749d4-2d27-4c42-9e86-3f233f4d9c40.png">
Python Work
This is a Python script that detects garbage in video frames and saves the corresponding images to a specified folder. Additionally, it sends the saved images to a server using HTTP requests.

Prerequisites
This script requires the following Python libraries to be installed:

opencv
numpy
requests
os
sqlite3
flask
flask_cors
pandas
config
Getting Started
To get started, follow these steps:

Clone the repository to your local machine.

Create an additional folder inside the root folder named core, and then create a media folder inside it for storing the images.

Install the required libraries using pip:

bash
Copy
Edit
pip install opencv numpy requests sqlite3 flask flask_cors pandas config
Save photos in the internal directory of your machine. Using Flask, store the images in an SQLite3 database table.

Run the API and make the user in the API:

Username: admin_user
Email: admin@gmail.com
Password: admin
After starting the API, navigate to the following URL in your browser:

plaintext
Copy
Edit
http://127.0.0.1:5000/admin/admin@gmail.com/admin
Update the save_folder variable in the script to specify the folder where you want to save the detected garbage images.

Update the send_img function in the script to specify the URL of the server where you want to send the images.

Set your path to store the images in the core/media folder. The video file name is IMG_1891.mp4.

Run the script using the following commands:

bash
Copy
Edit
python api.py
python garbage_detection.py
License
This script is distributed under the GNU General Public License.

Acknowledgements
This project uses the pre-trained haarcascade_garbage.xml file from the OpenCV GitHub repository for detecting garbage in the video frames.

React JS Work
This is a React JS program that demonstrates the use of various React components and libraries. The program displays a simple user interface that allows users to perform various actions, such as viewing detected garbage images, filtering results, and displaying statistics.

Requirements
This app requires an internet connection for using React Bootstrap and some offline images.

Installation of React JS:
Create a web app using the terminal:

bash
Copy
Edit
npx create-react-app garbage-detection
cd garbage-detection
npm start
Install necessary libraries:

bash
Copy
Edit
npm install axios react-toastify modal button react-router-dom
Other dependencies required for your project can be installed as necessary.

Features:
This program demonstrates the following features of React JS:

Components: The program is built using various React components, such as buttons, forms, and charts.
State management: The program uses state to manage the data displayed on the user interface.
Props: The program passes data between components using props.
Hooks: The program uses various React hooks, such as useState and useEffect.
React Router: The program uses React Router to handle navigation between different pages.
