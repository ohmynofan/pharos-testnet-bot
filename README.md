## PHAROS TESTNET BOT

### New Pharos Incentive Testnet

Pharos Testnet
Funding : 8M
Reward : Potential
Network : Pharos Testnet

Link:
[https://testnet.pharosnetwork.xyz/experience]

- Connect Wallet (New / BURNER)
- Complete Social Task
- Daily Check In
- Do Onchain Task
- Done!

## PREREQUISITES

- Git
- Node JS

## BOT FEATURE

- Multi Account
- Support PK and Seed
- Proxy Support
- Daily Transfer (SELF / FRIENDS)
- Daily Chek In
- Daily Swap (Zenithswap & Faroswap)
- Daily Add Liquidity (Zenithswap & Faroswap)

## SETUP & CONFIGURE BOT

### LINUX

1. Clone project repository
   ```
   git clone https://github.com/ohmynofan/pharos-testnet-bot.git && cd pharos-testnet-bot
   ```
2. Install dependencies
   ```
   npm install && npm run setup
   ```
3. Configure your accounts
   ```
   nano accounts/accounts.js
   ```
4. Configure your bot configuration and proxy
   ```
   nano config/config.js
   nano config/proxy_list.js
   ```
5. To start the app, run
   ```
   npm run start
   ```

### WINDOWS

1. Open your `Command Prompt` or `Power Shell`.
2. Clone project repository
   ```
   git clone https://github.com/ohmynofan/pharos-testnet-bot.git
   ```
   and cd to project dir
   ```
   cd pharos-testnet-bot
   ```
3. Install dependencies
   ```
   npm install && npm run setup
   ```
4. Navigate to `pharos-testnet-bot-js` directory.
5. Navigate to `accounts` and configure `accounts.js`.
6. Back to `pharos-testnet-bot-js` directory.
7. Navigate to `config` and configure `config.js` and `proxy_list.js` if you use proxy.
8. To start the app open your `Command Prompt` or `Power Shell` again and run
   ```
   npm run start
   ```

## UPDATE BOT

To update bot follow this step :

1. Run
   ```
   git pull
   ```
   or
   ```
   git pull --rebase
   ```
   if error run
   ```
   git stash && git pull
   ```
2. Run
   ```
   npm update
   ```
3. Start the bot

## NOTE

DWYOR & Always use a new wallet when running the bot, I am not responsible for any loss of assets.

If you got 429 Error, You need to use proxy with rotating feature (Residential) so the IP will change every specific minutes, otherwise you will got 429 - To Many Request Error

- [proxyscrappe](https://proxyscrape.com/)
- [dataimpulse](https://dataimpulse.com/)

## CONTRIBUTE

Feel free to fork and contribute adding more feature thanks. To get original unencrypted code just join my channel, original code (index.js and src folder) are Obfuscated during build

## WHY THE CODE ENCRYPTED

The code encrypted to avoid someone who steal or remake and use tho bot for commercial use like selling bot service, etc. Even if it encrypted it actualy easy to decrypt, i just want to give them some effort to steal it.

I hope everyone who steal or remake this bot give a credits for me, how ? just fork or include my github profile url on your bot. Thanks

The unencrypted code will be pushed to git after the event is over.

---
