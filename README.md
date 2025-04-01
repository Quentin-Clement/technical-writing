<p align="center">
  <img src="./openoffice-logo.png" alt="OpenOffice Logo" height="200"/>
</p>

# OpenOffice.org 2.4 README

Welcome to OpenOffice.org 2.4! This document offers crucial setup, usage, and support information. Whether you're a new or seasoned user, we encourage you to read through to ensure smooth operation and discover how to get involved in the community.

---

## 🌍 About OpenOffice.org
OpenOffice.org is a **free and open-source office suite**. It is available for everyone — businesses, schools, governments, and private users — under an open license.

🔗 [License details](http://www.openoffice.org/license.html)

Want to get involved? Learn more here:
🔗 [Introduction to the project](http://www.openoffice.org/about_us/introduction.html)

---

## 💻 System Requirements
Ensure your system meets the minimum specifications:
- Windows 98, ME, NT (SP6+), 2000, or XP
- Pentium-compatible PC
- 64 MB RAM
- 250 MB disk space (300 MB for CJK version)
- 800x600 screen resolution, 256 colors minimum
- ~500 MB disk space post-installation (after deleting temp files)

---

## ⚙️ Installation Notes
- Admin rights are **required** to install.
- Close all other applications.
- Ensure sufficient memory in the temporary directory.
- Windows 98 users: If prompted to reboot after Java installation, ignore or restart the setup manually afterward.

---

## 🚀 Startup Issues & Troubleshooting
If the program hangs or display errors occur:
- **Update your graphics drivers**.
- Try disabling **OpenGL**: Go to `Tools → Options → OpenOffice.org → View → 3D View`.
- Clipboard compatibility between OOo 1.x and 2.4 may vary. Use `Edit → Paste Special` as needed.

You can install OOo 2.4 **alongside** older versions. If you later remove an older version, run a **repair install** of 2.4.

---

## 🖱️ ALPS/Synaptics Touchpad Issue
Scroll gestures may not work due to driver conflicts. To fix:

Add the following to your `SynTPEnh.ini`:
```ini
[OpenOffice.org]
FC = "SALFRAME"
SF = 0x10000000
SF |= 0x00004000
```
📌 Restart required. File location may vary.

---

## 🔍 Accessibility: ZoomText
To use ZoomText with OOo 2.4, version **7.11 or later** is required. Only versions released **after June 12, 2002** support the needed features.

---

## ⌨️ Keyboard Shortcuts
OpenOffice.org shortcuts **must not conflict** with OS-level shortcuts. If a key combo fails:
- Check your OS shortcut settings.
- Customize OpenOffice.org shortcuts via `Tools → Customize`.

---

## ✉️ Sending Documents via Email
If crashes occur when sending files through `File → Send → Email`, the issue is likely related to Windows MAPI.
🔍 Visit Microsoft’s Knowledge Base and search for **"mapi dll"** for potential fixes.

---

## 📝 Registration & Feedback
Registration is optional but highly encouraged. It helps shape development based on real user needs.
🔗 [Register here](http://www.openoffice.org/welcome/registration-site.html)

Help improve the suite by responding to the online user survey. Your feedback supports ongoing development!

---

## 💡 Support & Resources
- 📚 [Mailing lists](http://www.openoffice.org/mail_list.html)
- 📌 [FAQ](http://user-faq.openoffice.org/)

Got a bug? Report it via **IssueZilla**, our bug tracker. This helps make OpenOffice.org better for everyone!

---

## 🤝 Get Involved
You don’t have to be a programmer to contribute! Here’s how:

### 📧 Subscribe to Mailing Lists
- 📰 `announce@openoffice.org` – News & updates (recommended)
- 💬 `discuss@openoffice.org` – User discussions
- 🎯 `dev@marketing.openoffice.org` – Help us spread the word
- 🛠️ `dev@openoffice.org` – Contribute to code

### 🔧 Join a Project
Projects range from:
- 📚 Documentation
- 🌍 Localization
- 🧪 Testing
- 📣 Marketing

Explore more: [Join a project](http://projects.openoffice.org/index.html)

---

## 🔐 Legal & Source Code Notes
Parts of OpenOffice.org include contributions from:
- James Clark (1998–1999)
- Netscape Communications Corporation (1996, 1998)

---

We wish you a smooth experience with OpenOffice.org 2.4!

🧡 — The OpenOffice.org Community

