# Simple discord bot to get badge

## Dependencies 

* discord.js (**npmjs**)

* dotenv (**npmjs**)

## How to run 

* Install dependencies:
```
npm install
```

* Create a .env and fill the informations: 
### # Linux:
```
touch .env
```
### # Windows 
* powershell:

```
"" > .env
```
* cmd:

```
echo. > .env
```

### # Inside .env:

```js
TOKEN=YOUR_BOT_TOKEN
GUILD_ID=YOUR_DISCORD_SERVER_ID
CLIENT_ID=YOUR_DISCORD_BOT_ID
```
### # Register slash commands:

```
node register-commands.js
```

### # Run discord bot:
```
node index.js
```


