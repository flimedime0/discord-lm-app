# Usage

## Running with Python

1. Install dependencies with `pip install -r requirements.txt`.
2. Configure your `.env` file.
3. Start the bot with `python bot.py`.

## Running with Docker

```bash
docker compose up --build -d
```

## Interacting with the Bot

- Use the `/chat` slash command to send prompts. Add `model:` (`gpt-4o` or `o3`) to switch models; the bot remembers your choice. Use `/chat` in servers **or** direct messages, and the bot mentions you at the end of replies.
- Replies tag you at the end of every chunk and display the model used.
- You can attach up to 10 images to `/chat` for multimodal prompts.
- Authorize the App using your OAuth2 URL to enable DM or group DM usage.
