Flair Moderator
=============

[/u/FlairModerator](https://www.reddit.com/user/flairmoderator) ensures that every submission on a subreddit will have flair. For more details, please visit [/r/FlairModerator](https://www.reddit.com/r/FlairModerator/).

About
-----

This bot requires `python3.6` or later.

After updating the appropriate global variables and renaming `praw.ini.example` over to `praw.ini` with the appropriate credentials, the following commands will get you up and running:

```
python3.6 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python3.6 bot.py
```

This bot logs to `./bot.log` and `stdout`.

Contributing
------------

The `develop` branch is used to development. `master` reflects the current state of production.