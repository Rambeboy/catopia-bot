# CATOPIA BOT

New Airdrops : Catopia

🪂 Register : [Catopia](https://t.me/catopia_game_bot)

🐱🌱Plant trees, upgrade pets, complete quests, invite friends and become the best.

## BOT FEATURE

- Auto Plant Seed
- Auto Buy Seed
- Auto Harvest
- Auto Claim Mission
- Auto Buy Chest
- Auto Buy Lands
- Auto Upgrade Pet 
- Auto Claim Gold
- Multi Account With Proxy Support

## Prerequisite

- Git
- Node JS
- TELEGRAM_APP_ID & TELEGRAM_APP_HASH Get it from [Here](https://my.telegram.org/auth?to=apps)
- Catopia Account , Create [Here](https://t.me/catopia_game_bot/), join and claim join reward, also don't forget to complete mandatory missions some completable mission.

## SETUP & CONFIGURE BOT

1. Clone project repository
   ```bash
   git clone https://github.com/Rambeboy/catopia-bot.git && cd catopia-bot
   ```
2. Install dependencies 
   ```bash
   npm install && npm i telegram@2.22.2
   ```
3. Setup your accounts
   ```bash
   npm run setup
   ```
4. Configure the bot config 
   ```bash
   cp -r config/config_tmp.js config/config.js && cp -r config/proxy_list_tmp.js config/proxy_list.js
   ```
5. To configure the app, run
   ```bash
   nano config/config.js
   ```
   And add your telegram app id and hash there.
6. To configure the Proxy, run
   ```bash
   nano config/proxy_list.js
   ```
   And add your proxy list there, it currently only support https proxy.
7. To start the app run
   ```bash
   npm run start
   ```

## UPDATE BOT

To update bot follow this step :
1. Run
   ```bash
   git pull
   ```
   or
   ```bash
   git pull --rebase
   ```
   If error run
   ```bash
   git stash && git pull
   ```
2. Run
   ```
   npm update
   ```
3. Start the bot

## SETUP SESSION

1. Run bot `npm run start`
2. Choose option `1` create session
3. Enter session name
4. Enter your phone number starting with countrycode ex : `+628xxxxxxxx`
5. After creating sessions, choose `3` start bot
6. If something wrong with your sessions, reset sessions first, to cancel running bot press `ctrl+c` twice, and start again from No 1.

## NOTE

This bot using telegram sessions. if you ever use one of my bot that use telegram sessions, you can just copy the sessions folder to this bot. Also for the telegram APP ID and Hash you can use it on another bot.

If you got error `Invalid ConstructorId` try to run this ```npm i telegram@2.22.2```.

## LICENSE

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
