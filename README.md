<div align="center" id="toc">
  <ul style="list-style: none">
	<summary>
  	<h1>💬 Python Chat App 💬</h1>
	</summary>
  </ul>
</div>

<div align="center">

[![Version](https://img.shields.io/badge/version-2.0.0-purple.svg)](https://github.com/Isaiahpeoples/PythonChatApp)
[![Built With](https://img.shields.io/badge/Built_with-Flask-purple)](https://flask.palletsprojects.com/)
[![Socket.io](https://img.shields.io/badge/Socket.io-Enabled-purple)](https://socket.io/)
[![Python](https://img.shields.io/badge/Python-3.11+-purple.svg)](https://www.python.org/)
[![Live](https://img.shields.io/badge/Live-Preview-brightgreen)](https://pythonchatapp-production.up.railway.app/)

</div>
<br/>

## 💡 Project Overview

**Python Chat App** is a simple yet effective real-time group messaging platform built with **Flask** and **Socket.io**. This web-based chat room supports multi-user connections, name changes, join/leave announcements, and persistent messaging via WebSockets. It’s perfect for learning event-based communication using Python and JavaScript.

<br/>

## 🚀 Technologies Used

| Technology 	| Description                                                          	|
|----------------|--------------------------------------------------------------------------|
| **Python** 	| 🐍 Handles backend logic and routing.                                	|
| **Flask**  	| ⚙️ Lightweight framework for API and server logic.                    	|
| **JavaScript** | 💻 Manages dynamic front-end interactions.                           	|
| **Socket.io**  | 🔁 Enables real-time bidirectional event-based communication.        	|
| **Virtualenv** | 🧪 Manages isolated Python environments for clean dependency handling.   |

<br/>

## 📸 Project Screenshot

![Python Chat Preview](https://online-project-images.s3.us-east-2.amazonaws.com/pythonchatapp/PythonChatApp-2.png)

*A real-time chat interface showing user messages and join/leave events.*

<br/>

## 📑 Key Features

- 📢 **Real-Time Messaging** – Broadcasts messages instantly to all connected users.
- 🧠 **Custom Event Handling** – Handles user actions like name changes, joins, and exits.
- 🔌 **Socket-Based Communication** – Keeps a live connection open via WebSockets.
- 🔧 **Minimal Flask Backend** – Uses clean Flask routes and SocketIO server logic.

<br/>

## 🔧 Installation & Setup 🔧

1. **Clone the repository**:
```bash
git clone https://github.com/Isaiahpeoples/PythonChatApp.git
cd PythonChatApp
```

2. **Create & activate virtual environment**:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install dependencies**:
```bash
pip install flask fl
```

4. **Start the development server**:
```bash
python .\app.py
```

5. **Optional: Deploy with Gunicorn + Eventlet**:
```bash
pip install -r requirements.txt

gunicorn --worker-class eventlet -w 1 wsgi:app
```

<br/>

## 🌐 Live Demo

Check out the live version:  
👉 [Python Chat App Live Demo](https://pythonchatapp-production.up.railway.app/)

<br/>

### ⭐️ Support ⭐️
If you found this project helpful or interesting, please give it a ⭐️! Your support helps to grow the project and boosts visibility. Thank you!
