# 📘 Linux Commands Cheat Sheet (Row Format)

This README documents Linux commands I learned for **process management, file management, and web utilities**.

---

## 📋 Commands

| Command                          | Description                                         | Example Usage                           | Extra Knowledge |
|----------------------------------|-----------------------------------------------------|-----------------------------------------|----------------|
| `pgrep <process>`                | Finds the PID(s) of a process by its name           | `pgrep firefox`                         | Combine with `pkill` to kill directly: `pkill firefox`. |
| `mkdir <directory>`              | Creates a new directory                             | `mkdir website`                         | Use `mkdir -p parent/child` to create nested directories. |
| `cd <directory>`                 | Change to a specific directory                      | `cd website`                            | `cd ..` goes back one directory. |
| `nano <file>`                    | Opens a file in the Nano text editor                | `nano index.html`                       | Use `CTRL + O` to save, `CTRL + X` to exit. |
| `curl <host>:<port>`             | Sends HTTP request to a host/port                   | `curl localhost:1234`                   | Add `-I` for headers only, or `-o file.html` to save output. |
| `wget <host>:<port>`             | Downloads content from a host/port                  | `wget localhost:1234`                   | Use `-O filename` to rename the downloaded file. |
| `touch <file>`                   | Creates an empty file                               | `touch test.txt`                        | Can also update file timestamps if file exists. |
| `cat << EOF > <file>`            | Creates a file with inline text until `EOF`         | `cat << EOF > notes.txt` <br> `Hello` <br> `EOF` | Great for writing multi-line content quickly. |
| `echo "text"`                    | Prints text to terminal or file                     | `echo "Hello World"`                    | Use `echo "Hello" > file.txt` to save output to a file. |

---

✨ With these commands, I can **create directories, manage files, write/edit content, and test local web services effectively**.
