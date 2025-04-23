# 💻 Nexus

**Nexus** is a cross-platform LAN communication and control system built in **C++ with Qt**. It enables real-time interaction between devices on the same local network without internet.

---

## 🚀 Features

- 🗨️ **Real-time LAN Chat** – Peer-to-peer messaging using UDP
- 📋 **Clipboard Sync** – Share copied text across devices with global hotkeys
- 📁 **File Transfer** – Send files directly to any system on the network with delivery status
- 🗂️ **Shared Dropbox** – Host files/folders for public access without transferring them
- 👥 **Auto User Discovery** – Detect and show all active users on the network
- 🔒 **Private and Local** – No internet needed, full control over your data

---

## 🖥️ UI Overview

- **Left Panel:** Floating menu + user list with avatars
- **Right Panel:** Dynamic view (chat, clipboard, dropbox, etc.)
- **Chat View:** Header (avatar + name), message area, input with send/file buttons

---

## 🛠️ Technology Stack

| Component        | Tech Used         |
|------------------|------------------|
| Frontend         | Qt Widgets (C++) |
| Messaging        | UDP Sockets      |
| File Sharing     | TCP Sockets      |
| Clipboard Sync   | Qt Clipboard + Hotkeys |
| Database         | SQLite (Temporary) |
| Build Tool       | qmake            |
| Platform         | Windows, Linux   |

---

## 🧠 Architecture

- **LanDiscovery** – Handles broadcasting and listening for active users
- **ChatManager** – Sends/receives UDP messages
- **ClipboardManager** – Sends clipboard contents and receives shared data
- **FileTransferManager** – TCP-based file transfer system with real-time status
- **DatabaseManager** – SQLite-based history storage (chat, clipboard, file logs)

---

## 📦 Download

| Platform | Installer |
|----------|-----------|
| Windows  | [Download Nexus.exe](downloads/nexus-windows.exe) |
| Linux    | [Download .tar.gz](downloads/nexus-linux.tar.gz) |

---

## 💡 Use Cases

- 💼 Office file and message exchange
- 🧪 Classroom/lab interactions without internet
- 🧠 Clipboard and workflow sync between personal devices
- 🏡 Home automation control hub (future feature)

---

## 📸 GUI Snapshots

| Chat Interface | Clipboard Sync |
|----------------|----------------|
| ![Chat GUI](https://github.com/user-attachments/assets/1137f99e-c5b7-426a-a490-73babf5d92bb) | ![Clipboard](https://github.com/user-attachments/assets/93dcd1e1-6ac6-4b79-af03-a9251fa00f15) |


---

## 🤝 Contributing

We welcome contributions! Fork the repo, create a branch, submit PRs. You can also suggest new features or report issues.

---

## 👨‍💻 Publisher & Developers

![BoldReach Logo](https://raw.githubusercontent.com/keshavsharma011/Project-Boldreach/refs/heads/main/Images/Boldreach-logo/boldreach_logo.webp)

**Published by:** **Boldreach Consultancy**  
**Developed by:** **Keshav** and **Gaurakh**

📧 Contact: [Boldreach](mailto:boldreach.in@gmail.com)

🌐 Website: [Boldreach
Consultancy](https://www.boldreach.in//)
