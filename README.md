

# README.md Template – Terminal Dashboard

````markdown
# Terminal Dashboard

Welcome to **Terminal Dashboard** – a colorful and interactive system monitoring tool for Linux terminals. This project provides a sleek way to view your system information directly from the command line, enhanced with ASCII art and terminal colors for a modern and aesthetic look.

---

## 🌟 Features

- **User & Host Info**: Quickly see your username, hostname, and shell.
- **OS & Kernel**: Check which operating system and kernel version you are running.
- **System Uptime**: See how long your system has been running.
- **Resource Usage**:
  - CPU load
  - Memory usage
  - Disk usage
- **Network Info**:
  - Local IP address
  - Default gateway
- **Interactive ASCII Art**: A small piece of ASCII art to make the terminal output fun and unique.
- **Lightweight & Fast**: Runs in the terminal without heavy dependencies.
- **Portable**: Can be placed in `/usr/local/bin` for global access from anywhere.

---

## 💻 Installation

1. Clone or download the repository:

```bash
git clone https://github.com/YOUR_USERNAME/terminal-dashboard.git
cd terminal-dashboard
````

2. Make the script executable:

```bash
chmod +x dashboard
```

3. Optional: Move it to `/usr/local/bin` for system-wide access:

```bash
sudo mv dashboard /usr/local/bin/dashboard
```

---

## 🚀 Usage

Run the dashboard script:

```bash
./dashboard
```

Or, if moved to `/usr/local/bin`:

```bash
dashboard
```

You should see a colorful dashboard displaying system information and an ASCII art header.

---

## 📸 Screenshots

Example output in terminal:

```⠀

========================================
      🚀 Terminal Dashboard 🚀
========================================
User:        bagashtml
Hostname:    bagashtml-IdeaPad-3-14IAU7
OS:          Ubuntu 24.04.3 LTS
Kernel:      6.14.0-29-generic
Uptime:      up 10 minutes
Shell:       /bin/bash

---- Resources ----
CPU Load:    1.05, 0.77, 0.40
Memory:      3.0Gi/7.5Gi
Disk:        20G/48G (44%)

---- Network ----
IP:          192.168.18.47
Default GW:  192.168.18.1
========================================
```

---

## ⚙️ Customization

* **Colors**: Edit the color variables at the top of the script (`RED`, `GREEN`, `CYAN`, `YELLOW`, `MAGENTA`) to match your terminal theme.
* **ASCII Art**: Replace the default ASCII art block with your own designs.
* **Additional Info**: Add more system information by extending the script with commands like `lsblk`, `df -h`, `uptime`, etc.

---

## 🛠 Dependencies

This script uses standard Linux commands:

* `bash`
* `awk`
* `free`
* `df`
* `hostname`
* `uptime`
* `ip`

No extra packages are required, making it lightweight and portable.

---

## 💡 Contributing

Contributions are welcome! Here are a few ways you can help:

* Add new features or system stats.
* Improve ASCII art or add multiple random headers.
* Optimize the script for performance.
* Fix bugs or typos.

To contribute:

```bash
git fork https://github.com/YOUR_USERNAME/terminal-dashboard.git
git checkout -b feature/my-feature
# make changes
git commit -am "Add new feature"
git push origin feature/my-feature
```

Then open a Pull Request on GitHub.

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use and modify it freely.

---

## 🙌 Credits

* Original idea inspired by Minegrub / system dashboard scripts.
* ASCII art and color enhancements by Bagas Tresna.

Enjoy your colorful terminal experience! 🚀

```

---

Kalau mau, aku bisa bikinin **versi ekstra README** yang **langsung ada instruksi install + screenshot + badge GitHub** biar repository kelihatan super profesional & eye-catching.  

Mau aku buatkan versi itu juga?
```
