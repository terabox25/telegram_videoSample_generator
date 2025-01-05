# Telegram Media Bot 🎧📹

A Telegram bot that allows you to easily trim and merge audio files, and generate video samples—all directly within Telegram!

## Features:
- **Audio Trimmer**: Trim your audio files by specifying start and end times.
- **Audio Merger**: Merge multiple audio files into a single track.
- **Video Sample Generator**: Trim a video and get a 15-second sample.

## Requirements:
- Python 3.8+
- Pyrogram
- FFmpeg
- Nest_asyncio
- Uvloop

## Step-by-Step Guide to Set Up Telegram Media Bot

### **Step 1: Clone the Repository**
First, clone the repository to your local machine:

1. Open a terminal (Command Prompt, PowerShell, or a terminal in your IDE).
2. Run the following command to clone the repo:
   ```bash
   git clone https://github.com/your-username/telegram-media-bot.git

   cd telegram-media-bot

  ### **Step 2: Install Dependencies
This bot requires several Python libraries. To install them, follow these steps:

Make sure you have Python 3.8+ installed. You can check by running:

python --version
Install the required dependencies using pip:

pip install -r requirements.txt
This will install the necessary packages like pyrogram, ffmpeg, nest_asyncio, and uvloop.

### **Step 3: Set Up Your Telegram API Credentials
To run the bot, you'll need to modify the credentials directly in the code:

### ** Get API credentials:

Go to Telegram's API Development Tools.
Log in with your Telegram account and create a new application to get your api_id and api_hash.
Get your bot token:

Open Telegram and search for the BotFather.
Create a new bot by following the instructions from BotFather.
Once created, you will receive a bot_token for your bot.
Modify the credentials in the code: Open the bot.py file in your project folder, and replace the placeholder values with your actual credentials:

api_id = your_api_id       # Replace with your API ID
api_hash = "your_api_hash" # Replace with your API hash
bot_token = "your_bot_token" # Replace with your bot token
Replace your_api_id, your_api_hash, and your_bot_token with the credentials you obtained.

### ** Step 4: Run the Bot
Now that everything is set up, it's time to run the bot:

In the project folder, run the following command to start the bot:


python bot.py
The bot should now be running. Open Telegram and start a chat with your bot by searching for it by its username.

Send /start to the bot, and it will show you the available options for trimming and merging audio or generating video samples.

Notes:
Make sure to keep your credentials secure and never share them publicly.
Ensure ffmpeg is installed on your system. If not, you can download and install it from FFmpeg's official site.
