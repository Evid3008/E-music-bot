
[![Deploy On Heroku](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https://github.com/adityahalder/adityaplayer)


<h2>♨️ Host AdityaPlayer On VPS Server</h2>


**1. At First Copy & Paste Below Command.**

```apt update -y && apt install sudo -y && sudo apt install curl ffmpeg git nano python3-pip screen -y && cd && rm -rf AdityaPlayer && git clone https://github.com/AdityaHalder/AdityaPlayer && cd AdityaPlayer && pip3 install -r requirements.txt --force-reinstall && screen -R AdityaPlayer```


**2. Now Run This Command & Add Your Variables.**

```nano Config.env```


**Required Variables !**

`API_ID`

`API_HASH`

`BOT_TOKEN`

`STRING_SESSION`

`MONGO_DB_URL`

`OWNER_ID`

`LOG_GROUP_ID`

`START_IMAGE_URL`


**3. After That Save and Exit By Below Buttons.**

```ctrl + s```

```ctrl + x```


**4. Now Run Your Bot in Background.**

```python3 -m AdityaHalder```


**5. Now Exit From Screen & Close Your Vps & Enjoy**

```ctrl + a + d```


> [!IMPORTANT]
> If you use Aditya-Player, it is important that you have proper knowledge about it. You should follow the [**`Documentation`**](https://t.me/adityaserver) to learn about Aditya-Player.


