install python if not installed https://www.python.org/downloads/

run the following command in cmd or powershell to install required packages:

pip install hjson

Open config.hjson in a text editor and update the settings to match your needs.

run index.py
Bot will run until the set claim time and perform a claim. Once claimed if compound is enabled it will check if you have enough HNR for a MUSHA node and if so create a new node.
once claim and node creation is done a new task will be scheduled and the bot will close. The bot will run again at the scheduled time/date.

First claim will occure at the tiem set on the day the bot is initially run.

changes to the config file will take effect wither the next tiem the scheduled task runs or if you run the index.py file manually (this will do a claim the day it is run)

*****curently task scheduling is only working on windows. I am working on the Linux/Mac scheduling still****
