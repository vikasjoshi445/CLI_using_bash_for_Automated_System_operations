# Mysh – Lightweight Custom Bash Shell with GUI Notepad

**mysh** is a small custom shell built entirely using Bash. It recreates essential Unix commands like `ls`, `cd`, and `pwd`, and provides features such as command history, tab autocompletion, and a graphical notepad using **Zenity**, with optional encryption using **GPG**.  
It’s designed to be both educational and useful for automating simple system operations.

---

## 🚀 Features

- Custom versions of common shell utilities:  
  `myls`, `mycd`, `mypwd`, `mymkdir`, `myrmdir`, `myhistory`, `notepad`, `exit`
- Saves full command history in a log file
- Tab-based autocompletion for supported commands
- **GUI Notepad**
  - Create, open, edit and delete notes
  - List notes from a visual interface
  - Encrypt & decrypt notes securely using GPG

---

## 📁 Project Structure
mysh.sh # Main shell entry script
run_mysh.sh # Optional launcher to open in a new terminal
notepad_gui_files/ # Automatically created storage for notes
mysh_history.log # Stores command history


---

## 🛠 Setup Instructions

### Install Dependencies
```bash
sudo apt update
sudo apt install xterm zenity gnupg

git clone https://github.com/your-username/mysh.git
cd mysh
chmod +x mysh.sh run_mysh.sh
./run_mysh.sh
```

---

## 💻 Usage

Once started, a shell prompt appears:

mysh>

Supported Commands

myls [-a] [-l] [dir]

mycd [dir]

mypwd

mymkdir [dir]

myrmdir [dir]

myhistory

notepad

exit

---

## 🔐 Encrypted Note Support

Encrypt notes with password-based GPG protection

Decrypt, edit, and securely save via GUI

Automatically handles temporary decrypted files

---

## 📄 License

Released under the MIT License — free to modify and distribute.

---

## 🙏 Acknowledgements

Zenity

GNU Bash, GPG, and Linux core utilities


---


