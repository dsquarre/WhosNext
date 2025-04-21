# 🎥 WhosNext

**whosnext.com** is an open-source alternative to Omegle, focused on **anonymous video chats** with a strong emphasis on **user safety** and **privacy**.

---

## 🌐 Vision

To build a real-time video-chat platform that enables safe and spontaneous conversations between strangers — while ensuring that inappropriate behavior is actively detected and blocked using AI/ML tools.

---

## 🛡️ Core Objectives

- 🔍 **Real-Time Monitoring**: Leverage AI/ML to detect nudity, violence, or any illegal activity in ongoing video streams.
- 🚫 **Auto-Banning System**: Instantly block users by IP if violations are detected.
- 🧹 **Privacy-First Storage**: Automatically delete screenshots and temporary media — keeping the database lightweight and user information secure.
- 🕵️ **Anonymous Yet Accountable**: Anonymous chats, but with backend-level checks to prevent misuse.

---

## ⚙️ Planned Tech Stack

### 🔧 Backend
- **FastAPI** – Lightweight, async web framework
- **OpenCV / Deep Learning Models** – For real-time content moderation
- **Redis / SQLite / PostgreSQL** – Session storage or temp data management (TBD)

### 💻 Frontend
- **React** – Component-based SPA
- **WebRTC** – Real-time peer-to-peer video streaming
- **Socket.io / WebSockets** – For signaling and chat communication

### 🧠 AI/ML
- **NSFW/Violence Detection Models** (e.g. NudeNet, DeepDetect, custom CNNs)
- **Frame Sampling + Image Analysis** – To balance accuracy and performance

---

## 🚀 Features (Planned)

| Feature | Status |
|--------|--------|
| Anonymous video chat | ⏳ In Progress |
| Real-time moderation using AI | 🧠 In Design |
| IP banning system | 🛠️ Planned |
| Screenshot capture and cleanup | 🛠️ Planned |
| Chat + Emoji support | ⏳ In Progress |
| Optional audio-only mode | 💡 Idea |
| Language filters | 💡 Idea |
| User report button | 🛠️ Planned |

---

## 🛠️ Setup (Coming Soon)

> ⚠️ Full setup instructions will be added once the MVP is ready.

For now, general dev dependencies you might want installed:
- `python3` + `pip`
- `nodejs` + `npm`
- `ffmpeg`
- `opencv-python`
- virtualenv

---

This project is in early development. If you’re interested in:
- AI/ML moderation
- WebRTC / FastAPI
- Frontend UI for chat apps

Feel free to fork the repo and raise an issue or PR!

## 🙌 Credits

- Daksh Jain – Name suggestion
- Danish Dubey – Project lead

