 <p align="center">
  <img src="https://img1.pixhost.to/images/11137/674052079_hoshino-assistant.jpg" width="100%" />
</p>

<h1 align="center">🤖 Yuzuhira WhatsApp Bot</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&center=true&vCenter=true&width=600&lines=Modern+WhatsApp+Bot;Stable+%7C+Clean+%7C+Production+Ready;Powered+by+Baileys+Latest;Developed+by+Kayzen+Izumi" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-20.x-green?style=for-the-badge&logo=node.js" />
  <img src="https://img.shields.io/badge/Baileys-Latest-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ESM-Enabled-purple?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Stable-success?style=for-the-badge" />
  <img src="https://img.shields.io/github/license/Kayzen-dev-tech/yuzuhira-bot?style=for-the-badge" />
</p>

---

## ✨ About

**Yuzuhira WhatsApp Bot** adalah base bot WhatsApp berbasis **Node.js (ESM)** menggunakan **@whiskeysockets/baileys versi terbaru**.  
Dirancang untuk **stabilitas tinggi, clean code, dan deployment multi-platform**.

Cocok untuk:
- 🤖 AI Assistant
- 💰 Store & QRIS Payment
- 👥 Bot komunitas
- ⚙️ Automation WhatsApp
- 🚀 Production server

---

## 🖼️ Preview

<p align="center">
  <img src="https://img1.pixhost.to/images/11138/674055651_hoshino-assistant.jpg" width="220" />
</p>

<p align="center">
  <b>Yuzuhira – AI Assistant Mode</b>
</p>

---

## 📸 Screenshots

<p align="center">
  <img src="https://placehold.co/300x600?text=Menu+Bot" />
  <img src="https://placehold.co/300x600?text=AI+Chat" />
  <img src="https://placehold.co/300x600?text=QRIS+Payment" />
</p>

> Ganti placeholder dengan screenshot asli bot setelah running.

---

## 🚀 Features

- Pairing Code Manual (Tanpa QR)
- ECMAScript Modules (ESM)
- Auto Reconnect & Anti Down
- Modular Plugin System
- AI Assistant (Yuzuhira)
- QRIS Payment (Pakasir)
- Clean Code (No Comments)
- Multi Platform Ready

---

## 📦 Requirements

- Node.js v18+ (Recommended v20)
- npm / pnpm / yarn
- Akun WhatsApp aktif

---

## 📁 Project Structure

.
├── index.js
├── config.js
├── package.json
├── session/
└── plugins/
├── menu.js
├── owner.js
├── ping.js
├── pakasir.js
└── yuzuhira.js

yaml
Salin kode

---

## 🔐 Pairing Code

1. Jalankan bot
2. Masukkan nomor WhatsApp `628xxxx`
3. WhatsApp → Perangkat Tertaut
4. Masukkan pairing code
5. Bot siap digunakan

---

## 🖥️ Deployment

### ▶ Pterodactyl
npm start

```yaml
- Node.js 18+
- Auto Restart ON
- Jangan hapus folder `session`
```

---

### ▶ VPS / Dedicated Server
```bash
git clone https://github.com/Kayzen-dev-tech/yuzuhira-bot.git
cd yuzuhira-bot
npm install
npm start
```

Gunakan PM2:
```bash
Salin kode
pm2 start index.js --name yuzuhira
pm2 save
```

### ▶ Termux (Android)
```bash
Salin kode
pkg install nodejs git
git clone https://github.com/Kayzen-dev-tech/yuzuhira-bot.git
cd yuzuhira-bot
npm install
npm start
```

### ▶ Railway
```txt
Deploy from GitHub
Start Command: npm start
Pairing via Logs
```

### ▶ Render
```txt
Build: npm install
Start: npm start
Runtime: Node.js 20
```

### 🧠 Commands
| Command    | Description  |
| ---------- | ------------ |
| `menu`     | Main menu    |
| `ping`     | Bot latency  |
| `owner`    | Owner info   |
| `yuzuhira` | AI Assistant |
| `pakasir`  | QRIS Payment |


### 🛡️ Security
```txt
Jangan bagikan folder session
Simpan API key di ENV untuk production
Gunakan private repository jika perlu
```

## 👤 Developer

| Field   | Detail |
|--------|--------|
| Name   | Kayzen Izumi |
| GitHub | https://github.com/Kayzen-dev-tech |
| Website | https://kayzen-izumi.vercel.app |
| API    | https://kayzen-api.my.id |


## 📄 [License](LICENCE)

<p align="center"> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&pause=1000&center=true&vCenter=true&width=500&lines=Clean+Code;Stable+Connection;Scalable+Architecture;Yuzuhira+WhatsApp+Bot" /> </p>
