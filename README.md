# PuddleOS
## Install Guide
1. Clone the repository locally.
2. Open a terminal as Admin/root.
3. Change to the root directory of PuddleOS.
4. Assuming Python 3 and `pip` is installed, run `pip install -r requirements.txt`. 
   This will install all the necessary libraries.
5. Now set the Flask environment variable. 
- Unix
`export FLASK_APP=app`
- Windows
`C:\path\to\app>set FLASK_APP=app.py`
- PowerShell
`PS C:\path\to\app> $env:FLASK_APP = "app.py"`
6. Run `python -m flask run`
7. The application should now be running under 127.0.0.1:5000

## User Guide
Coming soon.

## To-Do
*not listed in any order of importance*
1. Modify `GET` method to get the clustering method. Not necessary until another method is implemented.
2. Add node data to each layer accordian tab
3. ~~Add flag to display the Puddles or not~~
4. Add logic to create Puddles on screen
5. Add randomize graph button