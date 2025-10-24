# 🚀 NIAZI-MD

**NIAZI-MD** — Simple, friendly WhatsApp MD Bot (Baileys + Node.js)  
Owner: **+92 344 8166105**

<p align="center">
  <img src="https://i.ibb.co/WW3f9Mt9/shaban-md.jpg" alt="NIAZI-MD Banner" width="720"/>
</p>

---

## 🔗 Quick Links
- **Repo:** `https://github.com/Niaziofficial/NIAZI-HACKER-`  
- **Channel:** https://whatsapp.com/channel/0029VbBKWrA2v1Iu4KVE3A1H  
- **Group:** https://chat.whatsapp.com/KJ6qs3H2xC6AQPYRTaNBNm?mode=wwc  
- **Owner (WhatsApp):** +923448166105

---

## ⚙️ One-click / Pair Buttons

**Deploy to Heroku (one-click):**  
[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Niaziofficial/NIAZI-HACKER-)

**Pair / Open Heroku Logs** — click this to go straight to your Heroku app logs (scan QR there to link bot):  
[![Pair / Open Heroku Logs](https://img.shields.io/badge/Pair-Open%20Logs-orange)](https://dashboard.heroku.com/apps/niazi-md-bot/logs)

> ⚠️ If your Heroku app name is **not** `niazi-md-bot`, replace the URL above with:
> `https://dashboard.heroku.com/apps/<YOUR-HEROKU-APP-NAME>/logs`

---

## 🧾 Features
- ✅ Sends image menu (configured menu image)  
- ✅ Commands: `hi`, `menu`, `about`, `owner`, `ping`, `time`  
- ✅ Configurable via `config.json` (owner, channel, group, menuImage)  
- ✅ Ready for Heroku / Render / VPS deploy

---

## 📁 Files in repo
- `niazi_md.js` — main bot file (Node.js)  
- `config.json` — owner, channel, group, menuImage, botName  
- `package.json` — dependencies & start script  
- `Procfile` — `worker: node niazi_md.js` (for Heroku)  
- `.gitignore` — excludes `node_modules` and `auth_info.json`  
- `README.md` — (this file)

---

## 🛠 How to run locally (quick)
```bash
git clone https://github.com/Niaziofficial/NIAZI-HACKER-.git
cd NIAZI-MD
npm install
npm start
# or
node niazi_md.js
