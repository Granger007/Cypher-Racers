# CypherRacers - Multiplayer-Car-Racing Game secured via SSL

A fun and interactive **Multiplayer Car Racing** game built using **Python**, **Socket Programming**, and **SSL encryption** for secure client-server communication.

---

## 🚀 Features

* Real-time multiplayer racing
* Coin collection along the racing track
* Nitro Booster ("N") activated after collecting 5 coins for an insane speed boost
* Confetti celebrations upon winning
* Secure client-server architecture using SSL
* Custom car images and graphics
* Lightweight and easy to run

---

## 💡 How It Works

This project consists of a **server** (`server.py`) and **client** (`client.py`) setup:

* The server handles player connections and synchronizes game data.
* Each client sends and receives car positions via encrypted socket communication.

### Coin & Nitro Mechanic:

* Players collect coins scattered along the track.
* Upon collecting **5 coins**, the player unlocks an **"N" Nitro Booster**.
* Nitro grants a temporary but massive speed increase, ideal for overtaking opponents.

### Celebration Feature:

* Confetti animations celebrate the winner at the end of the race.

### Security Emphasis:

* Communication is protected using **SSL encryption**.
* Uses `cert.pem` (certificate) and `key.pem` (private key) to ensure **authentication**, **integrity**, and **confidentiality**.
* Clients cannot connect unless verified with the SSL cert/key pair, ensuring a **secure multiplayer environment**.

---

## 🔧 Installation

### Requirements:

* Python 3.x

### Clone the repository:

```bash
git clone https://github.com/Granger007/Multiplayer-Car-Racing.git
cd Multiplayer-Car-Racing
```

---

## 🛠️ Usage

### 1. Start the Server:

```bash
python server.py
```

### 2. Run the Clients:

Run in separate terminals or systems:

```bash
python client.py
```

Each client will connect to the server and control a car using keyboard inputs.

---

## 🌟 Assets

* `car1.png` and `car2.png` are the car images used in the game.
* `cert.pem` and `key.pem` are the SSL certificate and key.

---

## 📈 Future Improvements

* Add lap tracking and scoring
* GUI to select cars
* Add sound effects and background music
---


