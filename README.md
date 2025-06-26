# Helios Testnet BOT
Helios Testnet BOT

- Register Here : [Helios Testnet](https://testnet.helioschain.network/?code=ASTRAL-TITAN-689)
- Connect Discord Account

## Features

  - Auto Get Account Information
  - Auto Run With [Proxyscrape Free Proxy](https://proxyscrape.com/free-proxy-list) - `Choose 1`
  - Auto Run With Private Proxy - `Choose 2`
  - Auto Run Without Proxy - `Choose 3`
  - Auto Rotate Invalid Proxies - `y` or `n`
  - Auto Claim HLS Faucet - `Need 2captcha key`
  - Auto Bridge HLS to Sepolia
  - Auto Delegate HLS to Validator
  - Multi Accounts

### Note: Other features will be updated soon.

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.
- 2captcha key (Optional)

## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/airdropbomb/HeliosTestnet.git && cd HeliosTestnet
   ```

2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```

### Note: Check your web3, eth-account, and eth-utils library version first. If not same with version in requirements.txt, u must uninstall that library.
- **Check Library Version**
  ```bash
    pip show libary_name
  ```
- **Uninstall Library**
  ```bash
    pip uninstall libary_name
  ```
- **Install Library With Version**
  ```bash
    pip install libary_name==version
  ```

## Configuration

- **accounts.txt:** You will find the file `accounts.txt` inside the project directory. Make sure `accounts.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    your_private_key_1
    your_private_key_2
  ```

- **2captcha_key.txt:** You will find the file `2captcha_key.txt` inside the project directory. Make sure `2captcha_key.txt` contains data that matches the format expected by the script. Here are examples of file formats:

  ```bash
    your_2captcha_key
  ```

- **proxy.txt:** You will find the file `proxy.txt` inside the project directory. Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py #or python3 bot.py
```
