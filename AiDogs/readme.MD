📞 Contact

> [Termux guides if you run on mobile](https://github.com/MeoMunDep/Guides-for-using-my-script-on-termux.)

> If you encounter any issues or have questions, feel free to reach out:

- Contact: [Link](t.me/MeoMunDep)
- Group: [Link](t.me/KeoAirDropFreeNe)
- Channel: [Link](t.me/KeoAirDropFreeNee)

> Help me with your referral [Link](http://t.me/Aidogs_bot?start=ef6b2216)

## 🚀 Getting Started

To get started with the bot, follow these steps:

0. **Dowload NodeJS to run the bot**

-> [Link](https://t.me/KeoAirDropFreeNe/257/1462)

> Remember to download Nodejs version: **20.9.0** and NPM version: **10.9.0**

1. **Install Dependencies and Modules:**

   ```
   npm i user-agents axios colors p-limit https-proxy-agent socks-proxy-agent crypto-js ws uuid xlsx
   ```

2. **Prepare Configuration Files:**

   > You'll need to set up a few configuration files for the bot to work properly.

## 📁 Configuration Files

### 1. `configs.json` 📜 - Adjust configuration

```json
{
  "timeZone": "en-US",
  "rotateProxy": false,
  "skipInvalidProxy": false,
  "proxyRotationInterval": 2,
  "delayEachAccount": [5, 8],
  "timeToRestartAllAccounts": 300,
  "howManyAccountsRunInOneTime": 100,
  "doTasks": true,
  "playGames": true,
  "referralCode": "" // Do not change it if you want to support me ^^
}
```

### 2. `datas.txt` 🗂️ - Get it from here >>> [Link](https://t.me/KeoAirDropFreeNe/257/6879)

```txt
query_id.../user...
query_id.../user...
query_id.../user...
```

### 3. `wallets.txt` 💼 - Cannot update yet.

```txt - wallet address
abc...xyz
abc...xyz
abc...xyz
```

### 4. `proxies.txt` 🌐 - Proxy is an option. If you have one, fill it in; otherwise, leave it blank.

```txt
http://user:password@host:port
https://user:password@host:port
socks4://user:password@host:port
socks5://user:password@host:port
```

### 5. `sui_wallets.xlsx` 💼 - Do not touch this file or script can not working. | NO USE THIS ANYMORE, BECAUSE THE GAME JUST CHANGE TO SOLANA.

```txt
UID|Address|mnemonic|scretKey
UID|Address|mnemonic|scretKey
UID|Address|mnemonic|scretKey
```

### 6. `sol_wallets.txt` 💼 - Fill your Solana wallets here.
```txt
xxx...
xxx...
xxx...
```

💡 Usage:

> You need to `cd` to the file after extract it.
> To run the bot, use the following command: `cd aidogs-main/aidogs; node bot`

🎇Enjoy!
