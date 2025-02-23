-> Double click on `setup.bat` for windows or `setup.sh` for linux/mac if you want to run automatically, remember to fill all the necessary data.

1. **Install Dependencies and Modules:**

```
pkg install nodejs
``` 

```
   npm i user-agents axios colors p-limit https-proxy-agent socks-proxy-agent crypto-js ws uuid
   ```
## installation 
```
pkg install git
```

```
git clone https://github.com/blacksmith69-glitch/Blockmesh-v2.git
```
```
cd Blockmesh-v2
```
```
npm install axios
```
```
npm install colors
```
```
npm install ws
```
```
npm install crypto-js
```
```
npm install lodash
```
```
npm install uuid
```
```
npm install user-agents
```
```
npm install socks-proxy-agent
```
```
npm install https-proxy-agent
```
```
cd Blockmesh-v2 
```
### ***script run*** ###

```
node meomundep.js
```
### ***Before running script add this details*** ###
2. **Prepare Configuration Files:**

   > You'll need to set up a few configuration files for the bot to work properly.

## 📁 Configuration Files

### 1. `configs.json` 📜 - Adjust configuration
```
nano configs.json
```

```json
{
  "timeZone": "en-US",
  "rotateProxy": true,
  "skipInvalidProxy": false,
  "proxyRotationInterval": 2,
  "delayEachAccount": [5, 8],
  "timeToRestartAllAccounts": 300,
  "howManyAccountsRunInOneTime": 100
}
```

### 2. `emails.txt` 🗂️ - Your emails address.

```
nano emails.txt
```
```txt
xxx@gmail.com
xxx@gmail.com
xxx@gmail.com
```

### 2.1. `passwordss.txt` 🗂️ - Your passwords's emails.

```
nano passwordss.txt
```
```txt
xxx...
xxx...
xxx...
```

### 3. `wallets.txt` 💼 - Cannot update yet.

```txt - wallet address
abc...xyz
abc...xyz
abc...xyz
```

### 4. `proxies.txt` 🌐 - Proxy is an option. If you have one, fill it in; otherwise, leave it blank.

```
nano proxies.txt
```

```txt
http://user:password@host:port
https://user:password@host:port
socks4://user:password@host:port
socks5://user:password@host:port
```

💡 Usage:

> You need to `cd` to the file after extract it.
> To run the bot, use the following command: `cd blockmesh-main/blockmesh; node bot`

🎇Enjoy!
