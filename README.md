## localplayer-discordbot
A discord bot that plays music files locally with metadata support, sent to a channel as an embed.

![Image from Discord](https://daijobudes.s-ul.eu/RKa0rvfW.png)

### Bot Token
Simply get it from here https://discord.com/developers/applications/

Create a `token.txt` inside the directory with your discord bot token. This is to separate the bot token for privacy purposes.

### Running the bot
Clone this repository first by `git clone https://github.com/DaijobuDes/localplayer-discordbot`.

**Optional**: Create a virtual environment using `python3 -m venv localplayer-discordbot` then `cd localplayer-discordbot`.

Then install required python packages by `pip3 install -r requirements.txt`.

On linux, run `./start.sh` to run the bot. (Also works in Android phones using Termux with dependencies installed.)

On Windows, run `start.bat` to run the bot.

File types supported (with metadata)

- [ ] FLAC
- [ ] WAV
- [ ] MP3
- [ ] AAC/M4A
- [ ] OGG (probably)
