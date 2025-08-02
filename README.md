# 🌦️ SmartWeather Extension
> Real-time weather in your new tab, spoken in Thai.  
> **Manifest V3 · TTS · Minimal UI**

![release](https://img.shields.io/github/v/release/your-username/SmartWeather-Extension)
![license](https://img.shields.io/github/license/your-username/SmartWeather-Extension)
![issues](https://img.shields.io/github/issues/your-username/SmartWeather-Extension)

---

## ✨ Features
- Live weather data from a public API  
- Text-to-Speech (Thai voice) for audible forecasts  
- Responsive, modern UI ready for future expansion  
- Built on Manifest V3 for security and performance

---

## 🖥️ Demo
<p align="center">
  <img src="docs/screenshot_popup.png" width="420" alt="Popup screenshot">
</p>

---

## 📦 Tech Stack

| Layer            | Technology                                   |
| ---------------- | -------------------------------------------- |
| Core Languages   | HTML · CSS · JavaScript (ES Modules)         |
| Runtime          | Chrome Extension APIs (Manifest V3)          |
| Data Provider    | OpenWeatherMap API (REST)                    |
| Voice Output     | Web Speech API (SpeechSynthesis)             |
| Dev Ops          | Git · PowerShell · GitHub Actions (optional) |

---

## 🚀 Getting Started

   ```bash
   git clone https://github.com/your-username/SmartWeather-Extension.git
   cd SmartWeather-Extension
   
1. Create src/secrets.js
	 // src/secrets.js (git-ignored)
	 export const OPEN_WEATHER_KEY = 'YOUR_API_KEY';

2. Open Chrome → chrome://extensions/ • Enable Developer mode • Click Load unpacked → select the project folder

3. Reload after each change; Chrome reflects updates instantly.

-----------------------------------

📁 Project Structure

SmartWeather-Extension/
├─ manifest.json
├─ icons/
│  └─ icon128.png
├─ popup/
│  ├─ popup.html
│  └─ popup.js
├─ modules/
│  ├─ weather.js
│  └─ tts.js
├─ assets/
│  └─ style.css
├─ docs/                # screenshots, GIFs
├─ src/secrets.js       # git-ignored
└─ README.md

-----------------------------------

🛡️ SECURITY & PRIVACY

	🔒	src/secrets.js is excluded via .gitignore

	🔒	Only minimal permissions (geolocation, ttsEngine) requested

	🔒	Graceful fallback and rate-limit handling when API is unreachable

-----------------------------------

🗺️ ROADMAP

	✅ Basic weather popup — version 1.0 released

	🟡 Add °C/°F unit toggle in settings — planned for v1.1

	🟡 Voice selection + rate controls — planned for v1.2

	🔲 Air-Quality Index (AQI) module — idea for v1.3

	🔲 Dark-mode UI toggle — idea for v1.4

	🔲 Customizable update interval — future enhancement

	🔲 Option to auto-read on weather change — enhancement planned

	🟢 Refactor modules for easier scalability — ongoing improvement

----------------------------------

🤝 CONTRIBUTING

Pull requests are welcome. For major changes, open an issue first to discuss your ideas.

-----------------------------------

📄 LICENSE

Distributed under the MIT License. See the LICENSE file for details

-----------------------------------

