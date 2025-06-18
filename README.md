# 🤖 3DOS Automation BOT

Automate your daily grind on [3DOS](https://dashboard.3dos.io/register?ref_code=1068a0) — claim rewards, manage accounts, and rotate proxies like a farming pro 🌾

🔗 Register & Support:
- Register here → [3DOS Dashboard](https://dashboard.3dos.io/register?ref_code=1068a0)
- Referral Code: `1068a0`

---

## ✨ Features

- 📥 Auto Login & Account Info Fetching
- 🎁 Auto Daily Check-In
- 🔐 Auto API Key Generator
- 🌐 Auto Node Connection
- 🧑‍🤝‍🧑 Multi-Account Threading Support
- 🛡️ Proxy Options:
  - [1] Free Proxies from [ProxyScrape](https://proxyscrape.com/free-proxy-list)
  - [2] Private Proxies (Add to `proxy.txt`)
  - [3] No Proxy Mode
- ♻️ Auto Rotate Bad Proxies (`y/n` choice)

---

## 🧰 Requirements

- Python 3.9+
- pip (Python package manager)

---

## ⚙️ Installation

1. **Clone the Repo**
```bash
git clone https://github.com/cryptodai3/3DOS-Automation-BOT.git
````
```bash
cd 3DOS-Automation-BOT
````

2. **Install Required Libraries**

```bash
pip install -r requirements.txt
```
 OR
```bash
pip3 install -r requirements.txt
````
---

## 🛠️ Configuration

### 🔐 `accounts.json`

Use this format to load your email-password combos:

```json
[
  {
    "Email": "your_email_1",
    "Password": "your_password_1"
  },
  {
    "Email": "your_email_2",
    "Password": "your_password_2"
  }
]
```

### 🌐 `proxy.txt` (Optional)

Supports multiple formats:

```
ip:port
http://ip:port
http://user:pass@ip:port
```

If you're using proxy mode `1` or `2`, make sure to populate this file correctly.

---

## 🚀 Usage

Start the bot:

```bash
python bot.py
```
 OR
```bash
python3 bot.py
````

Follow prompts to select your proxy mode and start the automation.

---

## 🧩 Need Help?

* Open an issue on GitHub
* Reach out via [Telegram](https://t.me/cryptodai3)

---

## 🧠 Contribution

We welcome PRs, feedback, and stars ⭐
Feel free to fork and build your own farming fleet.

---

## Happy Farming! 🚀🌾

*Brought to you by [CryptoDai3](https://t.me/cryptodai3) X [YetiDAO](https://t.me/YetiDAO)*

---

## ☕ Buy Me a Coffee

* **EVM:** `0x49bb35693e9631760d2f3519e7db1dd618580a6a`
* **TON:** `UQDDYNRWZI12zMfXYBoy300ydECC5uouMUFLd_yZa6ZO4Jsm`
* **SOL:** `2PhLDFnyX8whHDMBbfGSFoLnVEsei6TYxyiqpDzPGyT1`
* **SUI:** `0xf3b008f8aac4b92195176aad27a892c565c216fd5c07bc99c70edb8394e23b59`

---

## 🔒 Safety & Support

### ⚠️ Important Disclaimer

* **Testnet Only** – This tool is designed for testnet environments only
* **No Liability** – Use at your own risk. Developers assume no responsibility
* **DYOR** – Always do your own research before using any automation tools

### 🛡️ Security Best Practices

* 🔐 Never use Main wallets
* 🚫 Never expose sensitive credentials
* 📜 Always review code before execution
* 💸 Use burner wallets with test tokens only

---

### 🙌 Support Our Work

Love this tool? Help us improve:

* ⭐ Star the repository
* 🔗 Share with your farming community
* 💎 Use our referral codes
* 💡 Contribute ideas and code

---

## 📝 License

This project is licensed under the MIT License.

---
