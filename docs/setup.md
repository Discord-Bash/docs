## How to setup the bot?

1. Go to [Discord Developers page](https://discord.com/developers){target="_blank"} and click `New Application` to create an application.

    <figure>
        <img src="/docs/showcases/setup/1.png" alt="Creating an application">
        <figcaption>Creating an application</figcaption>
    </figure>

2. Go to `Bot` section of the app and click `Add Bot`.

    <figure>
        <img src="/docs/showcases/setup/2.png" alt="Image">
        <figcaption>Creating a bot</figcaption>
    </figure>

3. Go to `OAuth2` section and check `bot` in `SCOPES` section.

    <figure>
        <img src="/docs/showcases/setup/3.png" alt="Image">
        <figcaption>Checking `bot` in `SCOPES` section</figcaption>
    </figure>

4. In `BOT PERMISSIONS` session, check `Send Messages`.

    <figure>
        <img src="/docs/showcases/setup/4.png" alt="Image">
        <figcaption>Checking `Send Messages` in `BOT PERMISSIONS`</figcaption>
    </figure>

5. Click the blue `Copy` button in `SCOPES` section and invite the bot to a guild of your choice.

    <figure>
        <img src="/docs/showcases/setup/5.png" alt="Image">
        <figcaption>Inviting the bot</figcaption>
    </figure>

6. The bot should be in your guild, now we need to provide a token to run it.

    <figure>
        <img src="/docs/showcases/setup/6.png" alt="Image">
        <figcaption>The bot is offline</figcaption>
    </figure>

7. Run the bot to generate system settings file.

    <figure>
        <img src="/docs/showcases/setup/7.png" alt="Image">
        <figcaption>Generating settings file</figcaption>
    </figure>

8. Go to your appication on [Discord Developers page](https://discord.com/developers){target="_blank"}.
9.  Go to the Bot section of it and click the blue `Copy` button in `TOKEN` section.

    <figure>
        <img src="/docs/showcases/setup/8.png" alt="Image">
        <figcaption>Copying the bot token</figcaption>
    </figure>

10. Paste the token to `token` field in the `settings.json` file.

    <figure>
        <img src="/docs/showcases/setup/9.png" alt="Image">
        <figcaption>Inserting the token to settings file</figcaption>
    </figure>

11. Open terminal in the bot's folder and type `node index.js`.

    <figure>
        <img src="/docs/showcases/setup/10.png" alt="Image">
        <figcaption>Launching the bot</figcaption>
    </figure>

12. That's it, the bot is running now.

    <figure>
        <img src="/docs/showcases/setup/11.png" alt="Image">
        <figcaption>The bot is now online</figcaption>
    </figure>