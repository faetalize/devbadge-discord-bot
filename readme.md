# Simple Discord Bot | Supports Slash Commands
## Want the *Active Developer* badge? Run the bot, execute the ping command, and you'll get it in less than 48 hours!

* Create a new [Discord Application](https://discord.com/developers/applications).
* Create a bot user for the application.
* Reset the *Token*, copy it alongside the *Client_ID* (found in the OAuth2 section).
* Rename `secrets-example.js` to `secrets.js`
* Insert the *Token* and *Client_ID* in `secrets.js`
* Run the bot

    ```
    node index.js
    ```
* Invite the bot with **bot** and **applications.commands** scopes. To create an invite link, go to the OAuth2 section, then *URL Generator*. Make sure to tick both scopes, and give the bot Administrator permission just in case.
* Use the `ping` command in the server you invited the bot to.
* Check https://discord.com/developers/active-developer in 48 hours to redeem!