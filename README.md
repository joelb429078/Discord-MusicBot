# Discord Music Bot
![discordbotmusics](https://github.com/joelb429078/Discord-MusicBot/assets/160978621/1ff30595-d97b-4ced-bd9b-0685faa96191)

This project is a Discord bot that integrates with YouTube to play music in voice channels. It utilizes the `youtube-dl` library to fetch songs from YouTube and provides various features like queues, a voting system for skipping songs, and more.

### Features

- **Play Music**: Users can request songs by typing the song name or URL, and the bot will play the song from YouTube.
- **Queue System**: Supports queuing up to 10 songs.
- **Voting System**: Users can vote to skip the current song, requiring at least 80% approval to skip.
- **Basic Controls**: Commands to join/leave voice channels, pause/resume playback, and skip songs.
- **Search Functionality**: Allows users to search for songs and select from the search results.

### Technologies Used

- **Programming Language**: Python
- **Discord Library**: discord.py
- **YouTube Integration**: youtube-dl, pafy

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/joelb429078/Discord-MusicBot.git
   ```
2. Navigate to the project directory:
   ```sh
   cd discord-music-bot
   ```
3. Install the required libraries:
   ```sh
   pip install discord.py youtube-dl pafy
   ```
4. Set up your Discord bot token and other configurations in the script.
5. Run the bot:
   ```sh
   python bot.py
   ```

### Commands

- **!join:** Connect the bot to your current voice channel.
- **!leave:** Disconnect the bot from the voice channel.
- **!play <song>:** Play a song by name or URL. If the bot is already playing, the song will be added to the queue.
- **!queue:** Display the current song queue.
- **!skip:** Vote to skip the current song. Requires 80% approval to skip.
- **!pause:** Pause the current song.
- **!resume:** Resume the paused song.
- **!search <song>:** Search for a song and display the results.
- **!nice:** Appreciate the tune with a reaction.
- **!deadtune:** Skip the current song with a funny message.

### License
This project is licensed under the MIT License.
