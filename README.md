# 🤖 amethystcraft-music (Discord Music Bot)
> amethystcraft-music is a music bot discord which is an improvement over Pinbot.

## Requirements

1. Discord Bot Token **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
2. YouTube Data API v3 Key **[Guide](https://developers.google.com/youtube/v3/getting-started)**  
3. Node.js v12.0.0 or newer

## 🚀 Started

```
git clone https://github.com/Amethyst-craft-lab/amethystcraft-music.git
cd amethystcraft-music
npm install
```

After installation finishes you can use `node src/main.js` to start the bot.

## ⚙️ Configuration

Rename `config.json.edit` to `config.json` and fill out the values:

⚠️ **Note: Never commit or share your token or api keys publicly** ⚠️

```json
{
    "TOKEN": "PUT-BOT-TOKEN-HERE",
    "YOUTUBE_API_KEY": "PUT-YOUR-YOUTUBE-API-KEY-HERE",
    "MAX_PLAYLIST_SIZE": 10,
    "PREFIX": "--",
    "PRUNING": false,
    "LOCALE": "id",
    "STAY_TIME": 300,
    "DEFAULT_VOLUME": 100
  }
```

Currently available locales are:
- English (en)
- Indonesian (id)
- Check [Contributing](#-contributing) if you wish to help add more languages!

## 📝 Features & Commands

> Note: The default prefix is '--'

* Now Playing (--np)
* Queue system (--queue, --q)
* Loop / Repeat (--loop)
* Shuffle (--shuffle)
* Volume control (--volume, --v)
* Lyrics (--lyrics, --ly)
* Pause (--pause)
* Resume (--resume, --r)
* Skip (--skip, --s)
* Skip to song # in queue (--skipto,--st)
* Move a song in the queue (--move, --mv)
* Remove song # from queue (--remove, --rm)
* Play an mp3 clip (--clip song.mp3) (put the file in sounds folder)
* List all clips (--clips)
* Show api ping (--ping)
* Show bot uptime (--uptime)
* Toggle pruning of bot messages (--pruning)
* Localization in 2 languages
* Help (--help, --h)
* Command Handler from [discordjs.guide](https://discordjs.guide/)
* Media Controls via Reactions

## 🤝 Contributing

1. [Fork the repository](https://github.com/Amethyst-craft-lab/amethystcraft-music/fork)
2. Clone your fork: `git clone https://github.com/your-username/amethystcraft-music.git`
3. Create your feature branch: `git checkout -b my-new-feature`
4. Commit your changes: `git commit -am 'Add some feature'`
5. Push to the branch: `git push origin my-new-feature`
6. Submit a pull request

## 📝 Credits & Support

> [Discord](https://discord.com/invite/FGw4nCbfqB)
> [Ko-Fi](https://ko-fi.com/ariflitejek)
> [Saweria](https://saweria.co/ipincamp)
> [Website](https://pinbot.amethystcraft.fun/pinbot) by `Zack`
