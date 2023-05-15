
# WhatsApp Automation Project

This project utilizes Python and the Selenium library to automate sending messages through WhatsApp Web.

## Prerequisites

- Python 3.x installed on your machine
- Selenium library installed (`pip install selenium`)
- ChromeDriver executable file ([Download here](https://sites.google.com/a/chromium.org/chromedriver/)) compatible with your Chrome browser version
- Google Chrome browser installed

## Setup
Open the python file and update the following variables:
# Path to the ChromeDriver executable
CHROME_DRIVER_PATH = '/path/to/chromedriver'

# Name or phone number of the recipient
RECIPIENT = 'Friend\'s Name'

# Message to be sent
MESSAGE = 'Hello from Python!'
Usage
Start the Chrome browser and navigate to web.whatsapp.com.

Run the Python script
python whatsapp_automation.py

Wait for the browser to open WhatsApp Web and scan the QR code if necessary.

The script will find the chat with the specified recipient and send the message.

Once the message is sent, the browser will close automatically.
