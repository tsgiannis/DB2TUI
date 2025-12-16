Here’s a polished and professional version of your GitHub README for DB2TUI, with improved clarity, structure, and readability while keeping your original tone and intent:

DB2TUI
A minimal TUI SQL IDE for DB2 Databases on AS/400
MainScreen

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
Table Navigation
2. Data View and Interaction

Use mouse selection (even in Putty) to interact with tables.
Supports paging for large datasets.
Data View
Paging
3. SQL Execution

Write SQL commands in the top pane.
Execute with Ctrl+E.
Open and run .sql files with Ctrl+O.
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

Feedback
Since I only have access to pub400, I’d love your feedback! Let me know:

What works well.
What’s missing.
Any bugs or unexpected behavior.

Let’s make DB2TUI better together! 🚀
