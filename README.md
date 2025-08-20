## 🛰️ Card Sharing WebServer

It is a test, and a good start, anyone can advance it and fix bugs, it is only for personal use and education.

**A modern [localhost](http://localhost) webserver for CCcam, NewCamd, MGcamd, and OSCam protocols with beautiful web interface.**

### ✨ Features

- 🔗 **Multi-Protocol Support** - CCcam, NewCamd, MGcamd, OSCam
- 🌐 **Modern Web Dashboard** - Real-time monitoring and management
- 📡 **C-Line Processing** - Easy upstream server management
- 🔄 **Local Sharing Bridge** - Connects receivers to upstream providers
- 📊 **Real-time Statistics** - Client monitoring and server status
- 🛡️ **Security Features** - User authentication and access control

### 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/your-username/card-sharing-webserver.git
cd card-sharing-webserver

# Install dependencies
pip install -r requirements.txt

# Start server
python backend/[server.py](http://server.py)
```

**Access dashboard:** [`http://localhost:8080`](http://localhost:8080)

### 📡 Receiver Configuration

```
Protocol: CCcam
Server: 127.0.0.1 (or your network IP)
Port: 50000
Username: admin
Password: alen
```

### 🔧 Configuration

- **Web Interface:** Port 8080
- **CCcam:** Port 50000
- **NewCamd:** Port 50001
- **MGcamd:** Port 50002
- **OSCam:** Port 50003

### 📋 Requirements

- Python 3.7+
- Flask
- Flask-SocketIO
- Modern web browser

### 🎯 How It Works

1. Add your provider's C-line in the dashboard
2. Server connects to upstream provider
3. Creates local CCcam server for your receivers
4. Bridges requests between local clients and upstream servers
5. Monitor everything through the web interface

### 📱 Supported Devices

- Satellite receivers (Dreambox, Vu+, Enigma2)
- GT Media series
- Zgemma boxes
- Any CCcam-compatible device

### ⚠️ Legal Notice

This software is for **educational purposes only**. Users are responsible for compliance with local laws and service provider terms. Only use with authorized content and valid subscriptions.

### 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### 💝 Support

If you find this project helpful, please give it a ⭐ star!

**Author:** Alen Pepa

**Copyright © 2025 Alen Pepa. All rights reserved.**

---

*Built with ❤️ for the satellite TV community*
