<div align="center" id="toc">
<ul style="list-style: none">
<summary>
 <h1>Python Chat App</h1>
</summary>
</ul>
</div>

<br>

A real-time group chat app built with Python (Flask) and JavaScript, using Socket.io for instant communication. It runs in a Python virtual environment and alerts all users when someone joins, leaves, or changes their name.


## 🚀 Technologies Used 🚀

- **Python**: owers the backend logic and server-side functionality.
- **JavaScript**: Manages client-side interactions and dynamic behavior.
- **Flask**: Micro web framework for routing and backend structure.
- **Socket.io**: Enables real-time bidirectional communication via events.
- **Virtualenv**: Isolates Python environment to manage dependencies cleanly.

## 📑 Key Features 📑

- **Real-time messaging**: Instantly sends and receives messages between users in the groupchat.
- **Socket connections**: Maintains persistent client-server communication using events.
- **Event handling**: Responds to custom chat events like join, message, or name change.
- **Flask routing**: Handles URL endpoints and serves the necessary pages.

## 🔧 Installation & Setup 🔧

1. **Clone the repository**:
```bash
git clone https://github.com/Isaiahpeoples/PythonChatApp.git
```

2. **Install dependencies**:
```bash
pip install flask fl
```

3. **Start the development server**:
```bash
python .\app.py
```

4. **Deployment commands for installation/run/build**:
```bash
pip install -r requirements.txt

gunicorn --worker-class eventlet -w 1 wsgi:app
```

### ⭐️ Support ⭐️
If you found this project helpful or interesting, please give it a ⭐️! Your support helps to grow the project and boosts visibility. Thank you!
