# telegram_streamer 

## What's this?

This is a simple implement telegram userbot for streaming videos from telegram to the web browser

using telethon telegram client libary


## How to run


Install requirements
```pip
pip3 install -r requirements.txt
```
Get your telegram account credentials from https://my.telegram.org/auth
```
export TG_API_ID=<API_ID>
export TG_API_HASH=<API_HASH>
```



run
```
python3 main.py
```


## Additional settings
```
export HOST=0.0.0.0
export PORT=80
export PUBLIC_URL=http://$(curl -s ifconfig.me/ip):$PORT
export DEBUG=true
```


## Credits
https://github.com/tulir/tgfilestream

Thanks for awesome work!
