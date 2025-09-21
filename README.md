# A7 Discord Bot 🛡️

a7 is a powerful, server-specific Discord bot built in Python using `discord.py`. It helps in automating moderation tasks and creating a welcoming environment for members. With features like custom welcome messages, anti-link protection, member count channel updates, auto role assignment, and restricted DM controls — it's the all-in-one solution to manage your Discord server efficiently.

---

## 🚀 Features

- 👋 **Custom Welcome Messages** with GIF support
- 👥 **Real-time Member Count** updates in a dedicated channel
- 🚫 **Anti-Link System** — blocks links from everyone except authorized users
- 🎨 **Embed Message Support** — clean, styled announcements or info
- 📩 **Mass DM Blocker** — restricts users from sending personal messages to everyone
- 🎭 **Auto Role Assignment** on member join (custom role per server)
- 🔒 **Owner & Authorized Users Only Controls**

---

## 🛠️ Tech Stack

- **Language**: Python

---

## 🔧 Setup Instructions

1. **Clone the repository**
   ```arm
   git clone https://github.com/adityatheog/A7-Discord-Bot.git
   ```
2. **Install dependencies**
   ```arm
   pip install -r requirements.txt
   ```

3. **Bot Token & Configuration**
    ```arm
    {
    "DISCORD_TOKEN": "your bot token",
    "servers": {
        "SERVER_ID": {
            "AUTHORIZED_USER_IDS": ["User_IDs_allowed_to_use_commands"],
            "CLIENT_ROLE_ID": ROLE_ID_ASSIGNED_TO_NEW_MEMBERS,
            "WELCOME_CHANNEL_ID": "Channel_ID_where_welcome_msg_is_sent",
            "WELCOME_IMAGE_URL": "https://your-custom-welcome-gif.gif",
            "RULES_CHANNEL_ID": "Channel_ID_to_redirect_for_rules",
            "MAIN_CHAT_CHANNEL_ID": "Channel_ID_for_main_chat_mention",
            "MEMBER_COUNT_CHANNEL_ID": "Channel_ID_to_show_member_count",
            "MEMBER_ROLE_NAME": "Role_Name_assigned_to_members",
            "EMBED_COLOR": EMBED_COLOR_INTEGER
            }
        }
    }
    ```

4. **Run the Bot**
   ```arm
   python bot.py
   ```
---


## 🙋‍♂️ Owner Info

> This bot is developed by:

- 👤 **Name**: Aditya Sutar
- 💬 **Discord Server**: [A7](https://discord.gg/A7)
- 🛠️ **GitHub**: [github.com/adityatheog](https://github.com/adityatheog)
- 🌐 **Portfolio**: [A7](https://)

For queries, support, or collaboration, feel free to reach out via Discord or GitHub.

---

**© 2025 A7 — All Rights Reserved**

