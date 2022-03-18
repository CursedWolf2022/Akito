![Node build](https://github.com/CursedWolf2022/Akito/actions/workflows/node.yml/badge.svg)
![Docker build](https://github.com/CursedWolf2022/Akito/actions/workflows/docker.yml/badge.svg)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

![logo](https://repository-images.githubusercontent.com/186841818/8aa95700-7730-11e9-84be-e80f28520325)

# 🤖 Akito (Discord Music Bot)
> Akito is a Discord Music Bot built with discord.js & uses Command Handler from [discordjs.guide](https://discordjs.guide)

## Requirements

1. Discord Bot Token **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
2. YouTube Data API Key **[Guide](https://developers.google.com/youtube/v3/getting-started)**  
2.1 Soundcloud Client ID **[Guide](https://github.com/zackradisic/node-soundcloud-downloader#client-id)**
3. Node.js v14.0.0 or newer
4. Bot Hoster

## 🚀 Getting Started

```sh
git clone https://github.com/CursedWolf2022/Akito.git
cd Akito
npm install
```

After installation finishes follow configuration instructions then run `node index.js` to start the bot.

## ⚙️ Configuration

Fill out the values:

⚠️ **Note: Never commit or share your token or api keys publicly** ⚠️

```json
{
  "TOKEN": "",
  "YOUTUBE_API_KEY": "",
  "SOUNDCLOUD_CLIENT_ID": "",
  "MAX_PLAYLIST_SIZE": 10,
  "PREFIX": "/",
  "PRUNING": false,
  "LOCALE": "en",
  "DEFAULT_VOLUME": 100,
  "STAY_TIME": 300
}
```

## 📝 Features & Commands

> Note: The default prefix is '>'

* 🎶 Play music from YouTube via url

`>play https://youtu.be/mRD0-GxqHVo`

* 🔎 Play music from YouTube via search query

`>play Heat Waves`

* 🎶 Play music from Soundcloud via url

`>play https://soundcloud.com/glassanimals/heat-waves`

* 🔎 Search and select music to play

`>search Heat Waves`

Reply with song number or numbers seperated by comma that you wish to play

Examples: `1` or `1,2,3`

* 📃 Play youtube playlists via url

`>playlist https://www.youtube.com/watch?v=YlUKcNNmywk&list=PL5RNCwK3GIO13SR_o57bGJCEmqFAwq82c`

* 🔎 Play youtube playlists via search query

`>playlist linkin park meteora`
* Now Playing (>np)
* Queue system (>queue, >q)
* Loop / Repeat (>loop)
* Shuffle (>shuffle)
* Volume control (>volume, >v)
* Lyrics (>lyrics, >ly)
* Pause (>pause)
* Resume (>resume, >r)
* Skip (>skip, >s)
* Skip to song # in queue (>skipto, >st)
* Move a song in the queue (>move, >mv)
* Remove song # from queue (>remove, >rm)
* Play an mp3 clip (/clip song.mp3) (put the file in sounds folder)
* List all clips (>clips)
* Show ping to Discord API (>ping)
* Show bot uptime (>uptime)
* Toggle pruning of bot messages (>pruning)
* Help (>help, >h)
* Command Handler from [discordjs.guide](https://discordjs.guide/)
* Media Controls via Reactions

![reactions](https://i.imgur.com/hSOHtwI.png)

## 🌎 Locales

Currently available locales are:
- English (en)
- Arabic (ar)
- Brazilian Portuguese (pt_br)
- Czech (cs)
- Dutch (nl)
- French (fr)
- German (de)
- Greek (el)
- Indonesian (id)
- Italian (it)
- Japanese (ja)
- Korean (ko)
- Minionese (mi)
- Persian (fa)
- Polish (pl)
- Russian (ru)
- Simplified Chinese (zh_cn)
- Singaporean Mandarin (zh_sg)
- Spanish (es)
- Swedish (sv)
- Traditional Chinese (zh_tw)
- Thai (th)
- Turkish (tr)
- Ukrainian (uk)
- Vietnamese (vi)
- Check [Contributing](#-contributing) if you wish to help add more languages!
- For languages please use [ISO 639-1](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) two letter format

## 🤝 Contributing

1. [Fork the repository](https://github.com/CursedWolf2022/Akito/fork)
2. Clone your fork: `git clone https://github.com/your-username/Akito.git`
3. Create your feature branch: `git checkout -b my-new-feature`
4. Stage changes `git add .`
5. Commit your changes: `cz` OR `npm run commit` do not use `git commit`
6. Push to the branch: `git push origin my-new-feature`
7. Submit a pull request

## 📝 Credits

[@CursedWolf2022](https://github.com/CursedWolf2022)
