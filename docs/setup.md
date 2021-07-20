## How to setup the bot?

1. Go to [Discord Developers page](https://discord.com/developers){target="_blank"} and click `New Application` to create an application.
2. Go to `Bot` section of the app and click `Add Bot`.
3. Go to `OAuth2` section and check `bot` in `SCOPES` section.
4. In `BOT PERMISSIONS` session, check `Send Messages`.
5. Click the blue `Copy` button in `SCOPES` section and invite the bot to a guild of your choice.
6. The bot should be in your guild, now we need to provide a token to run it.
7. Run the bot to generate system settings file.
8. Go to your appication on [Discord Developers page](https://discord.com/developers){target="_blank"}.
9. Go to the Bot section of it and click the blue `Copy` button in `TOKEN` section.
10. Paste the token to `token` field in the `settings.json` file.
11. Open terminal in the bot's folder and type `node index.js`.
12. That's it, the bot is running now.