# MeMusic
Discord Music Bot. Remake and edited some scripts. Bae I love you &lt;3. We are working to change License to MIT, this time you can download the bot. No Problems.
## Upgrading to v1...
MeMusic currently using old Disco Discord Player v5 yet! It's on the way, feel free to add a star to this repository to show your support. In the meantime, you should use **[discord-music-bot](https://github.com/Androz2091/discord-music-bot)**. Please do not spam issues here as it should have probably been resolved in the new repo. Thanks.

A complete code to download for a music bot. Using a module (discord-player) 🎧

Looking for a code for a music bot ? This fully open source code is made for your project !

If you need help with this project, to get support faster you can join the help server by just clicking [here](https://discord.gg/5cGSYV8ZZj).

### ⚡ Installation

Well, let's start by downloading the code.
Go to the folder `config` then the file `bot.js`.
For the bot to be able to start, please complete the file with your credentials as follows :

- For emojis

```js
emojis: {
    off: ':x:',
    error: ':warning:',
    queue: ':bar_chart:',
    music: ':musical_note:',
    success: ':white_check_mark:',
}
```

- For configuration

```js
discord: {
    token: 'TOKEN',
    prefix: 'PREFIX',
    activity: 'ACTIVITY',
}
```

- `token`, the token of the bot available on the [Discord Developers](https://discordapp.com/developers/applications) section.
- `prefix`, the prefix that will be set to use the bot.
- `activity`, the activity of the bot.

In the console, type `npm install` to install all dependencies.

- To start the bot :

```
#With Node
node index.js
npm start #Indicated in package.json

#With pm2
pm2 start index.js --name "MusicBot"
```

All you have to do is turn on your bot !

### 🎵 Music commands

```
play <name/URL>, play music in a voice channel.
search <name>, open a panel to choose a music and then play it.
pause, pause the current music.
resume, puts the current music back on.
queue, see the next songs.
clear-queue, remove music in the queue.
shuffle, to mix the queue.
nowplaying, see music in progress.
loop, to enable or disable the repeat function.
volume <1 - 100>, change the volume.
skip, skip to next music.
stop, stop all music.
filter <filter>, add / remove filter.
w-filters, see filters.
```

### 💡 General commands

```
ping, see the bot latency.
help, see the list of available commands.
debug, see number of voice connections.
```

### 🏓 Utilities (to change the code)

Find all the functions available on the official code [right here](https://github.com/Androz2091/discord-player).

This is used with [discord.js](https://www.npmjs.com/package/discord.js) and [discord-player](https://www.npmjs.com/package/discord-player).
