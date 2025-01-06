# CODTECH-Advanced-task-1

**Name :** Sangani Dhruvin
**college :** Silver oak university
**Task :** File integrity checker
**Intern ID :** CT08DAV


**Explanation of the python script which is used:
Dependencies:**

**hashlib: **Used for calculating file hashes (e.g., SHA256, MD5).
os: Used for navigating the file system and interacting with files and directories.
time: Used for introducing pauses between directory checks.
Functions:

**calculate_file_hash():** This function reads a file in binary mode and calculates its hash (default is SHA256).
**get_files_hashes():** This function scans the directory and computes the hash for each file present.
**monitor_directory():** This function continuously monitors the directory. It compares the current hash values with previously stored values to detect any new, modified, or deleted files. If a change is detected, it prints a message.

**Main Logic:**
The directory to monitor is defined as MONITOR_DIR. You should replace 'path/to/your/directory' with the actual path to the directory you want to monitor.
The script monitors the directory at regular intervals (default is 10 seconds) and checks for file changes.

**How to Use:**
Modify the MONITOR_DIR variable to the directory you wish to monitor.
You can adjust the sleep_time in the monitor_directory() function if you want the script to check for changes more or less frequently.
Run the script, and it will print messages to the console if it detects any changes in the files (new, modified, or deleted files).
