# Simple Discord Bot | Grants Active Developer Badge
## Want the *Active Developer* badge? Run the bot, execute the ping command, and you'll get it in less than 48 hours!

1. Create a new [Discord Application](https://discord.com/developers/applications).
2. Create a bot user for the application.
3. Reset the *Token*, copy it alongside the *Client_ID* (found in the *Bot* and *OAuth2* sections, respectively).
4. Rename `secrets-example.js` to `secrets.js`
5. Insert the *Token* and *Client_ID* in `secrets.js`
6. Initialize the project with
    ```
    npm install
    ```
7. Run the bot
    ```
    node index.js
    ```
8. Invite the bot to a server with [community](https://support.discord.com/hc/en-us/articles/360047132851-Enabling-Your-Community-Server) enabled. To create an invite link, go to the OAuth2 section, then *URL Generator*. Make sure to activate the **bot** and **applications.commands** scopes, and give the bot Administrator permission just in case.
9. Use the `ping` command in the server you invited the bot to.
10. Check https://discord.com/developers/active-developer in 48 hours to redeem!

*NOTE: Make sure you have the “Use data to improve Discord” setting enabled under `User Settings > Privacy & Safety` otherwise you won't be able to be marked as eligible.*
