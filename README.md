[![IMG-3395.jpg](https://i.postimg.cc/Hny3Hj0X/IMG-3395.jpg)](https://postimg.cc/2LCn7kKS)

# About

A Discord bot for nominating and voting for a member of the week.

# How it works

The bot will create a reaction-based poll every Friday at 12 AM UTC and announce the winner on Sunday at 12 PM UTC.

Server members can nominate one other user for member of the week by using `/nominate` followed by the user's name.

Any nominations after the poll is created will be ignored. Nominations are cleared once the winner is announced. The bot's reaction to the poll will not be counted towards the final vote, and ties will be announced with no winner.

The bot requires the `SEND MESSAGES`, `READ MESSAGE HISTORY`, `READ MESSAGE HISTORY`, `USE APPLICATION COMMANDS`, and `ADD REACTIONS` permissions

# Dependencies

discord.py 2.5.0

python-dotenv 1.0.1

apscheduler 3.11.0

# Installation

Make sure you have Python 3.12+

Clone the repository.

```
git clone https://github.com/ifeeljoy/member-of-the-week.git
```

Install dependencies. 

```
pip install discord.py python-dotenv apscheduler
```

Rename `.env-example` to .env and add your bot token and channel ID.

```
# Your bot's token.
BOT_TOKEN=here

# The channel for creating the poll and announcing the winner.
CHANNEL_ID=here
```

Run the bot.

```
python index.py
```

# License
This project is licensed under the GNU Affero General Public License v3.0. See the LICENSE file for more details.

# Buy Me A Coffee
[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/mozzarella)
