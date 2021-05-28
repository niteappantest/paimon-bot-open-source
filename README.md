<div align="center">
<img src="https://images5.alphacoders.com/911/911614.png" alt="BocchiBot" width="500" />

# **Paimon Bot**
>
>

<h3 align="center">Made with ❤️ by</h3>
<p align="center">
  <a href="https://github.com/hardiantojek93"><img src="https://avatars3.githubusercontent.com/u/28254882?s=400&u=25765902db0b709938966cf4127ac11af5eafb5d&v=4" height="128" width="128" /></a>
</p>

<p align="center">
  <a href="https://github.com/hardiantojek93"><img title="Author" src="https://img.shields.io/badge/Author-Hardianto-purple.svg?style=for-the-badge&logo=github" /></a>
</p>

<p align="center">
  <a href="https://github.com/hardiantojek93/paimon-bot-open-source#requirements">Requirements</a> •
  <a href="https://github.com/paimon-bot-open-source#installation">Installation</a> •
  <a href="https://github.com/paimon-bot-open-source#features">Features</a> •
  <a href="https://github.com/hardianto/paimon-bot-open-source#thanks-to">Thanks to</a> •
  <a href="https://github.com/hardiantojek93/paimon-bot-open-source#license">License</a>
</p>


# Requirements
* [Node.js](https://nodejs.org/en/)
* [Git](https://git-scm.com/downloads)
* [FFmpeg](https://www.gyan.dev/ffmpeg/builds/)
* Any text editor

# Installation
## 📝 Cloning this repo
```cmd
> git clone https://github.com/hardiantojek93/paimon-bot-open-source.git
> cd paimon-bot
```

##


## 🛠️ Installing the FFmpeg
* Download one of the available versions of FFmpeg by clicking [this link](https://www.gyan.dev/ffmpeg/builds/).
* Extract the file to `C:\` path.
* Rename the extracted folder to `ffmpeg`.
* Run Command Prompt as Administrator.
* Run this command:
```cmd
> setx /m PATH "C:\ffmpeg\bin;%PATH%"
```
It will give us a callback like `SUCCESS: specified value was saved`.
* Now that you've FFmpeg installed, verify that it's working by running this command to see version number:
```cmd
> ffmpeg -version
```

## 🔍 Installing the dependencies
```cmd
> npm install
```

## 🆗 Running the bot
Regular node:
```cmd
> npm start
```

PM2:
```cmd
> pm2 start index.js
> pm2 monit
```

PM2 with cron job (restart after 5 hours):
```cmd
> pm2 start index.js --cron "* */5 * * *"
> pm2 monit
```

After that scan the QR code using your WhatsApp in your phone!

# Features
If you want to unlo

# Thanks to
* [`Adiwajshing`](https://github.com/adiwajshing/baileys)
* [`YogaSakti/imageToSticker`](https://github.com/YogaSakti/imageToSticker)
* [`AlvioAdjiJanuar`](https://github.com/AlvioAdjiJanuar)
* [`VideFrelan`](https://github.com/VideFrelan)
* [`Hexagon`](https://github.com/hexagonz)
* [`LolHuman`](https://github.com/Lol-Human)
* [`Aqul`](https://github.com/zenn08)
* [`hardiantojek93`](https://github.com/hardiantojek93)

# License Readme.md
**BocchiBot** © [SlavyanDesu](https://github.com/SlavyanDesu), released under the MIT License.
Authored and maintained by SlavyanDesu.

<p align="center">
  <a href="https://app.fossa.com/projects/git%2Bgithub.com%2FSlavyanDesu%2FBocchiBot?ref=badge_large"><img src="https://app.fossa.com/api/projects/git%2Bgithub.com%2FSlavyanDesu%2FBocchiBot.svg?type=large" />
</p>
