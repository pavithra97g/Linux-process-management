# Process Management in Linux

## 1. Objective
The purpose of this task is to learn process management in Linux, including listing processes, killing processes, understanding process states, managing services using systemctl, enabling services at boot, and monitoring resource usage.

---

## 2. Commands Executed

### 2.1 List Running Processes
- `ps aux`
- `top`

### 2.2 Kill Processes
- `kill <PID>`

### 2.3 Start and Stop Services
- `sudo systemctl start ssh`
- `sudo systemctl stop ssh`

### 2.4 Enable Service at Boot
- `sudo systemctl enable ssh`
- `sudo systemctl disable ssh`

### 2.5 Monitor Resource Usage
- `vmstat 2`
- `free -h`

---

## 3. Process States
| State | Meaning |
|-------|---------|
| R     | Running |
| S     | Sleeping |
| Z     | Zombie |
| T     | Stopped |
| D     | Uninterruptible Sleep |

---

## 4. Screenshots
| Step | Screenshot |
|------|------------|
| ps output | `screenshots/ps.png` |
| top output | `screenshots/top.png` |
| kill command | `screenshots/process-kill.png` |
|process state | `screenshots/process-state.png`|
| start ssh service | `screenshots/system-ctl-start.png` |
| stop ssh service | `screenshots/system-ctl-stop.png` |
| status ssh service | `screenshots/system-ctl-status.png` |
| enable ssh service | `screenshots/system-ctl-enable.png` |
| disable ssh service | `screenshots/system-ctl-disable.png` |
| vmstat output | `screenshots/monitoring.png` |
| free -h output | `screenshots/monitoring.png` |

---

## 5. Findings
- Using `ps aux` and `top`, I was able to list and monitor running processes and view their PID, CPU usage, and memory usage.
- Process states observed include Running (R) and Sleeping (S).
- `kill <PID>` sends a graceful termination signal.
- Using `systemctl`, I started and stopped the `ssh` service successfully.
- Enabling the service at boot ensures that it automatically starts after system reboot.
- Resource monitoring using `vmstat` and `free -h` showed normal CPU and memory usage without spikes.

---

## 6. Conclusion
This task helped in understanding Linux process management and service control using CLI commands. I can now confidently list processes, kill processes, manage services, and monitor system resources.
