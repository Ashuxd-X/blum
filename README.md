<<<<<<< HEAD
## Table of Contents
- [Recommendation before use](#recommendation-before-use)
- [Features](#features)
- [Settings](#settings)
- [Quick Start](#quick-start)
- [Prerequisites](#prerequisites)
- [Obtaining API Keys](#obtaining-api-keys)
- [Installation](#installation)
- [Contacts](#contacts)

> [!WARNING]
> ⚠️ I do my best to avoid detection of bots, but using bots is forbidden in all airdrops. i cannot guarantee that you will not be detected as a bot. Use at your own risk. I am not responsible for any consequences of using this software.


# 🔥🔥 Use PYTHON 3.10 - 3.11 🔥🔥

## Features  
| Feature                                                     | Supported  |
|---------------------------------------------------------------|:----------------:|
| Multithreading                                                |        ✅        |
| Proxy binding to session                                      |        ✅        |
| Auto ref                                                      |        ✅        |
| Auto tasks                                                    |        ✅        |
| Auto play game                                                |        ✅        |
| Auto start farming                                            |        ✅        |
| Support for pyrogram .session / Query                         |        ✅        |

## [Settings](https://github.com/asish1346/blum/blob/main/.env-example)
| Settings | Description |
|----------------------------|:-------------------------------------------------------------------------------------------------------------:|
| **API_ID / API_HASH**      | Platform data from which to run the Telegram session (default - android)                                      |       
| **REF_LINK**               | Put your ref link here (default: "")                                                                 |
| **AUTO_TASK**              | Auto do tasks (default: True)                                                                                 |
| **AUTO_GAME**              | Auto play game (default: True)                                                                                 |
| **MAX_POINTS**              | Maximum points to get each game (default: 220)                                                                                 |
|**MAX_POINTS**              | Minimum points to get each game (default: 180)                                                                                 |
| **DELAY_EACH_ACCOUNT**               | Random delay bewteen accounts (default: [20, 30] seconds)                                                                        |
| **ADVANCED_ANTI_DETECTION**  |  Add more protection for your account (default: True)                                     |
| **USE_PROXY_FROM_FILE**    | Whether to use a proxy from the bot/config/proxies.txt file (True / False)                                    |



## Quick Start

To install libraries and run bot - open run.bat on Windows

## Prerequisites
Before you begin, make sure you have the following installed:
- [Python](https://www.python.org/downloads/) **IMPORTANT**: Make sure to use **3.10 - 3.11**.
- [Nodejs](https://nodejs.org/en) Make sure to use nodejs 19+

## Obtaining API Keys
1. Go to my.telegram.org and log in using your phone number.
2. Select "API development tools" and fill out the form to register a new application.
3. Record the API_ID and API_HASH provided after registering your application in the .env file.


## Installation
You can download the [**repository**](https://github.com/asish1346/Blum) by cloning it to your system and installing the necessary dependencies:
```shell
git clone https://github.com/asish1346/Blum.git
cd Blum
```

Then you can do automatic installation by typing:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux manual installation
```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Here you must specify your API_ID and API_HASH, the rest is taken by default
python3 main.py
```

You can also use arguments for quick start, for example:
```shell
~/Blum >>> python3 main.py --action (1/2)
# Or
~/Blum >>> python3 main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```

# Windows manual installation
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Here you must specify your API_ID and API_HASH, the rest is taken by default
python main.py
```
You can also use arguments for quick start, for example:
```shell
~/Blum >>> python3 main.py --action (1/2)
# Or
~/Blum >>> python3 main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```

# Termux manual installation
```
> pkg update && pkg upgrade -y
> pkg install python nodejs rust git -y
> git clone https://github.com/asish1346/Blum.git
> cd Blum
> pip install -r requirements.txt
> python main.py
```

You can also use arguments for quick start, for example:
```termux
~/Blum > python main.py --action (1/2)
# Or
~/Blum > python main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session 
```
### Contacts

For support or questions, you can contact me [![Static Badge](https://img.shields.io/badge/Telegram-Channel-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/Lootersera_th)
=======

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
>>>>>>> 63d743f1e5f578bcbea143ad63004ec7f4c91ca2
