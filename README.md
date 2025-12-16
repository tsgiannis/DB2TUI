Here’s a polished and professional version of your GitHub README for DB2TUI, with improved clarity, structure, and readability while keeping your original tone and intent:

DB2TUI
A minimal TUI SQL IDE for DB2 Databases on AS/400
![MainScreen](https://github.com/user-attachments/assets/f9e53d81-392b-4e97-9fe9-a2b8543f6997)

About
DB2TUI is a lightweight, terminal-based SQL IDE designed for DB2 databases running on AS/400 systems. This project began as part of a larger application I’m developing to explore the AS/400 ecosystem.
Current Version: 0.1 (Initial Release)
This is a minimal version with core functionality. Future updates will expand features based on time and feedback.

Requirements

Python 3.9.2 (Tested on pub400, the only free IBM system available for public use).
Textual package (Install via wheel):
bash
Copy

pip3 install https://files.pythonhosted.org/packages/5f/2b/7cdfdfd79bae4e2555d3ba79976417d675fbc52951190fdfc3ed0d0148ea/textual-6.10.0-py3-none-any.whl


Additional dependencies may be required. Install missing packages as errors arise (use pip3).

Features
1. Library and Table Navigation

Start by typing the LIBRARY you want to work with.
Tables appear in the left pane after pressing ENTER.
<img width="295" height="671" alt="image" src="https://github.com/user-attachments/assets/f03c6f43-c6cc-4c63-94ec-32474da647cd" />
Table Navigation
2. Data View and Interaction

Use mouse selection (even in Putty) to interact with tables.
Supports paging for large datasets.
Data View
Paging
<img width="1653" height="174" alt="image" src="https://github.com/user-attachments/assets/c7171c7c-c5ab-4744-b74e-43913fbf5f1f" />
3. SQL Execution

Write SQL commands in the top pane.
Execute with Ctrl+E.
Load .sql files with Ctrl+O. (execute with Ctrl_E)
<img width="534" height="197" alt="image" src="https://github.com/user-attachments/assets/10ed88aa-9cdc-4168-9f4d-302e1c2cfe10" />
SQL Execution
4. Keyboard Shortcuts
    
      Shortcut
      Action
    
  
  
    
      Ctrl+E
      Execute SQL
    
    
      Ctrl+O
      Open SQL file
    
    
      Ctrl+P
      Show available commands
    
    
      Ctrl+A
      Show about screen
    
  



Roadmap
I plan to enhance DB2TUI with:

More robust error handling.
Advanced SQL features.
Improved usability for complex workflows.
Goal: A tool you set up once and never need to memorize complex commands again.
Future Preview
<img width="951" height="497" alt="image" src="https://github.com/user-attachments/assets/b03f41bc-af47-4c6c-a797-bc7cb0f7417a" />
Feedback
Since I only have access to pub400, I’d love your feedback! Let me know:

What works well.
What’s missing.
Any bugs or unexpected behavior.

Let’s make DB2TUI better together! 🚀
