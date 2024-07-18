# Ai-Biden-Bot
AI Biden Bot is an interactive chatbot that simulates President Biden's responses using natural language processing. It converts these responses into speech and video, providing an engaging user experience on Telegram.

Project Description
AI Biden Bot leverages a pre-trained model from the Transformers library to generate text responses based on user input. The responses are then converted to speech using Google Text-to-Speech (gTTS) and combined with a video template to create a complete video response. The bot is deployed on Telegram, allowing users to interact with it in real-time.

How It Works
Text Generation: The bot uses a pre-trained GPT-2 model to generate responses to user queries.
Text-to-Speech: The generated text is converted to speech using gTTS.
Video Creation: The audio file is merged with a video template to produce the final video response.
Telegram Integration: The bot handles user messages and sends back video responses using the Telegram API.
Getting Started
Prerequisites
Python 3.6+
Transformers
gTTS
moviepy
ffmpeg
pyTelegramBotAPI
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/ai-biden-bot.git
cd ai-biden-bot
Install the required Python packages:

bash
Copy code
pip install -r requirements.txt
Set up your Telegram bot and get the API token. Update the TOKEN variable in bot.py with your token.
