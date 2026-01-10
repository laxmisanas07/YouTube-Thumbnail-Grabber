# ⚡ YouTube Thumbnail Grabber

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![GUI](https://img.shields.io/badge/GUI-Tkinter-yellow?style=for-the-badge)
![Theme](https://img.shields.io/badge/Theme-Jetstorm-cyan?style=for-the-badge)

> **A sleek, retro-futuristic tool to extract High-Quality (MaxRes) thumbnails from any YouTube video.** > *Part of the A-Z Python Projects Series.*

---

## 🌟 Features

* **🌌 Jetstorm UI:** Custom-drawn canvas background with a glowing grid and starfield animation effect.
* **⚡ Instant Fetch:** Grabs the highest resolution (`MaxResDefault`) image available directly from YouTube servers.
* **👁️ Live Preview:** View the thumbnail within the app before saving.
* **💾 Easy Save:** One-click save to your local disk.
* **🛡️ Smart Error Handling:** Automatically handles invalid URLs or videos without HD thumbnails.

---

## 🛠️ Tech Stack

* **Language:** Python 3
* **GUI Framework:** Tkinter (Standard Lib)
* **Image Processing:** Pillow (PIL)
* **Networking:** Requests

---

## 🚀 Installation & Usage

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/LaxmiSanas/YouTube-Thumbnail-Grabber.git](https://github.com/LaxmiSanas/YouTube-Thumbnail-Grabber.git)
    cd YouTube-Thumbnail-Grabber
    ```

2.  **Install Dependencies:**
    You need `requests` and `pillow` for image handling.
    ```bash
    pip install requests pillow
    ```

3.  **Run the Application:**
    ```bash
    python main.py
    ```

4.  **How to Use:**
    * Paste a YouTube Video URL (e.g., `https://youtube.com/watch?v=...`).
    * Click the **GRAB ⚡** button.
    * Once the preview loads, click **SAVE TO DISK**.

---

## 📂 Project Structure

```text
📂 YouTube-Thumbnail-Grabber
├── 📄 main.py                 # The source code (GUI & Logic)
├── 📄 yt_grabber_fixed.png    # Project Banner/Thumbnail
├── 📄 README.md               # Documentation
└── 📄 requirements.txt        # Dependencies

👨‍💻 Author
Built with Python & ❤️ by Laxmi Sanas
