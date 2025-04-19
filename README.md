AI-Powered Waste Management Classifier App

An intelligent mobile/web-based application that uses a **Convolutional Neural Network (CNN)** to classify waste as **biodegradable** or **non-biodegradable**. The system supports real-time image capture**, provides **classification feedback**, and includes a **smart chatbot (Jarvis)** to assist users in tracking waste processing and learning about proper segregation.

---

Features

- AI Waste Classifier**: Uses a trained CNN to identify the type of waste from uploaded images or camera input.
- Mobile/Web App Integration**: Classifier is embedded in an easy-to-use app interface.
- Jarvis – Chatbot Assistant**: Built with Dialogflow to answer user queries and track waste orders using tracking ID.
- Order Tracking**: Users can check the status of their submitted waste through a unique tracking ID.
- Eco-Education Support**: Helps users learn the best practices for waste segregation and disposal.

---

Tech Stack

| Component              | Technology Used                        |
|------------------------|----------------------------------------|
| ML Model               | CNN (TensorFlow / Keras)               |
| Image Processing       | OpenCV, Pillow                         |
| Backend API            | Flask / FastAPI                        |
| Frontend               | React Native / Flutter / Android SDK  |
| Chatbot Integration    | Google Dialogflow + Firebase / Webhook |
| Database (if any)      | Firestore / MongoDB                    |
| Deployment (optional)  | Heroku / Render / Localhost            |

---

Installation & Setup

```bash
 Clone the repo
git clone https://github.com/yourusername/waste-classifier-app.git
cd waste-classifier-app

 Setup virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install dependencies
pip install -r requirements.txt

Run the Flask backend
python app.py
