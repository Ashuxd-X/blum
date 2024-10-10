
# BlumAuto Installation Guide

Follow this installation guide to set up BlumAuto.

> **Warning**  
> "Users assume all responsibility and risk associated with the use of this bot/program script."

## Features

- ✅ Auto Claim
- ✅ Daily Auto Claim
- ✅ Proxy Support (see [Proxy Setup](#proxy-setup))
- ✅ Multi-Account Support
- ✅ Auto Claim Bonus Referral
- ✅ Auto Task Completion (details in [Config.json Overview](#configjson-overview))
- ✅ Automated Gameplay (random user input, see [Config.json Overview](#configjson-overview))

## Registration

Click the following link to register: [Register Here](https://t.me/blum/app?startapp=ref_fyH24gm7nP)

## How to Use

### Bot.py Parameter Features

Here are some parameters to enable features:

| Parameter | Description                                      |
|-----------|--------------------------------------------------|
| `--data`  | Set custom file data input (default: `data.txt`) |

### About Config.json

**Config.json Description:**

| Key                | Description                                                                                                                                     |
|--------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| `interval`         | Value type is integer/real number. <br> Specifies the delay between account actions.                                                          |
| `auto_complete_task`| Value type is bool (true/false). Set to true to activate auto-completion of tasks.                                                           |
| `auto_play_game`   | Value type is bool (true/false). Set to true to activate auto gameplay.                                                                        |
| `game_point`       | Value type is integer/real number. <br> Low: Minimum points earned when playing the game. <br> High: Maximum points earned when playing the game. |

### About Proxy

To get a free proxy, register at: [Webshare](https://www.webshare.io/)

You can add your proxy list in `proxies.txt`. The proxy format is as follows:

**Format:**

```
http://host:port
http://user:pass@host:port
```

**Example:**

```
http://127.0.0.1:6969
http://user:pass@127.0.0.1:6969
socks5://127.0.0.1:6969
socks5://user:pass@127.0.0.1:6969
```

## Installation Steps

### Windows

1. Ensure that Python and Git are installed on your computer.  
   **Suggestion:** Use Python version 3.8 or above.  
   - [Python Download](https://python.org)  
   - [Git Download](https://git-scm.com/)

2. Clone the repository:  
   ```bash
   git clone https://github.com/asish1346/blum.git
   ```

3. Navigate to the `blum` directory:  
   ```bash
   cd blum
   ```

4. Install the required libraries:  
   ```bash
   python -m pip install -r requirements.txt
   ```

5. Edit `data.txt` to input your data token. Find your token in [How to Find Account Token](#how-to-find-account-token). Each line corresponds to one account token. To add a second account, add it on a new line.

6. Execute the main program:  
   ```bash
   python bot.py
   ```

### Linux

1. Ensure that Python and Git are installed on your computer.  
   **Suggestion:** Use Python version 3.8 or above.  
   ```bash
   sudo apt install python3 python3-pip
   sudo apt install git
   ```

2. Clone the repository:  
   ```bash
   git clone git clone https://github.com/asish1346/blum.git
   ```

3. Navigate to the `blum` directory:  
   ```bash
   cd blum
   ```

4. Install the required libraries:  
   ```bash
   python3 -m pip install -r requirements.txt
   ```

5. Edit `data.txt` to input your data token. Each line corresponds to one account token. To add a second account, add it on a new line.

6. Execute the main program:  
   ```bash
   python bot.py
   ```

### Termux

1. Ensure that Python and Git are installed in Termux.  
   ```bash
   pkg install python
   pkg install git
   ```

2. Clone the repository:  
   ```bash
   git clone https://github.com/asish1346/blum.git
   ```

3. Navigate to the `blum` directory:  
   ```bash
   cd blum
   ```

4. Install the required libraries:  
   ```bash
   python -m pip install -r requirements.txt
   ```

5. Edit `data.txt` to input your data token. Each line corresponds to one account token. To add a second account, add it on a new line.

6. Execute the main program:  
   ```bash
   python bot.py
   ```

### Docker

1. Ensure that Docker is installed on your system.

2. Edit `data.txt` to input your data token. Each line corresponds to one account token. To add a second account, add it on a new line.

3. Run the Docker container:  
   ```bash
   docker run -it \
     -v "./data.txt:/app/blum/data.txt" \
     ghcr.io/asish1346/blum:latest
   ```

   Or use Docker Compose:  
   ```bash
   docker compose up
   ```

## Javascript Command to Get Telegram Data for Desktop

```javascript
copy(Telegram.WebApp.initData)
```

## Running Continuously

To run the script continuously, consider using a VPS or RDP. Use the `screen` application on a Linux VPS to keep the script running in the background.

## Discussion

For any questions or further assistance, please join: [Discussion Group](https://telegram.dog/lootersera_th)

## Q&A

**Q: Is it necessary to use a proxy with this bot/program script?**  
**A:** No, using a proxy is not required for this bot/program script.

**Q: How can I configure and use a proxy?**  
**A:** To use a proxy, simply fill out the `proxies.txt` file according to the provided format.
```
