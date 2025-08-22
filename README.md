# Circle FTP Dub and CamRip Labeler

A Tampermonkey/Greasemonkey userscript that enhances CircleFTP by **automatically labeling thumbnails** with clear badges for:

- 🎙️ **Dubbed content** → `DUB` label (blue for anime and orange for others) 
- 🎥 **Cam/Low-quality sources** → `CAM` label  

This makes browsing CircleFTP faster and easier by visually flagging important content types.

---

## ✨ Features
- Detects **dubbed content**
- Detects **cam/low-quality releases**
- Adds styled overlays (`DUB` and `CAM` labels) directly on **thumbnails**
- Uses **IntersectionObserver** for lazy loading efficiency
- Uses **MutationObserver** to handle dynamically loaded content
- Lightweight and fast — processes cards only once
---

## 🖼️ Script In Action

[![Script in action](https://raw.githubusercontent.com/LazyDevUserX/CircleFTP-Dub-Camrip-Labeler/d0919575dc035383ee732835e08a2de9d9f9e4cc/assets/Script-In-Action.jpeg)](https://raw.githubusercontent.com/LazyDevUserX/CircleFTP-Dub-Camrip-Labeler/d0919575dc035383ee732835e08a2de9d9f9e4cc/assets/Script-In-Action.jpeg)
---

## 📦 Installation
1. Install [Tampermonkey](https://www.tampermonkey.net/).
2. [Click here to install the script](userscript/circle-ftp-dub-camrip-labeler.user.js?raw=1).
3. Open [CircleFTP](http://new.circleftp.net/) — labels will appear on supported thumbnails automatically.

---

## ⚙️ Usage
- Navigate CircleFTP normally.
- Any **dubbed** or **cam rip** content will be flagged with a visible label:
  - 🔴 **CAM** → left corner of thumbnail
  - 🔵/🔴 **DUB** → right corner of thumbnail (blue for Eng+Jap Dual Audio, red otherwise)
