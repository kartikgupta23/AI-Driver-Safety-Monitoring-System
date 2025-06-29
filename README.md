# 🚗 AI Driver Safety Monitoring System

An **AI-powered driver safety monitoring system** that uses computer vision and deep learning to detect driver drowsiness, distraction, and unsafe driving behavior in real time. This project helps prevent accidents by monitoring a driver's eyes, head position, and facial landmarks through a live video feed, issuing timely alerts to improve road safety.

---

## 📌 Features

- Real-time drowsiness detection by monitoring eye closure and blinking rate.
- Distraction detection by tracking head pose and facial orientation.
- Live video feed processing using webcam or in-car camera.
- Facial landmark tracking with computer vision models.
- Visual or audible alert system for unsafe conditions.
- Easily extendable to integrate with vehicles or IoT safety features.

---

## ⚙️ Tech Stack

- Python 3
- OpenCV for video capture and image processing
- Dlib / MediaPipe for facial landmark detection
- TensorFlow / Keras for deep learning models
- NumPy, Scikit-learn for data processing and analysis
- Streamlit (optional) for simple UI

---

## 🚀 How It Works

1. **Live Video Feed** — Uses a connected webcam or dashcam.
2. **Facial Landmark Detection** — Detects eyes, eyelids, head pose, and facial orientation.
3. **Behavior Analysis** — Predicts drowsiness or distraction based on eye closure, blink rate, and head movement.
4. **Alerts** — Issues a visual or audible warning when unsafe behavior is detected.

---

## 📂 Project Structure

AI-Driver-Safety-Monitoring-System/
├── models/ # Trained deep learning models
├── data/ # Datasets (if applicable)
├── main.py # Main application script
├── utils.py # Utility functions
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── examples/ # Example images or videos

---

## ⚡ Getting Started

### 1️⃣ Clone the Repository

git clone https://github.com/kartikgupta23/AI-Driver-Safety-Monitoring-System.git
cd AI-Driver-Safety-Monitoring-System
2️⃣ Install Dependencies
Create a virtual environment and install the required packages:

# Windows
python -m venv venv
venv\Scripts\activate

# Mac/Linux
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
3️⃣ Run the Application
python main.py
Or, if using Streamlit:
streamlit run main.py
🧩 Requirements
Python 3.8+

Webcam or compatible camera

(Optional) GPU for faster processing

📸 Example Output

Example: Eye landmarks and head pose detection in action.

💡 Future Improvements
Integration with IoT car systems for automatic control.

Add audio alerts or seat vibration warnings.

Support for night vision.

Monitor seatbelt usage, phone usage, or other risk factors.

Deploy on embedded devices for real car hardware.

🤝 Contributing
Contributions are welcome!

Fork this repo

Create a new branch: git checkout -b feature/YourFeature

Commit your changes: git commit -m "Add new feature"

Push to the branch: git push origin feature/YourFeature

Open a Pull Request

📜 License
This project is licensed under the MIT License — see the LICENSE file for details.

📧 Contact
Email: kartikeyagupta1435@gmail.com

LinkedIn: linkedin.com/kartikeyagupta19

If you find this project useful, please ⭐️ the repo and share your feedback!
