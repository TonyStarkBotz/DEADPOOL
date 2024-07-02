![Typing SVG](https://readme-typing-svg.herokuapp.com/?lines=𝗧𝗛𝗜𝗦+𝗜𝗦+𝗗𝗘𝗔𝗗𝗣𝗢𝗢𝗟+𝐁𝐎𝐓!;𝗖𝗥𝗘𝗔𝗧𝗘𝗗+𝗕𝗬+𝗧𝗼𝗻𝘆𝗦𝘁𝗮𝗿𝗸+𝗕𝗢𝗧𝗭™;𝗔+𝗣𝗢𝗪𝗘𝗥𝗙𝗨𝗟𝗟+𝗧𝗚+𝗔𝗨𝗧𝗢𝗙𝗜𝗟𝗧𝗘𝗥+𝗕𝗢𝗧!)</p>
<p align="center">

<h1 align="center">
  <b> 𝑫𝑬𝑨𝑫𝑷𝑶𝑶𝑳 𝐁𝐎𝐓</b>
</h1>

[![Stars](https://img.shields.io/github/stars/TonyStarkBotz/DEADPOOL?style=flat-square&color=yellow)](https://github.com/TonyStarkBotz/DEADPOOL/stargazers)
[![Forks](https://img.shields.io/github/forks/TonyStarkBotz/DEADPOOL?style=flat-square&color=orange)](https://github.com/TonyStarkBotz/DEADPOOL/fork)
[![Size](https://img.shields.io/github/repo-size/TonyStarkBotz/DEADPOOL?style=flat-square&color=green)](https://github.com/TonyStarkBotz/DEADPOOL)   
[![Open Source Love svg2](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/TonyStarkBotz/DEADPOOL)   
[![License](https://img.shields.io/badge/License-AGPL-blue)](https://github.com/TonyStarkBotz/DEADPOOL/blob/main/LICENSE)

[![Sparkline](https://stars.medv.io/TonyStarkBotz/DEADPOOL.svg)](https://stars.medv.io/TonyStarkBotz/DEADPOOL)

<details>
<summary><b>Features</b></summary>

- [x] Auto Filter
- [x] Manual Filter
- [x] IMDB
- [x] Admin Commands
- [x] Broadcast
- [x] Index
- [x] IMDB Search
- [x] Inline Search
- [x] Random Pics
- [x] Ids And User Info
- [x] Stats, Users, Chats, Ban, Unban, Leave, Disable, Channel
- [x] Spelling Check Feature
- [x] Custom File Caption
- [x] Group Broadcast 
- [x] AutoFilter Auto Delete
- [x] Junk Group & Users Clearing On Database
- [x] Global Filter
- [x] Url Shortner In Autofilter
- [x] Custom Button Lock
- [x] Image Editor & Background Remover
- [x] Telegraph, Pin, Json, Password Generator
- [x] Ban, Mute, Unmute, Etc... Group Manager
- [x] Custom Welcome Message
- [x] Advanced Admin Panel
- [x] Photo Changing In All Buttons
- [x] Custom Start Message
- [x] Custom Button Alter Message
- [x] Advanced Status (Disk, Cpu, Ram, Uptime..) In Image Type
</details>

<details>
<summary><b>Variables</b></summary>
  
### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URL`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/1G1XwEOnxxo)
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
* `SUPPORT_CHAT` : Username of a Support Group / ADMIN. ( Should be username without @ and not ID
  
### Optional Variables
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used seperated by space )
* `USE_CAPTION_FILTER` : Whether bot should use captions to improve search results. (True False)
* `CUSTOM_FILE_CAPTION` : A custom file caption for your files. formatable with , file_name, file_caption, file_size, Read Readme.md for better understanding
* `CACHE_TIME` : The maximum amount of time in seconds that the result of the inline query may be cached on the server
* `IMDB` : Imdb, the view of information when making True/False
* `SINGLE_BUTTON` : choose b/w single or double buttons 
* `P_TTI_SHOW_OFF` : Customize Result Buttons to Callback or Url by (True = url / False = callback)
### Url Shortner Variable
* `SHORT_URL` : Url Of Shortner Site You Use
* `SHORT_API` : Api Key Of Shortner Which You Use
</details>

<details>
<summary><b>Deploy to Heroku</b></summary>

<a href="https://youtu.be/uv0WHxwHwfo"><img src="https://img.shields.io/badge/watch%20Heroku%20Tutorial-red.svg?logo=Youtube"></a>                

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/TonyStarkBotz/DEADPOOL)
</details>

<details>
<summary><b>Deploy to Koyeb</b></summary>

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/TonyStarkBotz/DEADPOOL&env[WEBHOOK]=True&env[BOT_TOKEN]&env[API_ID]&env[API_HASH]&env[CHANNELS]&env[ADMINS]&env[PICS]&env[LOG_CHANNEL]&env[AUTH_CHANNEL]&env[MAX_RIST_BTNS]=10&env[CUSTOM_FILE_CAPTION]&env[DATABASE_URL]&env[DATABASE_NAME]=MknBotz&env[COLLECTION_NAME]=Telegram_files&env[SUPPORT_CHAT]&env[IMDB]=True&env[PM_IMDB]=True&env[IMDB_TEMPLATE]&env[IMDB_DELET_TIME]=900&env[SINGLE_BUTTON]=True&env[PMFILTER]=True&env[G_FILTER]=True&env[BUTTON_LOCK]=True&env[P_TTI_SHOW_OFF]=True&run_command=python%20bot.py&branch=main&name=mr-rofessor)              
</details>

<details>
<summary><b>Basic Commands</b></summary>

```
start - 𝑐ℎ𝑒𝑐𝑘 𝑏𝑜𝑡 𝑎𝑙𝑖𝑣𝑒
settings - 𝑔𝑒𝑡 𝑠𝑒𝑡𝑡𝑖𝑛𝑔𝑠
logs - 𝑡𝑜 𝑔𝑒𝑡 𝑡ℎ𝑒 𝑟𝑒𝑠𝑐𝑒𝑛𝑡 𝑒𝑟𝑟𝑜𝑟𝑠
stats - 𝑡𝑜 𝑔𝑒𝑡 𝑠𝑡𝑎𝑡𝑢𝑠 𝑜𝑓 𝑓𝑖𝑙𝑒𝑠 𝑖𝑛 𝑑𝑏
filter - 𝑎𝑑𝑑 𝑚𝑎𝑛𝑢𝑎𝑙 𝑓𝑖𝑙𝑡𝑒𝑟𝑠
filters - 𝑣𝑖𝑒𝑤 𝑓𝑖𝑙𝑡𝑒𝑟𝑠
connect - 𝑐𝑜𝑛𝑛𝑒𝑐𝑡 𝑡𝑜 𝑃𝑀
disconnect - 𝑑𝑖𝑠𝑐𝑜𝑛𝑛𝑒𝑐𝑡 𝑓𝑟𝑜𝑚 𝑃𝑀
connections - 𝑐ℎ𝑒𝑐𝑘 𝑎𝑙𝑙 𝑐𝑜𝑛𝑛𝑒𝑐𝑡𝑖𝑜𝑛𝑠
del - 𝑑𝑒𝑙𝑒𝑡𝑒 𝑎 𝑓𝑖𝑙𝑡𝑒𝑟
delall - 𝑑𝑒𝑙𝑒𝑡𝑒 𝑎𝑙𝑙 𝑓𝑖𝑙𝑡𝑒𝑟𝑠
deleteall - 𝑑𝑒𝑙𝑒𝑡𝑒 𝑎𝑙𝑙 𝑖𝑛𝑑𝑒𝑥 (𝑎𝑢𝑡𝑜𝑓𝑖𝑙𝑡𝑒𝑟)
delete - 𝑑𝑒𝑙𝑒𝑡𝑒 𝑎 𝑠𝑝𝑒𝑐𝑖𝑓𝑖𝑐 𝑓𝑖𝑙𝑒 𝑓𝑟𝑜𝑚 𝑖𝑛𝑑𝑒𝑥
info - 𝑔𝑒𝑡 𝑢𝑠𝑒𝑟 𝑖𝑛𝑓𝑜
id - 𝑔𝑒𝑡 𝑡𝑔 𝑖𝑑𝑠
imdb - 𝑓𝑒𝑡𝑐ℎ 𝑖𝑛𝑓𝑜 𝑓𝑟𝑜𝑚 𝑖𝑚𝑑𝑏
users - 𝑡𝑜 𝑔𝑒𝑡 𝑙𝑖𝑠𝑡 𝑜𝑓 𝑚𝑦 𝑢𝑠𝑒𝑟𝑠 𝑎𝑛𝑑 𝑖𝑑𝑠
chats - 𝑡𝑜 𝑔𝑒𝑡 𝑙𝑖𝑠𝑡 𝑜𝑓 𝑡ℎ𝑒 𝑚𝑦 𝑐ℎ𝑎𝑡𝑠 𝑎𝑛𝑑 𝑖𝑑𝑠
leave - 𝑡𝑜 𝑙𝑒𝑎𝑣𝑒 𝑓𝑟𝑜𝑚 𝑎 𝑐ℎ𝑎𝑡
disable - 𝑑𝑜 𝑑𝑖𝑠𝑎𝑏𝑙𝑒 𝑎 𝑐ℎ𝑎𝑡
enable - 𝑟𝑒-𝑒𝑛𝑎𝑏𝑙𝑒 𝑐ℎ𝑎𝑡
ban_user - 𝑡𝑜 𝑏𝑎𝑛 𝑎 𝑢𝑠𝑒𝑟
unban_user - 𝑡𝑜 𝑢𝑛𝑏𝑎𝑛 𝑎 𝑢𝑠𝑒𝑟
channel - 𝑡𝑜 𝑔𝑒𝑡 𝑙𝑖𝑠𝑡 𝑜𝑓 𝑡𝑜𝑡𝑎𝑙 𝑐𝑜𝑛𝑛𝑒𝑐𝑡𝑒𝑑 𝑐ℎ𝑎𝑛𝑛𝑒𝑙𝑠
broadcast - 𝑡𝑜 𝑏𝑟𝑜𝑎𝑑𝑐𝑎𝑠𝑡 𝑎 𝑚𝑒𝑠𝑠𝑎𝑔𝑒 𝑡𝑜 𝑎𝑙𝑙 𝐷𝑒𝑎𝑑𝑝𝑜𝑜𝑙 𝑢𝑠𝑒𝑟𝑠
```

</details>

## TELAGRAM SUPPORT 

* [![TONY STARK BOTZ](https://img.shields.io/static/v1?label=TONYSTARK&message=BOTZ&color=critical)](https://t.me/TonyStark_Botz)

## Credit 💞

* [![TEAM EVA-MARIA](https://img.shields.io/static/v1?label=TEAM&message=EVA-MARIA&color=yellow)](https://t.me/TeamEvamaria)

* [![BASE REPO](https://img.shields.io/static/v1?label=BASE&message=REPO&color=green)](https://t.me/TeamEvamaria)


## Disclaimer
[![GNU Affero General Public License 2.0](https://www.gnu.org/graphics/agplv3-155x51.png)](https://www.gnu.org/licenses/agpl-3.0.en.html#header)    
Licensed under [GNU AGPL 2.0.](https://github.com/TonyStarkBotz/DEADPOOL/blob/main/LICENSE)
Selling The Codes To Other People For Money Is *Strictly Prohibited*.

