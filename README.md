# PyAutoClicker: _A autoclicker made in Python with pyautogui_

## How to install PyAutoClicker?
- Install **Python**:
  - Install **Python** for Windows:
    - Go to [Python Software Foundation site](python.org)
    - Hover your mouse in "Downloads"
    - Click "Windows"
    - Select the desired Python version
    - Alternately, you can click [here](https://www.python.org/ftp/python/3.9.0/python-3.9.0-amd64.exe) to download Python 3.9 x64 for Windows
    - Go to "Downloads" then run the installer
    > ***Note:***
    > Make sure to click "Add to PATH" to easy use in command prompt
  - Install **Python** for Linux:
    - Open the terminal
    - Run these commands:

    ```
    sudo add-apt-repository ppa:deadsnakes/ppa
    sudo apt update
    ```
    - Now, install **Python** with ```sudo apt install python3.9 -y```
    > ***Tip:***
    > To make sure **Python** was successfully installed on your system, run ```python3.9 --version```
  - Install **Python** for macOS:
    - Go to [Python Software Foundation site](python.org)
    - Hover your mouse in "Downloads"
    - Click "macOS"
    - Select the desired Python version
    - Alternately, you can click [here]([https://www.python.org/ftp/python/3.9.0/python-3.9.0-amd64.exe](https://www.python.org/ftp/python/3.9.0/python-3.9.0-macosx10.9.pkg)) to download Python 3.9 x64 for macOS (specifically macOS 10.9)
    - Go to "Downloads" then run the installer
- Install lastest pip version for Python
  - Open a terminal
  - Type ```python3.9 -m install --upgrade pip``` and wait
- Install *pyautogui*
  - Type ```python3.9 -m install pyautogui```
- Download ***PyAutoClicker***
  - Go to [this repository releases](https://github.com/Coxinha2K/PyAutoClicker/releases)
  - Go to latest version available
  - Download ```pyautoclicker.py```
  > ***Tip:***
  > Add ```pyautoclicker.py``` to PYTHONPATH so you can run ```python3.9 -m pyautoclicker``` to open the autoclicker
- Run ***PyAutoClicker***
  - Open a terminal
    - If you did the last tip, type ```python3.9 -m pyautoclicker``` to run **PyAutoClicker**
    - If you didn't, go to the folder to where you let ```pyautoclicker.py``` and run it with ```python3.9 -m pyautoclicker```

## How does PyAutoClicker works?
- When you fire up **PyAutoClicker**, it asks you:
  - The level, that's how many threads **PyAutoClicker** will spawn
  - The delay (can be something like 0.1 too), to add a pause between clicks
  - Max clicks, that's how many clicks **PyAutoClicker** can do before killing himself. To disable this, you set it to a negative number
- When the 5-second timer ends, it will spawn T threads (e.g.: level 10 = 10 threads or 10 T)
  - Each thread has a while True loop that keeps clicking where the cursor is and will increase the click amount
  - In principal thread (the main), it will keep calculating CPS and printing details on screen.
 
## Is it recommended?
Well, i personally built this to use it in [Stimulation Clicker](https://neal.fun/stimulation-clicker) by Neal (you can check it out, thanks Neal!)
I **don't encorage** people to use cheats on games, like Minecraft, for example, but if you want to use it, feel free!

## Examples
When i was testing, i got those results:

- Level 1: 8 CPS
- Level 5: 40-45 CPS
- Level 10: 75-85 CPS
- Level 15: 120-130 CPS
*(i did not test level 20+ because they render my PC so slow)*
