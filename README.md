# 🎧 Discord Music Bot (Lavalink)

A feature-rich, easy-to-use Discord music bot powered by [Lavalink](https://github.com/lavalink-devs/Lavalink). Stream high-quality music from platforms like YouTube, Spotify, SoundCloud, and more.

---

## 🚀 Features

- 🎵 Play music from YouTube, Spotify, and SoundCloud  
- 📂 Manage song queues: view, skip, remove, clear  
- 🔁 Loop and shuffle playback  
- ⏸️ Pause, resume, stop music  
- 🎚️ Volume control  
- 🔊 Auto join and leave voice channels  
- ⚙️ Lavalink integration for smooth audio streaming  
- 💤 Auto-disconnect when idle

---

## 📦 Requirements

- [Node.js](https://nodejs.org/) v16 or higher  
- A running [Lavalink](https://github.com/lavalink-devs/Lavalink) server  
- A Discord bot token from [Discord Developer Portal](https://discord.com/developers/applications)

---

## 🛠️ Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/discord-music-bot.git

# 2. Navigate into the directory
cd discord-music-bot

# 3. Install dependencies
npm install

# 4. Set up environment variables
cp .env.example .env

💬 Available Commands
Command	Description
`/play [url	song]`
/skip	Skip the current song
/pause	Pause playback
/resume	Resume playback
/stop	Stop music and clear the queue
/queue	Display the current song queue
/volume [1-100]	Set playback volume
/loop	Toggle loop mode
/shuffle	Shuffle the current queue
/leave	Disconnect the bot from the VC

🔧 Lavalink Server Setup
server:
  port: 2333
lavalink:
  server:
    password: "youshallnotpass"
    sources:
      youtube: true
      soundcloud: true
      spotify: true

copyright by RinDev 2022
