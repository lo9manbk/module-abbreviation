# ========== Standard Modules ==========

import math
# math: provides mathematical functions like square root, power, sin, etc.
print(math.sqrt(16))        # √16 = 4
print(math.pow(2, 3))       # 2^3 = 8
print(math.sin(math.pi/2)) # sin(π/2) = 1

import random
# random: used to generate random numbers or make random selections
print(random.randint(1, 10))         # random number between 1 and 10
print(random.choice(['a', 'b', 'c'])) # randomly pick one item

import datetime
# datetime: used for working with dates and times
now = datetime.datetime.now()
print(now)
print(now.strftime("%Y-%m-%d %H:%M:%S"))  # format date and time

import os
# os: used to interact with the operating system and file system
print(os.getcwd())     # get current working directory
print(os.listdir())    # list files in current directory

import sys
# sys: provides access to system-specific parameters and functions
print(sys.platform)     # platform info (e.g., 'win32', 'linux')

import time
# time: used for ti
