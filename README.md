# MyTelegramOrgRoBot

~~(yet)~~ another my.telegram.org scrapper inside Telegram.

- can be found on [Telegram](https://telegram.dog/)

## installing

#### The Easy Way

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)


#### The Legacy Way

- clone the repository, locally.
```sh
git clone https://GitHub.com/AmineSoukara/MyTelegramOrgBot.git
```

- change the directory.
```sh
cd MyTelegramOrgBot
```

- create a virtual environment.
```sh
virtualenv -p /usr/bin/python3 venv
```

- activate the virtual environment.
```sh
. ./venv/bin/activate
```

- install the requirements.
```sh
pip install -r requirements.txt
```

- create config.py

- run the bot
```sh
python3 bot.py
```

## [@DamienSoukara](https://telegram.dog/DamienSoukara)

- Only `TG_BOT_TOKEN` environment variables is mandatory.
- The Telegram RoBot should work without setting the non-mandatory variables.
- Please report any issues to the support group: [@DamienHelp](https://t.me/damienHelp)


## learning

check out the [helper_funcs](https://github.com/AmineSoukara/MyTelegramOrgBot/tree/master/helper_funcs) directory, to see how my.telegram.org is scrapped.

## LICENSE
[AGPLv3](https://github.com/AmineSoukara/MyTelegramOrgBot/tree/master/LICENSE)

## credits

- Libraries Used:
  - [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)
  - [requests](https://github.com/psf/requests)
  - [beautifulsoup4](https://pypi.org/project/beautifulsoup4)
