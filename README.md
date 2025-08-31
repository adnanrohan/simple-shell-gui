# Simple Shell GUI with Recycle Bin

A Bash-based interactive shell script that provides a simple **menu-driven GUI** for managing files and folders. It includes features like creating files/folders, renaming, searching, safe delete with a **Recycle Bin system**, restoring deleted items, and performing basic operations (sum & sorting).

---

## 🚀 Features

* **File & Folder Management**

  * Create new files and folders
  * Rename files and folders
  * Search for files or folders in a given directory

* **Recycle Bin System**

  * Safe delete (moves files/folders to `~/.recycle_bin` instead of permanent deletion)
  * View Recycle Bin contents
  * Restore deleted items to a chosen directory
  * Empty Recycle Bin safely

* **Utility Operations**

  * Calculate the sum of two integers
  * Sort an array of numbers

* **User-Friendly Menu**

  * Clear text-based menu for all options
  * Error handling for invalid inputs

---

## 📂 Project Structure

```
├── simple_shell_gui.sh   # Main Bash script
├── README.md             # Documentation
```

---

## 📖 Menu Options

1. Create File and Folder
2. Rename File or Folder
3. Search for Files or Folders
4. Safe Delete (Move to Recycle Bin)
5. View Recycle Bin
6. Restore from Recycle Bin
7. Empty Recycle Bin
8. Sum or Sort
9. Exit

---

## 🛡 Error Handling

* Prevents overwriting when renaming files/folders.
* Ensures only valid integers are accepted for sum calculations.
* Handles empty input when sorting arrays.
* Recycle Bin system avoids accidental permanent deletion.

---

## 🧑‍💻 Example Run

```text
------------------------------
      My Simple Shell GUI     
------------------------------
1. Create File and Folder
2. Rename File or Folder
3. Search for Files or Folders
4. Safe Delete (Move to Recycle Bin)
5. View Recycle Bin
6. Restore from Recycle Bin
7. Empty Recycle Bin
8. Sum or Sort
9. Exit
------------------------------
Enter your choice:
```

---


