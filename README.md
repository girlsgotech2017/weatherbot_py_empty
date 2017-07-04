1. Do: <br/>
sudo pip install -r requirements.txt (python 2)<br/>
sudo pip3 install -r requirements.txt (python 3)<br/>
2. Change python weather_telegrambot_empty.py to python weather_telegrambot.py
3. Have the weather.ini files with the following content:

[Weather]<br/>
api_key = {your key}

[Telegram]<br/>
token = {your bot token}

4. python weather_telegrambot.py
