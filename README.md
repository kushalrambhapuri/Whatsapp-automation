# WhatsApp Automation Bot
Tired of typing out WhatsApp messages? Now you can automate your messages with just 2 lines of Python code!
I created this bot using PyCharm, a popular Python code editor. Follow the steps below to set up your WhatsApp automation:

Prerequisites
Python Installed: Ensure Python is installed on your system.
Install pywhatkit: Open the terminal and run the following command:
pip install pywhatkit  
Code Explanation
Importing the Library: At the top of the script, import the pywhatkit module:

import pywhatkit  
Send a Message: Use the following line of code to send a WhatsApp message automatically:

pywhatkit.sendwhatmsg('+1 1234567890', 'YOUR MESSAGE HERE', 15, 30)  
Replace +1 1234567890 with the recipient's phone number (include the country code for the US).
Replace 'YOUR MESSAGE HERE' with the message you want to send.
The 15 and 30 represent the time (in 24-hour format) when the message should be sent (e.g., 3:30 PM).
How It Works
Once you run the script, the message will automatically be sent at the specified time.
A browser window will open, navigate to WhatsApp Web, and send the message on your behalf.
Notes
Ensure you’re logged into WhatsApp Web in your default browser before running the script.
Use automation responsibly and avoid spamming others.
And that’s it! Your WhatsApp automation bot is ready to send messages for you.
