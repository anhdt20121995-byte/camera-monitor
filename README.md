# 🎥 Camera Monitor - Surveillance System

A comprehensive surveillance system that turns a PC into a network video recorder (NVR) with multi-camera support, live streaming, recording, and mobile viewing capabilities.

## ✨ Features

- ✅ **Multi-Camera Support**: Add unlimited cameras with RTSP/ONVIF support
- ✅ **Multi-Screen Display**: 2x2, 4x4, 4x8 grid layouts (16-32 cameras)
- ✅ **Live Streaming**: Real-time video streaming to desktop and mobile
- ✅ **Local Recording**: Continuous or scheduled video recording
- ✅ **Network Storage**: PC hard drive as centralized storage
- ✅ **Mobile Access**: Remote viewing via iOS/Android app

## 🏗️ Architecture

```
IP Cameras (RTSP) ──→ Node.js Server ──→ Desktop App (Electron)
                             ↓
                        Local Storage (HDD)
                             ↓
                        Mobile App (React Native)
```

## 🚀 Quick Start

### Prerequisites
- Node.js 16+
- Git
- FFmpeg

### Installation

1. Clone repository:
```bash
git clone https://github.com/anhdt20121995/camera-monitor.git
cd camera-monitor
```

2. Setup Backend:
```bash
cd backend
npm install
npm start
```

3. Server runs on `http://localhost:5000`

## 📁 Project Structure

```
camera-monitor/
├── backend/          # Node.js Server
├── desktop/          # Electron Desktop App
├── mobile/           # React Native Mobile App
├── docs/             # Documentation
└── README.md
```

## 🔧 Technologies

- **Backend**: Node.js, Express, Socket.io
- **Desktop**: Electron, React
- **Mobile**: React Native
- **Video**: FFmpeg, RTSP
- **Database**: SQLite

## 📝 License

MIT License

## 👨‍💻 Author

anhdt20121995