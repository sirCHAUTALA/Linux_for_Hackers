# 🐧 Linux Commands Learned – Process & Service Management

This section documents the new commands I have learned for process handling and service management.

---

## 🔹 Process Management
| Command                  | Description                                              | Example Usage                 |
|---------------------------|----------------------------------------------------------|-------------------------------|
| `ps -aux | grep subline` | Search running processes for a keyword (e.g., `subline`) | `ps -aux \| grep subline`     |
| `ps -aux | grep nano`    | Check if `nano` (text editor) process is running          | `ps -aux \| grep nano`        |
| `ps -aux | grep ntp`     | Check if NTP (time sync service) is running               | `ps -aux \| grep ntp`         |

---

## 🔹 Interactive Process
| Command  | Description                               | Example Usage   |
|----------|-------------------------------------------|-----------------|
| `nano`   | Open a simple interactive text editor     | `nano file.txt` |

---

## 🔹 Service Management with `systemctl`
| Command                       | Description                                   | Example Usage                |
|-------------------------------|-----------------------------------------------|------------------------------|
| `sudo systemctl restart ssh`  | Restart the SSH service                       | `sudo systemctl restart ssh` |
| `sudo systemctl reload ssh`   | Reload configuration without stopping service | `sudo systemctl reload ssh`  |
| `sudo systemctl list-units`   | List all active systemd units (services, etc.)| `sudo systemctl list-units`  |

---

## ✅ Notes
- Use `ps -aux` with `grep` to filter specific processes.  
- `nano` is great for quick text editing inside the terminal.  
- `systemctl` is the modern replacement for `service` and controls background services (daemons).  

---

## 🚀 Next Steps
- Learn how to **enable/disable services**:  
  - `sudo systemctl enable service`  
  - `sudo systemctl disable service`  
- Practice **checking service status**:  
  - `sudo systemctl status ssh`  
- Explore **logs** with:  
  - `journalctl -u service`  
