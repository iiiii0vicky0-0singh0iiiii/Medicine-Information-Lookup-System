<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,3,30&height=220&section=header&text=Medicine%20Lookup%20System&fontSize=40&fontColor=fff&animation=fadeIn&fontAlignY=35&desc=Instant%20Drug%20Intelligence%20%7C%20Real-Time%20API%20%7C%20Clean%20Web%20Interface&descAlignY=58&descSize=15" width="100%"/>

</div>

<div align="center">

[![HTML5](https://img.shields.io/badge/HTML5-Frontend-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Styling-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-Logic-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![PHP](https://img.shields.io/badge/PHP-Backend-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://www.php.net)
[![Apache](https://img.shields.io/badge/Apache-Server-D22128?style=for-the-badge&logo=apache&logoColor=white)](https://httpd.apache.org)
[![License](https://img.shields.io/badge/License-MIT-22C55E?style=for-the-badge)](LICENSE)

<br/>

> **Search. Discover. Stay Informed.**
> A lightweight, real-time medicine lookup system that fetches accurate drug information from trusted public medical APIs — displayed through a clean, responsive web interface.

<br/>

**[🌐 Live Demo](#-live-demo)** &nbsp;·&nbsp; **[⚙️ Quick Setup](#️-installation--setup)** &nbsp;·&nbsp; **[🐛 Report Bug](https://github.com/iiiii0vicky0-0singh0iiiii/medicine-lookup-system/issues)** &nbsp;·&nbsp; **[💡 Request Feature](https://github.com/iiiii0vicky0-0singh0iiiii/medicine-lookup-system/issues)**

</div>

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Live Demo](#-live-demo)
- [Features](#-features)
- [How It Works](#-how-it-works)
- [Tech Stack](#️-tech-stack)
- [API Reference](#-api-reference)
- [Project Structure](#-project-structure)
- [Installation & Setup](#️-installation--setup)
- [Screenshots](#-screenshots)
- [Use Cases](#-use-cases)
- [Roadmap](#️-roadmap)
- [Contributing](#-contributing)
- [Disclaimer](#️-disclaimer)
- [License](#-license)
- [Contact](#-contact)

---

## 🔍 Overview

Access to reliable, fast drug information is critical — for patients, caregivers, pharmacists, and developers alike. The **Medicine Lookup System** bridges the gap between complex medical databases and everyday users by providing:

- ⚡ **Instant search** — type a medicine name and get results in milliseconds
- 📋 **Comprehensive drug data** — dosage, uses, side effects, interactions, and more
- 🌐 **Real-time accuracy** — data pulled live from trusted public medical APIs
- 📱 **Works on all devices** — fully responsive, mobile-first design
- 🏠 **Run locally or deploy** — works on XAMPP/localhost and production servers

```
User Types Medicine Name
         │
         ▼
  JavaScript captures input
         │
         ▼
  PHP backend sends API request
         │
         ▼
  Public Medical API responds
         │
         ▼
  Parsed & rendered in browser
         │
         ▼
  Clean card-based UI displayed ✅
```

---

## 🌐 Live Demo

<div align="center">

> 🔗 **[Launch Live App →](#)** *(Deployed — click to explore)*

| 🔎 Search View | 💊 Drug Details | 📱 Mobile View |
|---|---|---|
| Type any medicine name | See full drug profile | Fully responsive layout |

</div>

---

## ✨ Features

### Core Features

| Feature | Description |
|---|---|
| 🔍 **Medicine Search** | Search any drug by brand name or generic name |
| 💊 **Drug Information** | Uses, dosage, side effects, warnings, interactions |
| ⚡ **Real-Time Retrieval** | Live API calls — always up-to-date data |
| 📱 **Responsive Design** | Works on desktop, tablet, and mobile |
| 🎨 **Clean UI** | Minimal, card-based layout for easy reading |
| 🚀 **Lightweight** | No heavy frameworks — fast load times |
| 🌍 **Cross-Platform** | Runs on XAMPP locally or any Apache server |

### What Drug Information Is Shown

```
💊 Drug Name          — Brand & generic name
📋 Drug Class         — Category / classification
🩺 Uses               — Indications and medical conditions treated
⚠️  Side Effects       — Common and serious adverse effects
🔬 Dosage             — Recommended doses and forms
🚫 Contraindications  — When NOT to use the medicine
🔄 Drug Interactions  — What to avoid combining with
🏭 Manufacturer       — Company that produces it
📦 Available Forms    — Tablet, capsule, syrup, injection, etc.
```

---

## 🔄 How It Works

```
┌──────────────────────────────────────────────────────────────┐
│                        FRONTEND (HTML/CSS/JS)                 │
│   User types medicine name  →  JS captures keypress/submit   │
└──────────────────────────────────────┬───────────────────────┘
                                       │  AJAX / Fetch API
┌──────────────────────────────────────▼───────────────────────┐
│                        BACKEND (PHP)                          │
│   Receives query  →  Validates input  →  Calls Medical API   │
└──────────────────────────────────────┬───────────────────────┘
                                       │  HTTP Request
┌──────────────────────────────────────▼───────────────────────┐
│                  PUBLIC MEDICAL DATA API                      │
│   OpenFDA / RxNorm / DailyMed  →  Returns JSON response      │
└──────────────────────────────────────┬───────────────────────┘
                                       │  JSON Data
┌──────────────────────────────────────▼───────────────────────┐
│                     RESPONSE PARSING (PHP/JS)                 │
│   Extract fields  →  Format data  →  Send to frontend        │
└──────────────────────────────────────┬───────────────────────┘
                                       │
┌──────────────────────────────────────▼───────────────────────┐
│                   RENDERED WEB UI                             │
│   Card layout  →  Drug info displayed  →  User reads it ✅   │
└──────────────────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

<div align="center">

**Frontend**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Backend**

![PHP](https://img.shields.io/badge/PHP_8.x-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=for-the-badge&logo=apache&logoColor=white)

**Server & Tools**

![XAMPP](https://img.shields.io/badge/XAMPP-Local_Server-FB7A24?style=for-the-badge&logo=xampp&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

**APIs**

![OpenFDA](https://img.shields.io/badge/OpenFDA-Public_API-0072C6?style=for-the-badge)
![RxNorm](https://img.shields.io/badge/RxNorm-Drug_Database-6DB33F?style=for-the-badge)

</div>

---

## 🔌 API Reference

This project integrates with **free, trusted public medical APIs**:

| API | Source | Data Provided |
|---|---|---|
| **OpenFDA** | U.S. Food & Drug Administration | Labels, adverse events, recalls |
| **RxNorm** | U.S. National Library of Medicine | Drug names, codes, relationships |
| **DailyMed** | NIH / NLM | Full drug label information |

**Sample API call (OpenFDA):**
```bash
GET https://api.fda.gov/drug/label.json?search=openfda.brand_name:"Aspirin"&limit=1
```

**Sample Response (JSON):**
```json
{
  "results": [{
    "openfda": {
      "brand_name": ["Aspirin"],
      "generic_name": ["ASPIRIN"],
      "manufacturer_name": ["Bayer"],
      "product_type": ["HUMAN OTC DRUG"]
    },
    "indications_and_usage": ["For temporary relief of minor aches..."],
    "warnings": ["Reye's Syndrome warning..."],
    "dosage_and_administration": ["Adults and children 12 years and over..."]
  }]
}
```

---

## 📂 Project Structure

```
medicine-lookup-system/
│
├── 📁 assets/
│   ├── 📁 css/
│   │   ├── style.css               # Main stylesheet
│   │   └── responsive.css          # Mobile responsive styles
│   ├── 📁 js/
│   │   ├── main.js                 # Search logic & UI interactions
│   │   └── render.js               # Drug card rendering functions
│   └── 📁 images/
│       ├── logo.png                # App logo
│       └── icons/                  # UI icons
│
├── 📁 api/
│   ├── fetch_drug.php              # Main API handler
│   ├── parser.php                  # JSON response parser
│   └── config.php                  # API keys & base URLs
│
├── 📁 includes/
│   ├── header.php                  # Shared HTML header
│   └── footer.php                  # Shared HTML footer
│
├── index.php                       # Main entry point / homepage
├── result.php                      # Drug result display page
├── about.php                       # About the project
├── .htaccess                       # Apache URL rewriting rules
├── requirements.txt                # System requirements notes
└── README.md                       # Project documentation
```

---

## ⚙️ Installation & Setup

### Prerequisites

- [XAMPP](https://www.apachefriends.org/) (or any Apache + PHP server)
- PHP **7.4+** / **8.x**
- Git
- A modern web browser

---

### 🖥️ Local Setup (XAMPP)

**Step 1 — Clone the repository**
```bash
git clone https://github.com/iiiii0vicky0-0singh0iiiii/medicine-lookup-system.git
```

**Step 2 — Move to XAMPP's web root**
```bash
# Windows
move medicine-lookup-system C:\xampp\htdocs\medicine-lookup-system

# macOS / Linux
mv medicine-lookup-system /opt/lampp/htdocs/medicine-lookup-system
```

**Step 3 — Start Apache server**
```
Open XAMPP Control Panel → Click START next to Apache
```

**Step 4 — Configure API (optional)**
```bash
# Edit api/config.php
# Add your OpenFDA API key if you have one (free tier works without key)

define('API_BASE_URL', 'https://api.fda.gov/drug/label.json');
define('API_KEY', 'YOUR_OPTIONAL_API_KEY');
```

**Step 5 — Launch the app**
```
Open your browser and visit:

http://localhost/medicine-lookup-system/
```

---

### ☁️ Deploy to Live Server

```bash
# Upload all project files to your server's public_html or www directory
# Ensure PHP and Apache mod_rewrite are enabled

scp -r medicine-lookup-system/ user@yourserver.com:/var/www/html/
```

> ✅ No database setup needed — this is a fully API-driven application!

---

## 📸 Screenshots

<div align="center">

| 🏠 Homepage | 🔎 Search Results | 💊 Drug Details Card |
|---|---|---|
| Clean search interface | Instant results listing | Full drug profile view |

> 📷 *Add your actual screenshots in the `/assets/images/screenshots/` folder and update paths here.*

</div>

---

## 🎯 Use Cases

| 👤 User Type | 💡 How They Use It |
|---|---|
| 🧑‍⚕️ **Patients** | Quickly check what a prescribed medicine does |
| 👩‍⚕️ **Caregivers** | Look up dosage and side effects for family members |
| 💊 **Pharmacists** | Fast reference for drug interactions and warnings |
| 🧑‍💻 **Developers** | Learn how to integrate public medical APIs |
| 🎓 **Students** | Study drug classifications and pharmacology |

---

## 🛣️ Roadmap

- [x] Basic medicine search by name
- [x] Real-time API data retrieval
- [x] Responsive web interface
- [x] Deployed on live server
- [ ] 🔲 Search by drug category / class
- [ ] 🔲 Drug interaction checker (compare 2 drugs)
- [ ] 🔲 Favorites / bookmarks (localStorage)
- [ ] 🔲 Search history feature
- [ ] 🔲 Dark mode toggle
- [ ] 🔲 Multi-language support
- [ ] 🔲 Print / PDF export of drug info
- [ ] 🔲 REST API for developers (JSON endpoint)
- [ ] 🔲 Mobile app version (React Native / Flutter)

---

## 🤝 Contributing

All contributions are welcome — here's how to get involved:

1. **Fork** the repository
2. **Create** a feature branch
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Make** your changes and commit
   ```bash
   git commit -m "Add: YourFeatureName description"
   ```
4. **Push** to your branch
   ```bash
   git push origin feature/YourFeatureName
   ```
5. **Open** a Pull Request with a clear description of what you changed

---

## ⚠️ Disclaimer

> **This application is for informational and educational purposes only.**
>
> - Data is sourced from public APIs (OpenFDA, RxNorm, DailyMed) and may not always be complete or current.
> - **Do NOT use this tool as a substitute for professional medical advice, diagnosis, or treatment.**
> - Always consult a licensed pharmacist or healthcare provider before taking any medication.
> - The developer is **not responsible** for any health decisions made based on information shown in this app.

---

## 📄 License

Distributed under the **MIT License** — see [`LICENSE`](LICENSE) for full details.

---

## 📬 Contact

<div align="center">

[![Email](https://img.shields.io/badge/Gmail-indianarmysniper@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:indianarmysniper@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-iiiii0vicky0--0singh0iiiii-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/iiiii0vicky0-0singh0iiiii)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourprofile)

<br/>

<img src="https://komarev.com/ghpvc/?username=iiiii0vicky0-0singh0iiiii&label=Profile+Views&color=0ea5e9&style=for-the-badge" alt="Profile Views"/>

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,3,30&height=120&section=footer&animation=fadeIn" width="100%"/>

*Built with ❤️ by **Vicky Kumar Singh** — empowering people with trusted medical information.*

⭐ **If this project helped you, please give it a star!** ⭐

</div>
