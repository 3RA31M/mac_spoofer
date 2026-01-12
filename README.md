# 🕶️ MAC Spoofer Script (Linux)

A simple interactive **Bash script** to detect network interfaces and spoof MAC addresses using `macchanger`.

Built for:
- Linux users
- Kali / Parrot / Ubuntu
- Pentesting labs
- Privacy testing
- Learning Bash scripting the right way

---

## 🚀 Features

- 🔍 Automatically detects available network interfaces
- 🧠 Excludes loopback (`lo`)
- 📋 Menu-based interface selection
- 🎭 Multiple MAC spoofing modes:
  - Random MAC
  - Random MAC (same vendor)
  - Custom MAC
- ⛔ Root check (no silent failures)
- ✅ Brings interface down & up safely
- 📡 Shows MAC before and after change

---

## 🛠️ Requirements

Make sure these are installed:

- **Linux OS**
- **Bash shell**
- **macchanger**
- **iproute2**

## Notice 

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this tool.

See the `LICENSE` file for full details.


This program auto installs macchanger if not installed but its better to install 
Install macchanger if missing:
```bash
sudo apt update
sudo apt install macchanger


