# Discord.py-Music-Bot
A music bot built with the discord.py library

# Installion
- Open a command prompt and type in ```git clone https://github.com/palmtrww/Discord.py-Music-Bot.git && cd Discord.py-Music-Bot```
- Go to https://discord.com/developers/applications and create a bot
- Go to the "Bot" tab and click "Create a new bot", Then copy the bot token
- Go to the Oauth2 Tab and go to Scopes and click "Bot" in the options
- Then another box will pop up thats the bot permissions but whatever you want for those and it will generate a link
- Copy that link and paste it into you're broswer and invite it to any server you want
-  Then in a command promot with the directory of Discord.py-Music-Bot Type in: ```pip install -r requirements.txt```
- Then go into token.0 in the data folder and paste you're bot token
- The type in: python launcher.py
- If you want to change the prefix go to bot/bot.py and in self.prefix change it to whatever you want (Default is .)
You will also need:

- [OpenJDK 13.0.2](https://jdk.java.net/archive/) (make sure to download the right one for your OS)
- The latest version of [Lavalink](https://ci.fredboat.com/viewLog.html?buildId=lastSuccessful&buildTypeId=Lavalink_Build&tab=artifacts&guest=1) 
- An [application.yml](https://github.com/Frederikam/Lavalink/blob/master/LavalinkServer/application.yml.example) file, with the host set to 127.0.0.1
- Then add the jdk folder into the project and drag the application.yml and Lavalink.jar into jdk/bin
- Then open a terminal and cd into jdk/bin, Then run: ```java -jar Lavalink.jar```
