<p align="center"><b> Bot Ijo is a Music bot for playing music on telegram voice chat group with extra features </b></p>

<h3>Requirements</h3>

- FFmpeg
- NodeJS [nodesource.com](https://nodesource.com/)
- Python 3.8+ or Higher
- [PyTgCalls](https://github.com/pytgcalls/pytgcalls)
- [MongoDB](https://cloud.mongodb.com/)


### Commands 

- `/play <song name>` - play song you requested
- `/playlist` - Show now playing list
- `/current` - Show now playing
- `/song <song name>` - download songs you want quickly
- `/search <query>` - search videos on youtube with details
- `/video <song name>` - download videos you want quickly
- `/lyric <query>` - searching lyric 
- `/q` or `/quotly <reply text>` - make a sticker by reply text like @quotlybot
- `/paste` - paste your text or document to pastebin and make photo from that

#### Admins Only 
- `/player` - open music player settings panel
- `/pause` - pause song play
- `/resume` - resume song play
- `/skip` - play next song
- `/end` - stop music play
- `/musicplayer on` - to disable music player in your group
- `/musicplayer off` - to enable music player in your group
- `/userbotjoin` - invite assistant to your chat
- `/userbotleave` - remove assistant from your chat
- `/reload` - Refresh admin list
- `/uptime` - check the bot uptime status
- `/ping` - check the bot ping status

### Sudo User 
- `/pmpermit on | off` turn on/off the assistant pmpermit
- `/userbotleaveall` - order the assistant to leave all groups
- `/gcast` - send a broadcast message
- `/rmd` - remove all downloaded file

## If you deploy on heroku, sudo can :
- `/usage` - see your dynos usage for your app
- `/update` - to push last commit on github
- `/restart` - restarting your bot
- `/setvar <var> <value>` - add or retype your var on heroku
- `/delvar <var name>` delete your var on heroku

### pm-permit 
- `.yes` - approve user for sending message to assistant
- `.no` - disapprove user for sending message to assistant

### 🔎 Support Inline Search

### Heroku Deployment 💜
The easy way to host this bot, deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/ridho17-ind/BotIjo)

### Deploy On VPS 💙
```
- sudo apt update && apt upgrade -y
- sudo apt install git curl python3-pip ffmpeg -y`
- pip3 install -U pip
- curl -sL https://deb.nodesource.com/setup_16.x | bash -
- sudo apt-get install -y nodejs
- npm i -g npm
- git clone https://github.com/ridho17-ind/BotIjo # Clone your repo.
- cd KennedyXMusic
- pip3 install -U -r requirements.txt
- cp example.env .env #Use vim to edit ENV
- vim .env #Fill up your ENVs ( Steps press i to enter in insert mode then edit the file. Press Esc to exit the editing mode then type :wq! and press Enter key to save the file.)
- python3 main.py # Run the bot
```

### Support & Updates 🛵
<a href="https://t.me/FlicksSupport"><img src="https://img.shields.io/badge/Join-Group%20Support-red.svg?style=for-the-badge&logo=Telegram"></a> <a href="https://t.me/SadRoomsInfo"><img src="https://img.shields.io/badge/Join-Updates%20Channel-white.svg?style=for-the-badge&logo=Telegram"></a>

