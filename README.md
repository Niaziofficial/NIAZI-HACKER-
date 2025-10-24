🚀 NIAZI-MD

> **NIAZI-MD** — WhatsApp MD Bot (Baileys + Node.js)  
> Friendly, fast, and ready to deploy.  
> Owner: **+92 344 8166105**

---

<p align="center">
  <img src="https://i.ibb.co/WW3f9Mt9/shaban-md.jpg" alt="NIAZI-MD Banner" width="720"/>
</p>

---

## 🔥 Quick Links
- **Repo:** `https://github.com/Niaziofficial/NIAZI-HACKER-`  
- **Channel:** https://whatsapp.com/channel/0029VbBKWrA2v1Iu4KVE3A1H  
- **Group:** https://chat.whatsapp.com/KJ6qs3H2xC6AQPYRTaNBNm?mode=wwc  
- **Owner (WhatsApp):** +923448166105

---

## ⚙️ Features
- ✅ Multi-device (Baileys) WhatsApp bot  
- ✅ Auto reply: `hi`, `menu`, `about`, `owner`, `ping`, `time`  
- ✅ Menu sends image + caption (menu image configured)  
- ✅ Easy config via `config.json`  
- ✅ Ready for Heroku / Render / VPS deploy

---

## 📦 Files in repo
- `niazi_md.js` — Main bot file (Node.js)  
- `config.json` — Owner/channel/group/menuImage settings  
- `package.json` — NPM scripts & deps  
- `Procfile` — Heroku worker: `worker: node niazi_md.js`  
- `.gitignore` — `node_modules`, `auth_info.json` ignored  
- `README.md` — (this file)

---

## 🚀 One-click Deploy (Heroku)
[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Niaziofficial/NIAZI-HACKER-)

**OR** Deploy to Render (recommended for persistent disk):
[![Deploy to Render](https://img.shields.io/badge/Deploy-Render-blue)](https://render.com)

> **Note:** Heroku dynos are ephemeral — `auth_info.json` may be lost on restarts. For persistent session use Render or a VPS.

---

## 🛠 How to run locally (quick)
```bash
# clone (if not already)
git clone https://github.com/Niaziofficial/NIAZI-HACKER-.git
cd NIAZI-MD

# install
npm install

# start
npm start
# or
node niazi_md.js
[![Pair / Open Heroku Logs](https://img.shields.io/badge/Pair-Open%20Logs-orange)](https://dashboard.heroku.com/apps/niazi-md-bot/logs)
