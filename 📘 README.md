
# PhishXPro 

- Ethical Phishing Simulation Tool

PhishXPro is an educational tool designed for red team simulation, social engineering awareness, and security testing. It includes templates for common platforms and allows simulation of phishing environments using PHP and Ngrok.

## 🔥 Features

- ✅ Facebook and Gmail login page simulations
- ✅ Ngrok integration for remote access
- ✅ Works on Termux and Kali Linux
- ✅ Modular and beginner-friendly
- ✅ Auto-logs credentials (for ethical testing only)

---

## ⚙️ Installation

```bash
pkg install git php python -y
git clone https://github.com/yourname/PhishXPro.git
cd PhishXPro
chmod +x phishx.sh
./phishx.sh
````

*Note: Use `apt` or `apt-get` instead of `pkg` on Kali.*

---

## 🧪 Usage

```bash
./phishx.sh
```

Then select a phishing template:

```
[1] Facebook
[2] Gmail
[3] Custom
>> Choose:
```

You will then be prompted to use **Ngrok** or not.

---

## 🗂️ Logs

Captured credentials are saved in:

```
logs/credentials.txt
```

---

## 🧠 Educational Purpose Only

This tool is for **security awareness, training, and education**. Never use it on real targets without **explicit permission**.

---

## 📌 Output Example (logs/credentials.txt)

```
Email: example@domain.com | Pass: mypassword123
Email: user@gmail.com | Pass: 123456789
```

---

## 🔒 Legal Disclaimer

We do not promote or support illegal activities. This tool is strictly for **ethical hacking and educational purposes** only. Use responsibly.

```
