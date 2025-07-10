
# 🌍 Real-Time Geo Tracker

A real-time location tracking app built with **Node.js**, **Express**, **Socket.IO**, and **Leaflet.js**. It allows users to share their live location and view other connected users on a map in real time.

##  Features

-  Live geolocation tracking via browser
-  Real-time updates using WebSockets
-  Interactive map with Leaflet.js
-  Automatically removes disconnected users
-  Works on multiple devices or tabs simultaneously

---

##  Live Demo

🔗 [](https://your-deployment-url.onrender.com)  

---

## Tech Stack

- **Node.js** – backend runtime
- **Express.js** – web framework
- **Socket.IO** – real-time communication
- **EJS** – template engine
- **Leaflet.js** – interactive maps
- **HTML/CSS/JS** – frontend

---

##  How It Works

1. User grants location access
2. App emits real-time position via Socket.IO
3. Server rebroadcasts location to all users
4. Map updates user markers live using Leaflet
5. Disconnected users' markers are removed

---

##  Setup Instructions (Local)

### 1. Clone the Repository

```bash
git clone https://github.com/varsha-0110/Geo-Tracker.git
cd Geo-Tracker
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Run the App

```bash
npm start
```

### 4. View in Browser

```
http://localhost:4000
```

---

##  Deployment (Render)

1. Push repo to GitHub
2. Go to [https://render.com](https://render.com)
3. Click **New Web Service**
4. Choose your repo
5. Set:
   - Build Command: `npm install`
   - Start Command: `npm start`
6. Get your live deployed backend link

---


