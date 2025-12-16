# DB2TUI
A minimal TUI SQL IDE for DB2 Databases running in AS/400

![MainScreen](https://github.com/user-attachments/assets/f9e53d81-392b-4e97-9fe9-a2b8543f6997)

This project started just part for exploring the AS/400 ecosystem part of a larger application that I am developing
Don't expect to have at least for this initial 0.1 Version but if I have time I am planning to implement as many features as possible
For order for this run of course you need Python, all the tests have being contacted using the Python 3.9.2 on pub400 which is the only available IBM system that allows free use.
Besides Python it needs *textual* package , install it via wheel package https://files.pythonhosted.org/packages/5f/2b/7cdfdfd79bae4e2555d3ba79976417d675fbc52951190fdfc3ed0d0148ea/textual-6.10.0-py3-none-any.whl
It requires of course some more but you will find for the errors the matching wheels depending on the packages you already have (TIP use pip3)
The functionality is like this
you run it like this :
python3 db2tui.py
From there your first action is to type the LIBRARY you want to work this .
After you type and press ENTER you are getting the tables on the Left pane
<img width="295" height="671" alt="image" src="https://github.com/user-attachments/assets/f03c6f43-c6cc-4c63-94ec-32474da647cd" />
On the putty connection you can even use mouse for selecting and executing the data view on the table
<img width="1653" height="174" alt="image" src="https://github.com/user-attachments/assets/c7171c7c-c5ab-4744-b74e-43913fbf5f1f" />
The datatable features paging so you can view even big tables 
<img width="810" height="405" alt="image" src="https://github.com/user-attachments/assets/a31e7d62-05f0-4af5-ba9d-b9b74b7771be" />
On the top Pane you can write SQL commands and execute them via ctrl+e
Besides writing sql you can execute even .sql files, just hit ctrl+o to get the file path of the SQL 
if no mistakes 
<img width="534" height="197" alt="image" src="https://github.com/user-attachments/assets/10ed88aa-9cdc-4168-9f4d-302e1c2cfe10" />
hit ctrl+e to execute it  :)
ctrl+p shows the available commands (as shown on bottom status bar) and ctrl+a shows a minimal about screen
As said I have plans to make it more robust and more useful to handle even complex cases while still using a minimal TUI environment, 
something you will set it once and you probably never have to remember complex commands and everything.
Here is a glance of the future :)
<img width="951" height="497" alt="image" src="https://github.com/user-attachments/assets/b03f41bc-af47-4c6c-a797-bc7cb0f7417a" />

Since I only have access to pub400 I would like some feedback.








