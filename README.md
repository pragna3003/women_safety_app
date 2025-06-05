# 🛡️ Women Safety App (Python Version)

This is a simple yet powerful desktop-based Women Safety Application developed in Python using Tkinter. The app is designed to help women in emergency situations by triggering a loud siren, fetching the user’s location, and opening a pre-filled emergency email with location details.

---

## 🚀 Features

- ✅ One-click **SOS** button
- 🔊 **Siren sound** to alert nearby people
- 📍 **Simulated location** fetching using `geopy`
- 📧 **Emergency email** trigger via default mail app
- 🖥️ Simple and intuitive **GUI** using Tkinter

---

## 🛠 Tech Stack

- Python 3.x
- Tkinter (GUI)
- `geopy` (Location lookup)
- `playsound` (Alarm sound)
- `webbrowser` (Launch emergency email)

---

## 📁 Project Structure

WomenSafetyApp_Python/
├── assets/
│ └── siren.mp3 # Siren audio file (replace with real sound)
├── src/
│ ├── main.py # Main application GUI
│ └── modules.py # SOS trigger logic and location fetch
├── README.md

yaml
Copy
Edit

---

## 🔧 How to Run

1. **Install Dependencies**
   ```bash
   pip install geopy playsound
Add Siren File
Place a loud siren audio file in the assets/ folder and name it siren.mp3.

Run the App

bash
Copy
Edit
python src/main.py
📌 Notes
This app uses a hardcoded location via the geopy geocoder for demonstration. You can modify it to use IP-based geolocation or integrate GPS modules.

The emergency email is triggered via the default system mail client using a mailto: link.

