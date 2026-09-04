# number_guessing_game_v1
the number guessing game version one , simple working searches number between 1 to 10 and gives one chance to guess, used the random module

added a too high and too low case , allowing user multiple attempts unitl user gets it correct

import random                                     # importing the ramdom module

num=random.randint(1,10)                          # generating a random number

a=num                                             # assinging a variable to the number

ask=int(input('entre a number:'))                 # user input
i=1                                               # can use while true form also
while  i==1:                                      #while true form will also work
    if ask==a:                                    # checking the match using if conditon
        print('wow u guessed it')
        i=0                                        # here can use break key word also
    elif ask>a:
        print('number too high')
        ask=int(input('entre a number:'))
    elif ask<a:
        print('number too low')
        ask=int(input('entre a number:'))

print('------------------------------------------------')


print('------------------------------------------------')

