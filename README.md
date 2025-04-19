# ⚙️ Dria & Hyperbolic Node Setup Guide

> 📹 Video Tutorial: [Watch here](https://youtu.be/OIkFQk1kyn0?si=m8MIYBww3K1AaNfq)

---

## 🚨 Important Note
Dria requires sharing your private key. **Use a new wallet** for safety.

---

## 🧠 Dria Node Setup

1. **Skip this if using Google Cloud:**
```bash
sudo apt update && sudo apt upgrade
```

2. **Install Ollama:**
```bash
curl -fsSL https://ollama.com/install.sh | sh
```

3. **Install Dria Launcher:**
```bash
curl -fsSL https://dria.co/launcher | bash
```

4. **Create a screen session:**
```bash
screen -S dria
```

5. **Run the launcher:**
```bash
dkn-compute-launcher referrals
```

📌 Gemini API key: [Get it here](https://aistudio.google.com/app/apikey)

🔗 Referral Code: `u8D3yCyhKj3eWffeqoCe`

🔗 Dria Node Dashboard: [https://dria.co/edge-ai](https://dria.co/edge-ai)

---

## 🤖 Hyperbolic Node Setup

1. **Skip this if using Google Cloud:**
```bash
sudo apt update && sudo apt upgrade -y
```

2. **Install dependencies:**
```bash
sudo apt install git screen python3 python3-pip python3-venv -y
```

3. **Clone the repo and set up environment:**
```bash
git clone https://github.com/0xmoei/chatbot-app.git
cd chatbot-app
python3 -m venv venv
source venv/bin/activate
pip install requests
```

4. **Run in screen session:**
```bash
screen -S hyper
nano chatbot.py  # (Edit your keys or config here if needed)
python3 chatbot.py
```

To view logs later:

```bash
screen -r hyper
```

Dashboard: [https://app.hyperbolic.xyz/supply/earnings](https://app.hyperbolic.xyz/supply/earnings)

---
