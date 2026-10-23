# 🌱 Mitti Mitra

**AI-Powered Smart Farming and Gesture-Based Irrigation System**

Mitti Mitra is an accessible smart-farming prototype designed to help farmers monitor farm conditions and control irrigation through a simple dashboard and hand gestures.

## ✨ Features

- **Gesture-Based Irrigation:** Open palm to turn irrigation ON and closed fist to turn it OFF.
- **Farm Dashboard:** View soil moisture, temperature, humidity, water usage, and irrigation status.
- **Backend API:** Connects the frontend to a backend server.
- **Database Integration:** Uses MySQL to store farm data, sensor readings, alerts, and irrigation events.
- **Accessible Design Goal:** Aims to make farming technology easier to use for farmers with disabilities.

## 🛠️ Technologies Used

- React
- Vite
- JavaScript
- Node.js
- Express.js
- MySQL
- MediaPipe Tasks Vision
- HTML and CSS

## 📁 Project Structure

```text
mitti-mitra/
├── client/       # React frontend
├── server/       # Express backend and database connection
├── .gitignore
└── README.md
```

## 🚀 Getting Started

### Prerequisites

Install Node.js and MySQL. Git is recommended for version control.

### 1. Start the backend

Open a terminal:

```bash
cd server
npm install
npm run dev
```

Configure your database connection using a local `server/.env` file. Never upload passwords or secrets to GitHub.

### 2. Start the frontend

Open a second terminal:

```bash
cd client
npm install
npm run dev
```

Open the local URL shown by Vite in your browser.

### 3. Test gesture control

Allow camera access when prompted. Show an open palm to turn irrigation ON or a closed fist to turn it OFF.

## ⚠️ Important Note

This is a software prototype. Sensor readings may be simulated, and irrigation control updates the software state. Physical sensors and a real irrigation pump are not connected unless separately integrated.

## 🔮 Future Enhancements

- Connect real soil-moisture and temperature sensors.
- Integrate physical pump control.
- Add weather forecasting and crop recommendations.
- Improve gesture recognition under different lighting conditions.
- Add multilingual voice assistance and offline support.

## 👩‍💻 Project

**Mitti Mitra** — making smart farming more accessible through AI and technology.
