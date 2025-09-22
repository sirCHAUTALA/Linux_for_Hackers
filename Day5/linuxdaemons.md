# 📘 Linux Commands Cheat Sheet (Row Format)

This README documents the Linux commands I learned for **process management**, **networking**, and **system utilities**.

---

## 📋 Commands

| Command                     | Description                                   | Example Usage                 |
|-----------------------------|-----------------------------------------------|-------------------------------|
| `pgrep <process>`           | Finds the PID(s) of a process by its name     | `pgrep firefox`               |
| `kill <PID>`                | Terminates a process using its PID            | `kill 42051`                  |
| `ps -u <username> \| grep`  | Lists processes for a user and filters output | `ps -u kali \| grep firefox`  |
| `ps -aux \| grep <process>` | Shows all processes and filters by keyword    | `ps -aux \| grep firefox`     |
| `ping -c <count> <host>`    | Sends a set number of ICMP packets            | `ping -c 10 asfngo.org`       |
| `sleep <seconds>`           | Pauses the system/command for given time      | `sleep 30`                    |

---

✨ With these commands, I can **find and kill processes, check running tasks, test connectivity, and control execution timing**.
