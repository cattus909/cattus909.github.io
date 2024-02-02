number guessing game:

import random as r

random_number = r.randrange(1,100)


while (True):
  guess_number = int(input('Guess the number 1-100  '))

  if (guess_number == random_number): 
    print ("you won")
    exit()
  if (random_number > guess_number):
    print ("higher")
  if (random_number < guess_number):
    print ("lower")
