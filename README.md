<div align="center">

# 🌍 Smart Translator

### A modern, bilingual desktop translation app powered by PyQt5 & Google Translate

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![PyQt5](https://img.shields.io/badge/PyQt5-5.15%2B-41CD52?style=flat&logo=qt&logoColor=white)](https://pypi.org/project/PyQt5/)
[![deep-translator](https://img.shields.io/badge/deep--translator-1.11%2B-0EA480?style=flat)](https://pypi.org/project/deep-translator/)
[![License](https://img.shields.io/badge/License-Custom-blue?style=flat)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey?style=flat)]()

**Translate text across 100+ languages with a clean, modern, RTL-aware interface.**

🇮🇷 [مطالعه به فارسی](README.fa.md) · 🐛 [Report a Bug](https://github.com/samafzalidev/smart-translator-app/issues) · ✨ [Request a Feature](https://github.com/samafzalidev/smart-translator-app/issues)

</div>

---

## 📖 About The Project

**Smart Translator** is a professional desktop translation application built with **PyQt5** that leverages the powerful **deep-translator** library (Google Translate API) to deliver fast and accurate translations between **100+ languages**.

The app is designed with a sleek, modern UI that is fully **bilingual (Persian / English)** and supports **right-to-left (RTL)** layouts out of the box — making it equally comfortable for users of Persian, Arabic, Hebrew, and English alike.

> 💡 Whether you're a student, translator, developer, or just need quick translations without opening a browser — Smart Translator gives you a fast, distraction-free experience right on your desktop.

---

## ✨ Key Features

- 🌐 **100+ Languages** — Translate to and from virtually any major world language
- 🎨 **Modern UI** — Clean, flat design with a custom color palette (`#0ea480` brand accent)
- 🔁 **Bilingual Interface** — Every label is shown in both Persian and English
- ↔️ **Full RTL Support** — Native right-to-left layout for Persian/Arabic users
- 🎯 **Custom Dropdowns** — Hand-crafted `QComboBox` with custom arrow indicator
- ⚡ **Instant Translation** — Powered by Google Translate via `deep-translator`
- 📝 **Large Text Areas** — Comfortable editing of long-form text
- 🛡️ **Error Handling** — Graceful pop-ups for network or input issues
- 💻 **Cross-Platform** — Runs on Windows, macOS, and Linux
- 🆓 **100% Free & Open Source** — No ads, no tracking, no API key required

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| 🐍 **Python 3.8+** | Core programming language |
| 🎨 **PyQt5** | Cross-platform GUI framework |
| 🌐 **deep-translator** | Translation API wrapper (Google Translate) |

---

## 🚀 Getting Started

### 📋 Prerequisites

Make sure you have **Python 3.8 or higher** installed:

```bash
python --version
```

### 📥 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/samafzalidev/smart-translator-app.git
   cd smart-translator-app
   ```

2. **(Recommended) Create a virtual environment**
   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On macOS / Linux
   source venv/bin/activate
   ```

3. **Install the required dependencies**
   ```bash
   pip install PyQt5 deep-translator
   ```

   Or, if a `requirements.txt` is provided:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   python smart_translator.py
   ```

---

## 🎮 Usage

1. **Launch** the app — a window titled *"مترجم هوشمند | Smart Translator"* will open.
2. **Select the source language** from the left dropdown (default: Persian).
3. **Select the target language** from the right dropdown (default: English).
4. **Type or paste** the text you want to translate in the upper text area.
5. Click the **ترجمه | Translate** button.
6. The translated text will instantly appear in the lower output area. ✨

> 💡 **Tip:** An active internet connection is required since translations are powered by Google Translate.

---

## 📁 Project Structure

```
smart-translator-app/
├── 📄 smart_translator.py    # Main application source code
├── 📄 README.md              # English documentation (this file)
├── 📄 README.fa.md           # Persian documentation
├── 📄 LICENSE                # License file
```

---

## 🗺️ Roadmap

Planned features for upcoming versions:

- [ ] 🔄 Swap source ↔ target languages with one click
- [ ] 📋 Copy-to-clipboard button for translated text
- [ ] 🔊 Text-to-speech (TTS) for both input & output
- [ ] 🌙 Dark mode toggle
- [ ] 💾 Save translation history (SQLite)
- [ ] ⌨️ Keyboard shortcut (`Ctrl+Enter`) to translate
- [ ] 🌐 Support for multiple backends (DeepL, MyMemory, etc.)
- [ ] 📦 Standalone Windows `.exe` build via PyInstaller
- [ ] 🍎 macOS `.dmg` and Linux `.AppImage` releases

Have an idea? [Open an issue](https://github.com/samafzalidev/smart-translator-app/issues) to suggest a feature!

---

## 🤝 Contributing

Contributions, issues, and feature requests are warmly welcome! 🎉

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

> ⭐ If you like this project, please consider giving it a **star** — it really helps!

---

## 📜 License

This project is distributed under a **custom permissive license**:

> Permission is granted to use, copy, and distribute this software for **personal, educational, and non-commercial purposes**, provided the original author (**Sam Afzali**) is credited.
>
> Modification, resale, commercial use, or claiming authorship of the code is **strictly prohibited**.
>
> The software is provided **"AS IS"**, without warranty of any kind.

See the [LICENSE](LICENSE) file for full details.

---

## 👨‍💻 Author

<div align="center">

### **Sam Afzali**

🐙 **GitHub:** [@samafzalidev](https://github.com/samafzalidev)

_Designed & developed with ❤️ in Iran_

</div>

---

## 🙏 Acknowledgments

- [**deep-translator**](https://github.com/nidhaloff/deep-translator) — the powerful translation library that drives this app
- [**Qt / PyQt5**](https://www.riverbankcomputing.com/software/pyqt/) — the cross-platform GUI framework
- [**Google Translate**](https://translate.google.com/) — the underlying translation engine
- All open-source contributors and the Python community 🐍❤️

---

<div align="center">

**If this project was helpful, don't forget to leave a ⭐ on GitHub!**

Made with ❤️ by [Sam Afzali](https://github.com/samafzalidev)

</div>
