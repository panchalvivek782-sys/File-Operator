## # Personal Journal Manager
## 
## ## Description
## This Python application is a command-line Personal Journal Manager.
## It allows users to write, store, and manage daily journal entries.
## Entries are permanently saved to a local text file with automated timestamps.
## 
## ## Key Features Implementation
## * **File I/O Handling**: Uses robust error-handling blocks to safely read from and append data to files.
## * **Automated Timestamps**: Leverages the `datetime` module to stamp every entry with the exact creation time.
## * **Keyword Search**: Parses file contents to filter and display logs matching specific user queries.
## * **Resource Cleanup**: Offers a secure choice to wipe the storage file completely from disk memory.
## 
## ## How to Run
## 1. Verify that Python is installed on your computer.
## 2. Copy the code into a file named `journal_manager.py`.
## 3. Open your terminal or command line prompt.
## 4. Execute the script using the command: `python journal_manager.py`
## 
## ## Interactive Menu Options
## * **Option 1**: Add a New Entry (accepts custom text and appends a timestamp).
## * **Option 2**: View All Entries (reads and prints the full history from the log file).
## * **Option 3**: Search for an Entry (scans all logs for custom phrases or specific dates).
## * **Option 4**: Delete All Entries (removes the underlying text file after a user confirmation).
## * **Option 5**: Exit (closes the interactive management application cleanly).
