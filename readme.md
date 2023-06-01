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
* Invite the bot to a server with [community](https://support.discord.com/hc/en-us/articles/360047132851-Enabling-Your-Community-Server) enabled. To create an invite link, go to the OAuth2 section, then *URL Generator*. Make sure to activate the **bot** and **applications.commands** scopes, and give the bot Administrator permission just in case.
* Use the `ping` command in the server you invited the bot to.
* Check https://discord.com/developers/active-developer in 48 hours to redeem!

*NOTE: Make sure you have the “Use data to improve Discord” setting enabled under User Settings > Privacy & Safety otherwise you won't be able to be marked as eligible.*
