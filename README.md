# Telegram_Bot-
The Telegram Gist Execution Bot allows users to install, execute, and manage code snippets from GitHub Gists directly through a Telegram chat interface. It provides functionality to download and execute Python scripts from Gists, handle user input for script execution, and manage installed Gist files.

**Features**

Install Gist Files: Download and store files from GitHub Gists.

Execute Python Code: Run Python scripts from installed Gists.

Provide Input to Scripts: Send input dynamically for interactive scripts.

Stop Execution: Stop code execution if needed.

Remove Installed Files: Delete downloaded Gist files when no longer required.

**Commands**

/install <gist_url> – Downloads and stores the Gist files.

/run <file_name> – Executes the specified Python script.

<text input> – Sends input to a running script.

/stop – Stops the script execution.

/remove <file_name> – Deletes the specified file.

**Prerequisites**

Python 3.x installed on the system.

A Telegram bot token from BotFather.

python-telegram-bot and requests modules installed.

**Installation**

Clone or download the script.

Install dependencies using:

pip install python-telegram-bot requests

Replace 'your bot token' in the script with your actual Telegram bot token.

Run the bot using:

python bot.py

**Usage**

Start the bot and send the /install command followed by a valid GitHub Gist URL.

Run a script using /run <file_name>.

If the script requires input, send text messages to provide input.

Stop execution using /stop.

Remove a downloaded file using /remove <file_name>.

**Example**

/install https://gist.github.com/example/12345
/run script.py
Hello World  # This is user input

**Notes**

The bot only supports Python scripts.

Ensure that the Telegram bot has permission to receive and respond to messages.

Scripts are executed in the local environment, so handle security considerations carefully.

Scripts are executed in the local environment, so handle security considerations carefully.
