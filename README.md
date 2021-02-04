## Installation

### Complete the file `config.json`

- `id` must be your bot ID.
- `token` must be the bot's token .
- `prefix` must be the bot prefix .
- `secret` can be found in your bot page on discordapp.com
- `url` should be the URL that users will be redirected if you're local, put simply: http://localhost.
- `production` must be true or false . If you are using a URL with the port (like localhost:3000), put false . Otherwise, put true .

## Operation

> **Note: `npm` and `nodejs` are required to make the bot work.**

- Be sure to put the OAuth2 redirection in the **REDIRECTS** of your bot.
![image](https://cdn.discordapp.com/attachments/485886312398848030/485886331336130561/unknown.png)
- Do in `npm install` order to install all the modules necessary for the functioning of the bot.
- To start the bot, do `node app.js`.
