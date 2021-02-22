# 24/7 discord bot template

option 1 for self hosting:

in the .env file change your-token to your discord bots token. Or you could use the config.json and put your token in it (i use the config.json)

go to repl.it and import this repo and run the repl. there should be some packager files now.

then copy the url at the pot of the output and copy it. go to uptimerobot.com and make an account or sign in. make a monitor and choose https, make a name, and put the url in the url slot. then press the create monitor button and your bot will be online 99.9 percent of the time!

you can put your bot files in the repl like commands and stuff, but make sure there is not any files named index.js or .env (.env is okay just move the contents of it over to the .env that comes with your bot.)

option 2 for self hosting: (DEFINITLY THE EASIER OPTION)

put the following code in your index.js file

var _247DiscordJsBotTemplate = require("@chelms21/24-7-discord.js-bot-template")
