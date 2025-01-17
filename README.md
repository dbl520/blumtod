
# BlumTod

AUTO CLAIM FOR BLUM / @blum

[Klik Disini README Dalam Bahasa Indonesia](README_ID.md)

# Table of Contents
- [BlumTod](#blumtod)
- [Table of Contents](#table-of-contents)
- [Warning](#warning)
- [Support My Work!](#support-my-work)
- [Available Features](#available-features)
- [Registration](#registration)
- [How to Use](#how-to-use)
  - [Command Line Options / Arguments](#command-line-options--arguments)
  - [About Proxies](#about-proxies)
  - [Windows](#windows)
  - [Linux](#linux)
  - [Termux](#termux)
- [How to Get the Query](#how-to-get-the-query)
- [JavaScript Code to Get Data in Telegram Desktop App](#javascript-code-to-get-data-in-telegram-desktop-app)
- [Running 24/7](#running-247)
- [Discussion](#discussion)
- [Questions and Answers](#questions-and-answers)
- [Thank You](#thank-you)

# Warning

All risks are borne by the user

# Support My Work!

If you like my work, you can support me through the following links:

- [Indonesia] https://s.id/nusanqr (QRIS)
- [Indonesia] https://trakteer.id/fawwazthoerif/tip
- [Global] https://sociabuzz.com/fawwazthoerif/tribe
- If you want to send support in another form, you can contact me via Telegram.

# Available Features

- [x] Automatic Claim Every 8 Hours
- [x] Automatic Daily Check-In (Login)
- [x] Automatic Claim of Referral Results
- [x] Proxy Support
- [x] Automatic Task Completion
- [x] Automatic Game Play after Claiming
- [x] Multiprocessing Support

# Registration

Click the following link to register: [https://t.me/BlumCryptoBot/app?startapp=ref_aPYIYj1oKc](https://t.me/BlumCryptoBot/app?startapp=ref_aPYIYj1oKc)

# How to Use

## Command Line Options / Arguments

This script/program supports several argument parameters that can be used. Here's an explanation of the arguments:

`--data` / `-D`: Used when you have a different filename for storing account data. By default, the filename used by this script/program to store account data is `data.txt`. For example, if you have a file named `query.txt` as the file storing account data, just run `bot.py` with the `--data` / `-D` argument. Example: `python bot.py --data query.txt`

`--proxy` / `-P`: Used when you have a different filename for storing the proxy list. The filename used by this script/program to store the proxy list is `proxies.txt`. For example, if you have a file named `prox.txt` as the file storing the proxy list, you just need to add the `--proxy` / `-P` argument parameter to use your proxy file. Example: `python bot.py --proxy prox.txt`

`--worker` / `-W`: This argument is used to customize the number of threads/workers used when the bot script is running. By default, this script/software uses (total CPU cores / 2) as the number of workers. For example, if your CPU has 6 cores, the number of workers used is 3. You can customize the number of workers using this argument. For example, if you want to set the number of workers to 100, run `bot.py` with this argument: `python bot.py --worker 100`. And if you don't like using workers/threads/multiprocessing, you can customize the worker to 1, for example: `python bot.py --worker 1`.

## About Proxies

Register on the following website to get free proxies: [Here](https://www.webshare.io/?referral_code=dwj0m9cdi4mp)

Website with the cheapest proxy price $1/GB [Here](https://dataimpulse.com/?aff=48082)

You can add proxy lists in the `proxies.txt` file, and the proxy format is as follows:

If there is authentication:

Format : 

```
protocol://user:password@hostname:port
```

Example:

```
http://admin:admin@69.69.69.69:6969
```

If there is no authentication:

Format:

```
protocol://hostname:port
```

Example:

```
http://69.69.69.69:6969
```

Please pay close attention to whether the proxy you are using requires authentication or not, as many people DM me asking about how to use proxies.

## Windows 

1. Make sure your computer has Python and Git installed.

    Recommendation: Use Python version 3.8+ (3.8 or newer)
   
   Python site: [https://python.org](https://python.org)
   
   Git site: [https://git-scm.com/](https://git-scm.com/)

2. Clone this repository.
   ```shell
   git clone https://github.com/akasakaid/blumtod.git
   ```

3. Enter the BlumTod folder
   ```
   cd blumtod
   ```

4. Install the required modules/libraries.
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit the `data.txt` file, enter your query data into the `data.txt` file. You can get your query by following [How to Get the Query](#how-to-get-the-query). One line for 1 account, if you want to add a 2nd account, fill it in on a new line.

6. Run the program/script.
   ```
   python bot.py
   ```

## Linux 

1. Make sure your computer has Python and Git installed.

    Recommendation: Use Python version 3.8+ (3.8 or newer)
   
   Python
   ```shell
   sudo apt install python3 python3-pip
   ```
   Git
   ```shell
   sudo apt install git
   ```

2. Clone this repository.
   ```shell
   git clone https://github.com/akasakaid/blumtod.git
   ```

3. Enter the BlumTod folder
   ```
   cd blumtod
   ```

4. Install the required modules/libraries.
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit the `data.txt` file, enter your query data into the `data.txt` file. You can get your query by following [How to Get the Query](#how-to-get-the-query). One line for 1 account, if you want to add a 2nd account, fill it in on a new line.

6. Run the program/script.
   ```
   python bot.py
   ```

## Termux

1. Make sure your device has Python and Git installed.

    Recommendation: Use Python version 3.8+ (3.8 or newer)
   
   Python
   ```shell
   pkg install python3
   ```
   Git
   ```shell
   pkg install git
   ```

2. Clone this repository.
   ```shell
   git clone https://github.com/akasakaid/blumtod.git
   ```

3. Enter the BlumTod folder
   ```
   cd blumtod
   ```

4. Install the required modules/libraries.
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit the `data.txt` file, enter your query data into the `data.txt` file. You can get your query by following [How to Get the Query](#how-to-get-the-query). One line for 1 account, if you want to add a 2nd account, fill it in on a new line.

6. Run the program/script.
   ```
   python bot.py
   ```

# How to Get the Query

The required data is the same as [pixelversebot](https://github.com/akasakaid/pixelversebot), so you can watch the same tutorial video!

Here: [https://youtu.be/KTZW9A75guI](https://youtu.be/KTZW9A75guI)

# JavaScript Code to Get Data in Telegram Desktop App

```javascript
copy(Telegram.WebApp.initData)
```

# Running 24/7

You can run the bot script 24/7 using a VPS/RDP. You can use the `screen` application if using a Linux operating system to run the bot script in the background.

# Discussion

If you have questions or anything else, you can ask here: [@sdsproject_chat](https://t.me/sdsproject_chat)

# Questions and Answers

Q: Is it mandatory to use a proxy with this bot script/program?

A: No, this bot script/program does not require a proxy.

Q: How do I use a proxy?

A: The simple explanation is that you just need to fill the `proxies.txt` file with the proxy format I explained above.

# Thank You