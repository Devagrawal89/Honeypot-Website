# 🕵️ Honeypot Website Project

A simple **Honeypot Web Application** built using **Node.js and Express** to simulate a fake login page and capture attacker information such as IP address and request data.

---

## 🚀 Features

* Fake login interface (honeypot trap)
* Captures attacker IP address
* Logs request data for analysis
* Lightweight Node.js + Express setup
* Easy to deploy and test

---

## 🛠️ Tech Stack

* Node.js
* Express.js
* HTML (Frontend)

---

## 📂 Project Structure

```
Honeypot-Website/
│── public/           # Frontend files (HTML, CSS)
│── server.js         # Main server file
│── package.json      # Dependencies
│── README.md         # Documentation
```

---

# ⚙️ Installation & Setup

## 🐧 Run on Kali Linux

### Step 1: Install Node.js

```bash
sudo apt update
sudo apt install nodejs npm -y
```

### Step 2: Clone Repository

```bash
git clone https://github.com/Devagrawal89/Honeypot-Website.git
cd Honeypot-Website
```

### Step 3: Install Dependencies

```bash
npm install
```

### Step 4: Run Server

```bash
node server.js
```

---

## 🪟 Run on Windows

### Step 1: Install Node.js

* Download from: https://nodejs.org
* Install LTS version
* Make sure **“Add to PATH”** is enabled

### Step 2: Clone or Download Project

#### Option 1 (Git):

```bash
git clone https://github.com/Devagrawal89/Honeypot-Website.git
cd Honeypot-Website
```

#### Option 2 (ZIP):

* Download ZIP from GitHub
* Extract folder
* Open CMD in that folder

---

### Step 3: Install Dependencies

```bash
npm install
```

---

### Step 4: Run Server

```bash
node server.js
```

---

## 🌐 Access Application

Open browser and go to:

```
http://localhost:3000
```

---

## 📊 Logs & Monitoring

* Attacker activity will be logged in:

  * Terminal (console logs)
  * Or custom log files (if implemented)

---

## ⚠️ Important Notes

* This project is for **educational and ethical use only**
* Do not deploy publicly without proper security measures
* Honeypots should be isolated from production systems

---

## 🧠 Future Improvements

* Store logs in database (MongoDB / MySQL)
* Add geolocation tracking (IP-based)
* Detect VPN / Proxy users
* Dashboard for monitoring attacks
* Integration with SIEM tools

---

## 👨‍💻 Author

**Dev Agrawal**

---

## 📜 License

This project is open-source and available under the MIT License.

---
