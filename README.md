# gpt2bot

<img src="https://github.com/polakowo/gpt2bot/blob/master/logo.png?raw=true" width=128>

# GPTbot

GPTbot is an interactive chatbot available on Telegram, powered by state-of-the-art neural network technologies developed by Microsoft. This bot utilizes the DialoGPT model, which is trained on a vast corpus of dialogue data from Reddit, ensuring that it can generate human-like responses in multi-turn conversations. Additionally, GPTbot is equipped with DialogRPT to enhance dialogue generation through ranking responses based on extensive human feedback.

## Features

- **Multi-Turn Dialogue**: Engage in natural, extended conversations with responses that consider the context of the whole interaction.
- **Human-like Responses**: Thanks to the training on 147M multi-turn dialogue data from Reddit, the bot’s responses are often indistinguishable from those a human might provide.
- **Extensible**: GPTbot is built to support multiple text generators from the Hugging Face's transformers library, making it versatile and adaptable to new models.
- **Quality Interaction**: Enhanced with DialogRPT, the bot ranks potential responses based on quality, ensuring the interaction remains engaging and coherent.

## Installation

To run GPTbot, you need to set it up on a server with Telegram bot integration. Follow these steps:

1. Clone this repository:
git clone https://github.com/yourusername/GPTbot.git
cd GPTbot

2. Install required packages:


3. Set up your Telegram bot token:
- Create a bot with [BotFather](https://core.telegram.org/bots#6-botfather) on Telegram and get your token.
- Add your token to the configuration file or use it directly in your code.

4. Run the bot:
python bot.py

## Usage

Once the bot is running, you can interact with it directly through Telegram. Just start a conversation on the Telegram app, and GPTbot will respond.

## Contributing

Contributions are welcome! Please feel free to submit pull requests, create issues for bugs and feature requests, and provide feedback to improve the bot.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Microsoft for the DialoGPT and DialogRPT models.
- Hugging Face for their transformers library.
- The Reddit community for the data used to train the model.
