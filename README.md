<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B6B,100:4ECDC4&height=200&text=FileTo%20Stream&fontSize=50&fontColor=fff&animation=fadeIn&fontAlignY=40&desc=Telegram%20File%20To%20Link%20via%20Cloudflare%20Workers&descAlignY=55&descSize=15"/>
</div>



<p align="center">
  <a href="https://github.com/salman-dev-app/FileTo-Stream">
    <img src="https://readme-typing-svg.demolab.com?font=Tagesschrift&size=25&duration=2000&pause=800&color=F7F7F7&background=FF001400&center=true&vCenter=true&multiline=true&width=500&height=80&lines=File+To+Link+Bot;Powered+by+Cloudflare+Workers" alt="Typing SVG" />
  </a>
</p>



<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-ES2022-FF6B6B?style=for-the-badge&logo=javascript&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloudflare-Workers-4ECDC4?style=for-the-badge&logo=cloudflare&logoColor=white" />
  <img src="https://img.shields.io/badge/Platform-Telegram-00D9FF?style=for-the-badge&logo=telegram&logoColor=white" />
  <img src="https://img.shields.io/github/last-commit/salman-dev-app/FileTo-Stream?style=for-the-badge&color=00D9FF&label=LAST%20UPDATED&logo=github&logoColor=white" />
</p>

---

<div align="center">
  <h3>
    <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Glowing%20Star.png" alt="Star" width="25" height="25" style="vertical-align: middle;" />
    A zero-cost, serverless Telegram bot powered by Cloudflare Workers that converts Telegram files into direct streamable/downloadable links instantly.
  </h3>
</div>

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Globe%20Showing%20Americas.png" alt="Globe" width="30" height="30" style="vertical-align: middle;" /> Quick Links

<p align="center">
  <a href="mailto:mdsalmanhelp@gmail.com">
    <img src="https://img.shields.io/badge/Contact-Send_Email-FF6B6B?style=for-the-badge&logo=minutemailer&logoColor=white" />
  </a>
  <a href="https://github.com/salman-dev-app/FileTo-Stream">
    <img src="https://img.shields.io/badge/Source-View_Code-00D9FF?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Laptop.png" alt="Laptop" width="30" height="30" style="vertical-align: middle;" /> Core Features & Capabilities

<div align="center">

### Project Highlights

</div>

<p><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Check%20Mark%20Button.png" width="18" height="18" style="vertical-align: middle;" /> <strong>Serverless</strong> — Runs entirely on Cloudflare Workers — zero server costs</p>
<p><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Check%20Mark%20Button.png" width="18" height="18" style="vertical-align: middle;" /> <strong>Instant Links</strong> — Convert any Telegram file to a direct streamable link</p>
<p><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Check%20Mark%20Button.png" width="18" height="18" style="vertical-align: middle;" /> <strong>Secured</strong> — Bot secret and owner-only access controls</p>
<p><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Check%20Mark%20Button.png" width="18" height="18" style="vertical-align: middle;" /> <strong>Channel Storage</strong> — Uses a private Telegram channel as file storage backend</p>
<p><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Check%20Mark%20Button.png" width="18" height="18" style="vertical-align: middle;" /> <strong>Public/Private Mode</strong> — Toggle between public bot or private use with a config flag</p>
<p><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Symbols/Check%20Mark%20Button.png" width="18" height="18" style="vertical-align: middle;" /> <strong>Zero Latency</strong> — Cloudflare edge network delivers sub-100ms response times</p>

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Wrench.png" alt="Wrench" width="30" height="30" style="vertical-align: middle;" /> Tech Stack

<div align="center">

### Backend
<img src="https://skillicons.dev/icons?i=js,cloudflare&theme=dark" />

<br/>### Tools
<img src="https://skillicons.dev/icons?i=git,github&theme=dark" />

<br/>
</div>

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Rocket.png" alt="Rocket" width="30" height="30" style="vertical-align: middle;" /> Installation & Setup

```javascript
// 1. Clone and configure worker
git clone https://github.com/salman-dev-app/FileTo-Stream.git

// 2. Edit variables in worker.js
const BOT_TOKEN   = "YOUR_BOT_TOKEN";
const BOT_SECRET  = "YOUR_SECRET";
const BOT_OWNER   = 123456789;        // Your Telegram ID
const BOT_CHANNEL = -100123456789;    // Storage channel ID
const PUBLIC_BOT  = false;

// 3. Deploy to Cloudflare Workers
wrangler publish
```

---

<div align="center">
  <h2>
    <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Briefcase.png" alt="Briefcase" width="35" height="35" style="vertical-align: middle;" />
    Let's Build Together
  </h2>
</div>

<p align="center">
  <a href="mailto:mdsalmanhelp@gmail.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=63A4FF&center=true&vCenter=true&width=500&lines=Available+for+New+Opportunities;Open+to+Freelance+Contracts;Let's+Build+Something+Amazing!" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="mailto:mdsalmanhelp@gmail.com">
    <img src="https://img.shields.io/badge/Hire_Me-Send_an_Email-63A4FF?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Scroll.png" alt="Scroll" width="30" height="30" style="vertical-align: middle;" /> License

<div align="center">
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge&logo=open-source-initiative&logoColor=white" />
  </a>
</div>

<p align="center">
  This project is licensed under the MIT License — feel free to use, modify, and contribute.
</p>

---

<footer align="center">
  <p>© 2024-2026 Md Salman Biswas · All rights reserved</p>
  <p>
    <a href="https://github.com/salman-dev-app">
      <img src="https://img.shields.io/badge/Profile_Status-Active-4ECDC4?style=flat" alt="Status" style="vertical-align: middle;">
    </a>
  </p>
  <p>Engineered by <a href="https://github.com/salman-dev-app">Md Salman Biswas</a></p>
</footer>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B6B,100:4ECDC4&height=120&section=footer"/>