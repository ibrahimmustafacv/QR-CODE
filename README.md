# 🔳 QRForge — Free Professional QR Code Generator

<div align="center">

**A powerful, fully client-side QR code generator with advanced styling and customization**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

</div>

---

## 📖 Overview

**QRForge** is a free, no-watermark QR code generator that runs entirely in the browser. It supports 14+ content types (URLs, WiFi, contacts, crypto payments, social profiles, and more), full visual customization (colors, gradients, dot styles, logos), and high-resolution PNG/SVG export — all with a live, real-time preview.

---

## ✨ Features

- 🚫 **No watermark, no sign-up** — fully free to use
- 🖼️ **High-resolution export** in both **PNG** and **SVG** formats
- 🎨 **7 dot styles** and multiple corner/finder-pattern styles for a unique look
- 🌈 **Solid colors or gradients** for foreground and background, including a transparent background option
- 🏷️ **Custom logo embedding** — upload your own logo or pick from built-in icons, with adjustable size and background
- ⚙️ **Fine-grained settings** — image size, margin, padding, and error-correction level (EC)
- 📊 **Live QR stats panel** showing module count, QR version, EC level, and character count
- 📋 **One-click copy to clipboard** for quick sharing
- 🔊 **Sound toggle** for interaction feedback
- 📱 **Fully responsive**, drag-and-drop logo upload support
- ⚡ **Instant live preview** — the QR code regenerates automatically as you type or adjust settings

---

## 🧩 Supported Content Types

| Type | Description |
|---|---|
| 🌐 Website | Any URL / link |
| 📝 Text | Plain text content |
| 📞 Phone | Direct dial number |
| 📧 Email | Email with optional subject & message |
| 💬 SMS | Pre-filled text message |
| 📶 WiFi | Auto-connect with SSID, password & security type |
| 👤 Contact (vCard) | Full contact card (name, phone, email, org, etc.) |
| 💚 WhatsApp | Chat link with pre-filled message |
| ✈️ Telegram | Username or phone-based link |
| 📸 Instagram | Direct profile link |
| ✖️ Twitter/X | Direct profile link |
| ▶️ YouTube | Channel or video link |
| 📍 Location | GPS coordinates with optional place name |
| ₿ Bitcoin | Payment address with optional amount & label |

---

## 🛠️ Tech Stack

- **HTML5** for structure
- **CSS3** (Custom Properties, Flexbox, responsive layout) for a clean modern UI
- **JavaScript (Vanilla)** for QR generation, canvas rendering, styling logic, and file export
- **HTML5 Canvas API** for rendering the QR code and custom dot/logo styling
- **Font Awesome** for icons

---

## 📂 Project Structure

```
📁 QRForge
│
└── index.html    # Single file containing all HTML, CSS, and JS
```

---

## 🚀 Getting Started

1. Download or clone the project
2. Open `index.html` directly in any modern web browser

```bash
open index.html      # macOS
start index.html     # Windows
```

No server, build step, or dependencies required — everything runs client-side in the browser.

---

## 🎯 How to Use

1. **Choose a content type** (Website, WiFi, Contact, WhatsApp, etc.)
2. **Fill in the fields** for the selected type
3. Switch to the **Style tab** to customize dot style, corner style, colors, or gradients
4. Switch to the **Logo tab** to add a custom logo or built-in icon at the center of the QR code
5. Adjust **Settings** (size, margin, padding, error-correction level) as needed
6. Click **Generate** to render the QR code, then **download as PNG/SVG** or **copy it directly**

---

## 📌 Notes

- All processing happens **entirely in the browser** — no data is ever sent to a server, making it fully private
- The higher the error-correction level, the more damage/obstruction (e.g. a logo) the QR code can tolerate while remaining scannable

---

<div align="center">

**Built for creators, businesses, and anyone who needs a clean, custom QR code — fast**

© 2024 QRForge — All rights reserved

</div>
