# AI Talks

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://ai-talks.streamlit.app)

A ChatGPT API wrapper, providing a user-friendly Streamlit web interface.

Enhance your ChatGPT experience with our user-friendly API wrapper, featuring a seamless Streamlit web interface. Effortlessly interact with ChatGPT, while enjoying an intuitive and responsive design. Discover simplified access to advanced AI technology in just a few clicks.

![](ai_talks/assets/demo/ai-talks.gif)

## Setup

1. Clone repo:

```bash
git clone https://github.com/dKosarevsky/AI-Talks.git
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Add API key to `.streamlit/secrets.toml`:

```toml
[api_credentials]
api_key = "sk-..."
```

## Usage

To run the app use the following command:

```bash
bash run.sh
```

Another way:

```bash
streamlit run ai_talks/chat.py
```

Once the script is started, you can go to the URL [http://localhost:8501](http://localhost:8501) to start using the bot.

## License

This project is released under the B.A.L. License



</details>
