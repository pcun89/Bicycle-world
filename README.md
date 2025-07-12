# Bicycle-world
# 🚴 Bicycle World – Python File System Simulation

**Bicycle World** is a Python-based simulation of a fictional bicycle shop’s file system, inspired by Codecademy’s *Bicycle World* command-line project. This script gives you hands-on practice with file and directory manipulation using Python’s built-in modules (`os`, `shutil`), emulating basic shell commands like `mkdir`, `touch`, `mv`, and `rm`.

---

## 📌 Features

- 📁 Simulate a directory structure using `os.makedirs()`
- 📝 Create, read, and edit files using Python I/O
- 🔁 Move, rename, and delete files with `shutil` and `os`
- 📄 View contents of directories and files
- 🧪 Text-based simulation output (no user input required)

---

## 🧠 Concepts Practiced

- File system operations in Python
- Programmatic directory management
- Basic file I/O (read/write/append)
- Modular code organization
- Real-world scripting use cases

---

## 🗂️ Simulated Directory Structure

bicycle_world/
├── inventory/
│ ├── bike_list.txt
│ └── accessories/
│ └── gloves.txt
├── sales/
│ └── invoices/
├── staff/
│ ├── mechanics.txt
│ └── sales_team.txt

yaml
Copy
Edit

---

## 🚀 Getting Started

### ▶ Run the Simulation

Make sure you have **Python 3.7+** installed.

```bash
python bicycle_world.py
This will:

Create the file structure.

Populate sample data into files.

Perform file operations (move, append, delete).

Print the results in the terminal.

🧪 Sample Output
bash
Copy
Edit
✅ Bicycle World setup complete.

Contents of bicycle_world/inventory:
 - helmets.txt
 - bikes.txt
 - accessories

Contents of bicycle_world/inventory/accessories/gloves.txt:
Winter Gloves
Summer Gloves

Contents of bicycle_world/inventory:
 - bike_list.txt
 - accessories
