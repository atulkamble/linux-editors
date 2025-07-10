# 📖 Mastering Text Handling in Linux

---

## 📌 1️⃣ Introduction to **Text Handling in Linux**

Linux systems manage configuration, logs, and scripts in plain text files. Being efficient with text editors is crucial for system administrators, DevOps engineers, and developers.

Common text editors:

* **vi/vim**
* **nano**
* **cat, less, more, head, tail, grep, sed, awk** for viewing and processing

---

## 📌 2️⃣ Introduction to **Vi Editor**

The **vi** editor is a powerful, lightweight, and widely available text editor in Linux.

### 📌 Basic Modes:

* **Command Mode:** Default mode (for navigation, deletion, copying, saving)
* **Insert Mode:** For writing text
* **Last Line Mode (Ex Mode):** For saving, quitting, searching

### 📌 Open a file with `vi`:

```bash
vi filename.txt
```

### 📌 Enter Insert Mode:

Press `i` to start typing.

### 📌 Save and Quit:

* Press `Esc` → type `:wq` → press `Enter`

### 📌 Quit Without Saving:

* Press `Esc` → type `:q!` → press `Enter`

### 📌 Other Common Commands:

| Action                  | Command         |
| :---------------------- | :-------------- |
| Move up/down/left/right | `k` `j` `h` `l` |
| Delete line             | `dd`            |
| Copy line               | `yy`            |
| Paste                   | `p`             |
| Search                  | `/text`         |
| Replace word            | `:s/old/new/g`  |

---

## 📌 3️⃣ Introduction to **"vi" Editor (Same as Vi Editor)**

In most Linux distributions, `vi` points to `vim` or a lightweight variant.
You can check this with:

```bash
vi --version
```

To install **vim** (if missing):

```bash
sudo apt install vim        # Debian/Ubuntu
sudo yum install vim        # RHEL/CentOS
```

---

## 📌 4️⃣ Introduction to **Nano Editor**

**nano** is a beginner-friendly, terminal-based text editor in Linux.

### 📌 Open a file:

```bash
nano filename.txt
```

### 📌 Start Typing:

It’s in edit mode by default.

### 📌 Save and Exit:

* **Ctrl + O** → Enter (to save)
* **Ctrl + X** (to exit)

### 📌 Exit Without Saving:

* **Ctrl + X**
* When prompted, press `N` (for No)

### 📌 Common Nano Commands:

| Action           | Command    |
| :--------------- | :--------- |
| Save file        | `Ctrl + O` |
| Exit             | `Ctrl + X` |
| Cut current line | `Ctrl + K` |
| Paste            | `Ctrl + U` |
| Search           | `Ctrl + W` |
| Replace          | `Ctrl + \` |

---

## 📌 5️⃣ Introduction to **"nano" Editor (Same as Nano Editor)**

Like **vi**, `nano` is a command-line text editor pre-installed on many systems.

To install **nano** (if missing):

```bash
sudo apt install nano        # Debian/Ubuntu
sudo yum install nano        # RHEL/CentOS
```

---

## ✅ Summary Table

| Editor | Command to Open     | Save & Exit                | Exit Without Saving | Search     |
| :----- | :------------------ | :------------------------- | :------------------ | :--------- |
| vi     | `vi filename.txt`   | `:wq`                      | `:q!`               | `/text`    |
| nano   | `nano filename.txt` | `Ctrl + O` then `Ctrl + X` | `Ctrl + X` then `N` | `Ctrl + W` |

---

## 📦 Bonus: Check Installed Editors

```bash
which vi
which nano
```

---
