# Master AI BOT: Fastest Telegram AI BOT. Voice Support. GPT-4 Turbo. Unique Chat Modes

<p align="center">
  <img src="https://pub-f858c7e521464395920779af297fb1bd.r2.dev/Master-AI-BOT-GIT.gif" align="center" style="width: 100%; border-radius: 20px" />
</p>

Unleash the power of ChatGPT with our Telegram Bot! Say goodbye to the laggy experience of chat.openai.com, daily usage limits, and outdated web interfaces.

You can deploy your own bot or use our streamlined version: [Click Here](https://t.me/Master_AI_YESBHAUTIK_BOT)

## Key Features

- Lightning-fast responses (typically within 3-5 seconds)
- No request limits – chat as much as you want
- Seamless message streaming (see the demo)
- Powered by GPT-4 Turbo
- Group chat support (/help_group_chat for instructions)
- DALLE 2 integration (select 👩‍🎨 Artist mode for image generation)
- Voice message recognition
- Code highlighting for developers
- 15 special chat modes: 👩🏼‍🎓 Assistant, 👩🏼‍💻 Code Assistant, 👩‍🎨 Artist, 🧠 Psychologist, 🚀 Elon Musk, and more. Customize your chat modes by editing `config/chat_modes.yml`
- Utilize the [ChatGPT API](https://platform.openai.com/docs/guides/chat/introduction)
- Control access with a list of authorized Telegram users
- Keep track of your OpenAI API spending

<p align="center">
  <img src="https://github.com/yesbhautik/Master-AI-BOT/blob/main/static/help_group.gif?raw=true" style="width: 40%; border-radius: 20px"/>
</p>

---

## Bot Commands

- `/retry` – Regenerate the last response from the bot
- `/new` – Start a new conversation
- `/mode` – Choose a chat mode
- `/balance` – Check your OpenAI API balance
- `/settings` – View and adjust bot settings
- `/help` – Get assistance with using the bot

## Getting Started

1. Obtain your [OpenAI API key](https://openai.com/api/).

2. Get your Telegram bot token from [@BotFather](https://t.me/BotFather).

3. Pre-requirements Installation [For Debian Based Environment only, for other system please install manually: Docker, Docker-compose, Python, pip]

   ```bash
   sudo apt -y update
   sudo apt -y install ca-certificates curl gnupg lsb-release docker-compose docker docker.io docker-compose python3 python3-pip apt-utils
   ```

4. Clone the repository:

   ```bash
   git clone https://github.com/yesbhautik/Master-AI-BOT
   ```
   
5. Go to the project directory:

   ```bash
   cd Master-AI-BOT
   ```
   
6. Install dependencies:
   
   ```bash
   pip3 install -r requirements.txt
   ```
   
7. Install dependencies:

   ```bash
   cp config/config-example.env config/config.env
   cp config/config-example.yml config/config.yml
   ```
8. Edit the configuration file `config/config.yml` to set your tokens. You can also edit `config/config.env` if you're an advanced user.

9. 🔥 Now, it's time to **run**:

    ```bash
    docker-compose --env-file config/config.env up --build -d
    ```

## References

1. Learn more about how we built ChatGPT from GPT-3: [Build ChatGPT from GPT-3](https://learnprompting.org/docs/applied_prompting/build_chatgpt)

## Contributing 🤝
Contributions are welcome! Please follow these steps to contribute to the project:

1. Fork the repository🍴
2. Create a new branch for your feature or bug fix 🌿
3. Make your changes and commit them 💻
4. Push your changes to your fork 🚀
5. Create a pull request to the main repository 📥

## 🔥 Show Your Support | Make a Donation

If you find this repository helpful, please show your support by giving it a ⭐! Your support means a lot to us and encourages us to contribute more to the open-source community.

Additionally, if you'd like to offer financial support, you can do so via our donation link: [Make a Donation](https://rzp.io/l/Contribute-to-YesbhautikX-USD)

<br>
<a href="https://rzp.io/l/Contribute-to-YesbhautikX-USD">
  <img src="https://www.pngall.com/wp-content/uploads/2016/05/PayPal-Donate-Button-Free-Download-PNG.png" alt="Donate" width="100">
</a>

## 💬 Let's Connect

Feel free to reach out to us if you have questions, ideas, or simply want to chat. We're here to help and connect with the community.

- Website: [https://yesbhautik.co.in/](https://yesbhautik.co.in/)
- Another One: [https://yesbhautikx.co.in/](https://yesbhautikx.co.in/)
- LinkedIn profile: [https://www.linkedin.com/in/yesbhautik](https://www.linkedin.com/in/yesbhautik)
- Instagram page: [https://www.instagram.com/yesbhautik](https://www.instagram.com/yesbhautik)

## 📜 License

This repository is licensed under the MIT License. For more information, see the [LICENSE](LICENSE) file.

Transforming your `readme.md` into an attractive, user-friendly guide is crucial for engaging your audience and making a lasting impression. If you have any further requests or need assistance with anything else, feel free to ask.
