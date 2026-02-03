# Empty Folder Scanner & Deleter (Python)

This is a beginner-level Python project built using the **os module**.  
The script scans a given directory, finds **empty folders**, and deletes them **only after user confirmation**.

This project was created as **Day 17 practice** while learning the OS module in Python.

---

##  Features
- Checks if a folder path exists
-  Scans all items inside the folder
-  Detects **empty subfolders**
-  Asks user confirmation before deleting
-  Handles permission errors safely
-  Skips files automatically

---

##  Concepts Used
- `os.path.isdir()`
- `os.listdir()`
- `os.path.join()`
- `os.rmdir()`
- `try / except` error handling
- User input validation

---

##  How to Run
1. Make sure Python is installed
2. Run the script:
   ```bash
   python deletion.py
