# nbot-wa
<p align="center" width="100%">
    <a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FNurutomo%2Fnbot-wa&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false"/></a>
    div align="center">

        <img src="20211004_132256.png" alt="GIF" width="250" height="200"/>
</p>

# Pre-Installation
- Download **Git** [here](https://git-scm.com/downloads) (Termux: `pkg install git`)
- Download **NodeJS** [here](https://nodejs.org/en/download/) (Termux: `pkg install nodejs`)
- Download **FFmpeg** [here](https://www.gyan.dev/ffmpeg/builds/) (Termux: `pkg install ffmpeg`)

# Installation
Type these on `cmd`, optional: `npm i node-gyp`
```
git clone https://github.com/Nurutomo/nbot-wa.git
cd nbot-wa
npm i
```
# Starting
```
npm start <sessionName>
```
or
```
node . <sessionName>
```

Default Prefixes: `!, @, #, $, %, ^, &, /, .`
# Features
| Features                                     |                   Supported                  |
|----------------------------------------------|:--------------------------------------------:|
| Image to Sticker                             |                  Yes (Sharp)                 |
| Video/GIF to Animated Sticker                |                 Yes (FFmpeg)                 |
| Image /w Text to Sticker                     |                 Yes (MemeGen)                |
| Meme Generator                               |                 Yes (MemeGen)                |
| YTMP3 Downloader                             |                 Yes (y2mate)                 |
| YTMP4 Downloader                             |                 Yes (y2mate)                 |
| Video to MP3                                 |                 Yes (FFmpeg)                 |
| Bass Boosting                                |                 Yes (FFmpeg)                 |
| Earrape                                      |        Yes (node-wav and WebAudioAPI)        |
| Promote /w Multiple Users (by Mention)       |                      Yes                     |
| Demote /w Multiple Users (by Mention)        |                      Yes                     |
| Kick /w Multiple Users (seperated by commas) |                      Yes                     |
| Add /w Multiple Users (seperated by spaces)  |                      Yes                     |
| Broadcast (Need to enable on each group)     |                      Yes                     |
| Broadcast Permission                         |                      Yes                     |
| Instagram Downloader                         | Unlikely ([API](mhankbarbar-api--nurutomo.repl.co)) |

# Environment Variables
Windows: `set VARIABLENAME=VALUE`
Linux/Termux: `VARIABLENAME=VALUE`

## List
- `prefix` RegExp Prefixes `prefix=[!#%]` will set prefix to `!, #, %`
