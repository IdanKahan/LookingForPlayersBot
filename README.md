# Looking For Players Bot 🎮

This is a custom Discord bot I made for me and my friends to easily find people to play games with.  
It lets you click buttons for games you want to play and pings others who are into the same game and currently online.

---

## ✨ Features

- Slash command `/spawn` posts a message with interactive game buttons.
- Click a button to notify others that you're looking for players.
- Automatically tags users with the matching role who might want to join.
- Detects if you're in a voice channel and includes that in the ping.
- Add or remove game buttons dynamically with `/addbutton` and `/removebutton`.
- Each button can have a custom emoji and role assigned.

---

## 🚀 Usage

1. Set your bot token in the environment as `token`.
2. Set the channel ID inside the code where the bot sends the embed (`channel = bot.get_channel(...)`).
3. Run the bot.
4. Use `/spawn` in a text channel to post the game buttons.
5. Click a button while in a voice channel to ping friends with the same role of the game you want to play.

---

## 🚶 Uses a webserver

This bot includes a simple webserver (`webserver.py`) so it can be pinged easily and stay alive 24/7
