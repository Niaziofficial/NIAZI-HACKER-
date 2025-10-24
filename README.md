# 🚀 NIAZI-MD

**NIAZI-MD** — A friendly WhatsApp MD Bot (Baileys + Node.js)  
Owner: **NIAZI** — **+92 344 8166105**

<p align="center">
  <img src="https://i.ibb.co/WW3f9Mt9/shaban-md.jpg" alt="NIAZI-MD Banner" width="720"/>
</p>

---

## 🔗 Quick Links
- **Repo:** https://github.com/Niaziofficial/NIAZI-HACKER-  
- **Channel:** https://whatsapp.com/channel/0029VbBKWrA2v1Iu4KVE3A1H  
- **Group:** https://chat.whatsapp.com/KJ6qs3H2xC6AQPYRTaNBNm  
- **Owner (WhatsApp):** +923448166105

---

## ⚙️ One‑click / Pair Buttons

**Deploy to Heroku (one‑click):**  
[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Niaziofficial/NIAZI-HACKER-)

**Pair / Open Heroku Logs** — click this to open Heroku app logs (replace `<YOUR-HEROKU-APP>` with your app name if different):
[![Pair / Open Heroku Logs](https://img.shields.io/badge/Pair-Open%20Logs-orange)](https://dashboard.heroku.com/apps/niazi-md-bot/logs)

> ⚠️ If your Heroku app name is **not** `niazi-md-bot`, edit the above link to:
> `https://dashboard.heroku.com/apps/<YOUR-HEROKU-APP-NAME>/logs`

---

## 🧾 Features
- ✅ Sends menu image + caption (configured menu image)  
- ✅ Commands: `hi`, `menu`, `about`, `owner`, `ping`, `time`  
- ✅ Configurable via `config.json` (owner, channel, group, menuImage)  
- ✅ Ready for Heroku / Render / VPS deploy

---

## 📁 Files in repo (what you should have)
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
```
First run shows QR in terminal — scan using **WhatsApp → Linked Devices → Link a Device**. `auth_info.json` will be created — keep it safe (do not commit).

---

## 📱 How to Pair (Heroku / Logs) — Urdu + English short
1. Heroku pe app deploy kar lo (Deploy button ya Dashboard → Connect GitHub).  
2. Heroku Dashboard → app → **Resources** → ensure `worker` ON (scale = 1).  
3. App → **More → View logs**. Logs me jab bot start hota hai to **QR** ya `Scan this QR` nazar aayega.  
4. **Doosra phone** le kar WhatsApp → Settings → **Linked devices** → **Link a device** → camera se Heroku logs me dikhne wala QR scan karo.  
5. Scan hone ke baad bot connect ho jayega — ab `menu` bhejo to image + caption reply aayega.

**Agar sirf ek phone hai:** logs me jo QR text ho usko copy kar ke kisi QR-generator web page pe paste karo, PNG generate kar ke doosri device pe bhejo, wahan se scan karo.

---

## 🔐 Important Notes (zaroor padho)
- **Do not commit** `auth_info.json` to GitHub. It contains session data. `.gitignore` already has it.  
- Baileys is an **unofficial** WhatsApp library—use responsibly (spam may lead to bans).  
- Heroku dynos are ephemeral — session (`auth_info.json`) may be lost on redeploys. For persistent session use **Render (persistent disk)** or a VPS.

---

## ✍️ Edit config (quick)
To change owner / links / menu image, edit `config.json`:
```json
{
  "owner": "+923448166105",
  "channel": "https://whatsapp.com/channel/0029VbBKWrA2v1Iu4KVE3A1H",
  "group": "https://chat.whatsapp.com/KJ6qs3H2xC6AQPYRTaNBNm",
  "botName": "NIAZI-MD",
  "menuImage": "https://i.ibb.co/WW3f9Mt9/shaban-md.jpg"
}
```

---

## 👋 Need help?
README paste kar ke commit kar lo, phir yahan likh **"Done — README updated"**.  
Main phir Heroku deploy + QR pairing me step-by-step live guide kar dunga (urdu me).

---
© NIAZI-MD — Made with ❤️
