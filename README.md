import math
import os
import random
import re
import sys
n=int(input('enter a number'))
if n%2==1:
    print('Weird')
elif n%2==0:
    if n in range(2,6):
        print('Not weird')
    if n in range(6,21):
        print('Weird')
    if n>20:
        print('Not weird')

