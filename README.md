## BUMS BOT

---

## BOT FEATURE

- Auto tap
- Auto daily
- Auto task
- Auto upgrade

---

## REQUIREMENTS

- Node JS
- Git


---

## INSTALL MODULES

1. Clone Project Repository
   ```bash
   git clone https://github.com/D4rkCipherX/Bums.git && cd Bums
   ```

2. Install Dependencies
   ```bash
   npm install
   ```
3. nano data.txt

For those using multiple accounts, it's recommended to use a proxy (if using only one account, there's no need to create the proxy.txt file).

---

## PROXY FORMAT

```bash
http://username:passwoord@hostname:port
socks5://username:password@hostname:port
```

---

# GET DATA

In the `data.txt` file, you need to have the following format:

```bash
query_id=xxx
user=xxxx

# CONFIGURATION

This configuration option of `config.json`

```js
{
    "maxUpgradeCost": 1000000
}
```

---

# RUN BOT

1. No Proxy
   ```bash
   node main.js
   ```
2. Proxy
   ```bash
   node bums-proxy.js
   ```
BUY ME A COFFEE : (Tron/TRX) TGHDx9dBsNSZSadiu4iJ5ZFW4a4KtRTEjq