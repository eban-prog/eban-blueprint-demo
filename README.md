# ÉBAN — Ethical Social Tech Blueprint Prototype

> 🧺 *Building change without evidence is like carrying water in a basket.*  
> ÉBAN transforms fragmented social care records into collective, ethical evidence — with dignity, privacy, and trust.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Privacy First](https://img.shields.io/badge/privacy-first-0EAD69)

🌱 **ÉBAN Blueprint Prototype**  
A privacy-first, federated case management system for ethical social care networks — built to demonstrate how ethics, technology, and governance can align for digital inclusion.

---

## 🌟 Features

### 🧩 Core Functionality
- 🗂️ **Local Records Management** — Securely register and track community support cases
- ✅ **Consent Management** — Granular consent controls for every data interaction
- 🕶️ **Privacy Mode** — Mask or anonymize sensitive information instantly
- 🌍 **Federated Network** — Optionally contribute anonymized insights to shared dashboards
- 🔐 **Pseudonym Generation** — Automatic identity protection by design
- 👩🏾‍⚕️ **Technician Profiles** — Track local team activity ethically

---

### ⚙️ Technical Highlights
✅ **Zero Dependencies** — Pure HTML, CSS & JavaScript  
✅ **Offline-First** — Works fully in-browser  
✅ **Responsive** — Mobile & desktop optimized  
✅ **Accessible** — WCAG 2.1 compliant with ARIA labels  
✅ **Privacy-Focused** — No tracking, no cookies, no storage  
✅ **Progressive Enhancement** — Degrades gracefully

---

## 🚀 Quick Start

### 💻 Live Demo
Simply open **index.html** in any modern web browser.

### 🧱 Local Development
```bash
# Clone the repository
git clone https://github.com/ebanodigital/eban-blueprint-demo.git

# Navigate to directory
cd eban-blueprint-demo

# Open in browser
open index.html
# or
python -m http.server 8000
# then visit http://localhost:8000
```

## 📋 Usage

### Register a New Case
1. Click **➕** or select "New Case"
2. Enter technician name (required)
3. Add beneficiary (optional, pseudonym auto-generated)
4. Choose support type
5. Review and check consent boxes
6. Submit

### Privacy Protection
- 🔒 **Privacy Mode**: toggle in "More" menu to mask data
- 👻 **Anonymous Cases**: exclude identifiable info
- 🪶 **Federated Consent**: optional sharing of anonymized patterns only

### Data Management
All data is stored in memory only — no persistence, no external calls.  
This demo illustrates ethical data handling practices defined by the **ÉBAN Blueprint**.

## 🏗️ Architecture

### Data Flow
```
User Input → Validation → In-Memory Storage → Render → Privacy Controls → Masked Display
```

### Key Components
- **appState** — centralized state management
- Real-time form validation
- Single-page navigation & conditional rendering
- Dynamic masking based on privacy settings

## 🔒 Privacy & Security

### Privacy-First Design
- No external API calls
- No cookies / localStorage
- No analytics or tracking
- Data cleared on reload
- Automatic pseudonymization

### Consent Hierarchy
1. 🏡 **Local Consent** (required) — basic case storage
2. 🌐 **Federated Consent** (optional) — anonymized insight sharing
3. 🕊️ **Anonymous Mode** (optional) — full privacy protection

🧭 This prototype is **GDPR-compliant** and follows the **ÉBAN Ethical Blueprint**: consent, autonomy, and co-creation.

## 🎨 Customization

### Colors
Modify CSS variables in the `:root` selector:
```css
:root {
  --blue: #003B73;
  --terra: #D9643A;
  --green: #0EAD69;
}
```

### Localization
- **Default language**: English 🇬🇧
- **To translate**: replace text in `index.html`, update `<html lang="pt">`

## 📱 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile (iOS 14+, Android 90+)

## 🤝 Contributing

Contributions welcome! 🛠️

1. Fork this repo
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit and push changes (`git commit -m 'Add amazing feature'`)
4. Open a Pull Request

### Guidelines
- Maintain zero dependencies
- Respect accessibility standards
- Test cross-browser
- Uphold privacy-by-design principles

## 📄 License

Licensed under **MIT License**.  
Use of this code must comply with data protection and ethical digital principles.  
See: [ÉBAN Blueprint Guidelines](https://github.com/ebanodigital/eban-blueprint-demo).

## 🙏🏾 Acknowledgments

- Built with 🤎 for ethical support organizations
- Co-created with frontline caregivers and digital inclusion advocates
- Inspired by federated learning, differential privacy, and human-centered design

## 🗺️ Roadmap

- 🌐 Multi-language support (PT, ES, FR)
- 🧾 PDF report export
- 🌙 Dark mode
- 🔗 Backend integration templates
- 📊 Analytics dashboard
- 🔐 Encrypted persistence module

---

✊🏾 **ÉBAN — Making care visible through ethical data.**
