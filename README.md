# Popular Plex

This script is designed to run weekly, generating collections in Plex of most popular Movies and Television based on the data from the Tautulli API. It uses the [python-plexapi](https://github.com/pkkid/python-plexapi) package and [requests](http://python-requests.org/). It provides two options for login, Server/Access Token or Username/Password/Server, access token is preferred and when set username/password/server can be blank.

The idea behind this project was to recreate Netflix's 'What's Popular' list

![Screenshot of Popular Movies Collections](/Screenshots/Movies.png)
![Screenshot of Popular TV Collections](/Screenshots/TV.png)

## Requirements

- Python
- [Plex](https://plex.tv)
- [Tautulli](https://github.com/Tautulli/Tautulli)

## Setup

```sh
cp config.ini.example config.ini
```

> Edit `config.ini` in your preferred text editor

```sh
pip install -r requirements.txt
python plextopplaylist.py
```
