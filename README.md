# number_guessing_game_v1
the number guessing game version one , simple working searches number between 1 to 10 and gives one chance to guess, used the random module 

import random                                     # importing the ramdom module

num=random.randint(1,10)                          # generating a random number

a=num                                             # assinging a variable to the number

ask=int(input('entre a number:'))                 # user input

if ask==a:                                        # checking the match using if conditon
    print('wow u guessed it')                     # if correct
else:                                             # else condition
    print('opps!, wrong guess, the number was',a) #if not correct
