# Process Management in Linux

## ✅ Task Overview
The task focuses on Linux process management, including:
- Listing running processes using `ps` and `top`
- Killing processes using `kill`
- Understanding process states
- Starting/stopping services using `systemctl`
- Enabling services at boot
- Monitoring system resource usage
- Recording findings

## 📁 Repository Contents
- `report.md` – Detailed report with commands, findings, and screenshots.
- `screenshots/` – Folder containing all screenshots of command outputs.

## 🛠 Commands Used
- `ps aux`
- `top`
- `kill <PID>`
- `sudo systemctl status ssh`
- `sudo systemctl start ssh`
- `sudo systemctl stop ssh`
- `sudo systemctl enable ssh`
- `sudo systemctl disable ssh`
- `vmstat 2`
- `free -h`

## 📌 Notes
- SSH service was used as the example service for start/stop and enable at boot.
- Resource usage monitoring was done using `vmstat` and `free -h`.
