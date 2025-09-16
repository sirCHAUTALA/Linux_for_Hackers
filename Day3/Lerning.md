# 🐧 Linux Commands Learned

This README contains the Linux commands I have learned so far.

---

## 🔹 File & Directory Management
| Command     | Description                                    | Example Usage                    |
|-------------|------------------------------------------------|----------------------------------|
| `find`      | Search for files and directories               | `find /home -name "*.txt"`       |
| `chmod`     | Change file permissions                        | `chmod 755 script.sh`            |
| `chown`     | Change file ownership                          | `sudo chown user:user file.txt`  |
| `rename`    | Rename files using a pattern                   | `rename 's/.txt/.bak/' *.txt`    |

---

## 🔹 User Management
| Command     | Description                                    | Example Usage             |
|-------------|------------------------------------------------|---------------------------|
| `adduser`   | Add a new user with home directory             | `sudo adduser testuser`   |
| `su`        | Switch user                                    | `su testuser`             |

---

## 🔹 Package Management
| Command     | Description                                    | Example Usage                        |
|-------------|------------------------------------------------|--------------------------------------|
| `dpkg`      | Install/remove Debian packages manually        | `sudo dpkg -i package.deb`           |
| `apt`       | Install, update, upgrade packages (Debian/Ubuntu) | `sudo apt install curl`           |
| `apt upgrade` | Upgrade installed packages                   | `sudo apt upgrade`                   |
| `aptitude`  | Alternative package manager with text UI       | `sudo aptitude install vim`          |
| `snap`      | Install and manage snap packages               | `sudo snap install spotify`          |

---

## 🔹 Version Control
| Command     | Description                                    | Example Usage                     |
|-------------|------------------------------------------------|-----------------------------------|
| `git`       | Version control system for code management     | `git clone https://github.com/...`|

---

## ✅ Next Steps
- Learn process management commands: `ps`, `kill`, `jobs`, `fg`, `bg`.  
- Explore networking commands: `ping`, `ifconfig`, `netstat`, `ss`.  
- Start automation with **bash scripting**.  
