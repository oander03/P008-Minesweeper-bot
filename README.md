# Minesweeper bot
This script is made to do the google minesweeper using images. Made because I wanted to beat the world record using code.
Code is was made in the way that mimics how I play the game so it might not be the best way and not optimized.  

https://github.com/user-attachments/assets/f34a03a8-4937-4c36-a435-dfca0b20b9b3

## How it Works 🚀

- Takes screenshot of the board and maps it on a big 2D array
- Looks if theres any clear flags to place
- Looks if theres any squares with enough flags
- Looks more in depth at hints to find confirmed flags and free squares that passed the first test
- Waits a few seconds for the minesweeper animations and repeats
  
## Tech Stack 🛠️

100% Python <br/>
```bash
#packages:
import pyautogui
import pyautogui as pag
import random
import time
import numpy as np
import win32api, win32con
import mss
from pyclick import HumanClicker
```
## Notes

The reason for the resting between moves is because the animations of minesweeper get in the way of the screenshot. It can go faster but with less accuracy.  

# Contact 📬
Created by Owen Anderson on May ‎15, ‎2025
