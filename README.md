<p align="center"><a href="https://t.me/VeezVideoBot"><img src="https://github.com/levina-lab/video-stream/raw/main/driver/veezlogo.png"></a></p>
<p align="center">
    <br><b>Video Stream is an Open-Source Telegram Bot project that's allow you to play Video & Music on Telegram Group Video Chat</b><br>
</p>
<p align="center">
    <a href="https://www.python.org/" alt="made-with-python"> <img src="https://img.shields.io/badge/Made%20with-Python-black.svg?style=flat-square&logo=python&logoColor=blue&color=red" /></a>
    <a href="https://github.com/levina-lab/video-stream/graphs/commit-activity" alt="Maintenance"> <img src="https://img.shields.io/badge/Maintained%3F-yes-red.svg?style=flat-square" /></a>
    <a href="https://app.codacy.com/gh/levina-lab/video-stream/dashboard"> <img src="https://img.shields.io/codacy/grade/a723cb464d5a4d25be3152b5d71de82d?color=red&logo=codacy&style=flat-square" alt="Codacy" /></a><br>
    <a href="https://github.com/levina-lab/video-stream"> <img src="https://img.shields.io/github/repo-size/levina-lab/video-stream?color=red&logo=github&logoColor=blue&style=flat-square" /></a>
    <a href="https://github.com/levina-lab/video-stream/commits/main"> <img src="https://img.shields.io/github/last-commit/levina-lab/video-stream?color=red&logo=github&logoColor=blue&style=flat-square" /></a>
    <a href="https://github.com/levina-lab/video-stream/issues"> <img src="https://img.shields.io/github/issues/levina-lab/video-stream?color=red&logo=github&logoColor=blue&style=flat-square" /></a>
    <a href="https://github.com/levina-lab/video-stream/network/members"> <img src="https://img.shields.io/github/forks/levina-lab/video-stream?color=red&logo=github&logoColor=blue&style=flat-square" /></a>  
    <a href="https://github.com/levina-lab/video-stream/network/members"> <img src="https://img.shields.io/github/stars/levina-lab/video-stream?color=red&logo=github&logoColor=blue&style=flat-square" /></a>  
</p>

## 📊 CodeFactor Stats
[![CodeFactor](https://www.codefactor.io/repository/github/levina-lab/video-stream/badge)](https://www.codefactor.io/repository/github/levina-lab/video-stream)

## 🎭 Preview
<p align="center">
  <img src="https://telegra.ph/file/11e63eb2b59ad15a43a03.jpg">
</p>

## ✨ Features
- Music & Video stream support
- Multi-Chat support
- Playlist & Queue support
- Skip, Pause, Resume, Stop feature
- Music & Video downloader feature
- Inline Search support
- YouTube direct search support
- YouTube/Local/Live/m3u8 stream support
- Control With Button support
- Volume Control
- Userbot Auto Join
- Broadcast & Global Ban
- Shell Executor (eval & sh)
- SpeedTest Runner
- Updater & Restart feature

## 🛠 Commands:
| Command | Description |
| ------ | ------ |
| `/play (query)` | play music from youtube |
| `/vplay (query)` | play video from youtube |
| `/vstream (live link)` | play live streaming video |
| `/pause` | pause the streaming (admin only) |
| `/resume` | resume the streaming (admin only) |
| `/skip` | goes to the next track (admin only) |
| `/stop` | stop the playback and clear queues (admin only) |
| `/vmute` | for mute the userbot on group call |
| `/vunmute` | for unmute the userbot on group call |
| `/volume 1/200` | adjust the volume of userbot (userbot must be admin) |
| `/playlist` | show you all the current stream list |
| `/song (query)` | download music from youtube |
| `/video (query)` | download video from youtube |
| `/userbotjoin` | invite the userbot to join group (admin only) |
| `/userbotleave` | instruct userbot to leave the group (admin only) |
| `/leaveall` | order the userbot to leave from all group (bot owner only) |
| `/update` | update your bot directly without leaving telegram (bot owner only) |
| `/restart` | restart your bot directly without leaving telegram (bot owner only) |
| `/speedtest` | run server speedtest that you use to run your bot |
| `/broadcast` | brodcast message to all group that in bot database |
| `/gban & /ungban` | use this to gban someone and ungban them |
| `/stats` | get the bot current statistic |
| `/calls` | show you the list of current running group call in bot database |

## Generate Session Name 🔻

[![GenerateString](https://img.shields.io/badge/repl.it-generateString-yellowgreen)](https://replit.com/@levinalab/Session-Generator?lite=1&outputonly=1#main.py)

## Heroku Deployment 💜

<h3 align="center">Click The button below for deploy your bot to Heroku, Note: Set the app country to Europe (it will help to make the bot much faster and stable).</h3>
<p align="center"><a href="https://heroku.com/deploy"><img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy to Heroku" target="_blank"/></a></p>

📝 [NOTE]: Remember to fork this repo first then you can deploy this repo, if not your deployment proccess will failed that because Heroku has blacklisted this repo !

## VPS Deployment 📡
Get the best Quality of streaming performance by hosting it on VPS, here's the step's:

```sh
sudo apt update && apt upgrade -y
sudo apt install git curl python3-pip ffmpeg -y
pip3 install -U pip
curl -sL https://deb.nodesource.com/setup_16.x | bash -
sudo apt-get install -y nodejs
npm i -g npm
git clone https://github.com/Riswanmd16/video-stream # clone the repo.
cd video-stream
pip3 install -U -r requirements.txt
cp example.env .env # use vim to edit ENVs
vim .env # fill up the ENVs (Steps: press i to enter in insert mode then edit the file. Press Esc to exit the editing mode then type :wq! and press Enter key to save the file).
python3 main.py # run the bot.

# continue the host with screen or anything else, thanks for reading.
```

# Credits 💖

- [Levina](https://github.com/levina-lab) ``Dev``
- [Zxce3](https://github.com/Zxce3) ``Dev``
- [tofikdn](https://github.com/tofikdn) ``Dev``
- [Laky's](https://github.com/Laky-64) for [``py-tgcalls``](https://github.com/pytgcalls/pytgcalls)
- [Dan](https://github.com/delivrance) for [``Pyrogram``](https://github.com/pyrogram)

### Support & Updates 🎑
<a href="https://t.me/VeezSupportGroup"><img src="https://img.shields.io/badge/Join-Group%20Support-blue.svg?style=for-the-badge&logo=Telegram"></a> <a href="https://t.me/levinachannel"><img src="https://img.shields.io/badge/Join-Updates%20Channel-blue.svg?style=for-the-badge&logo=Telegram"></a>
