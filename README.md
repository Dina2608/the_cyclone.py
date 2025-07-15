# the_cyclone.py
# My first repository in my life 
Height = int(input('Height:  '))
Credits = int(input('Credits:  '))
if Height > 137 and Credits >= 10:
  print('Enjoy the ride!')
elif Height <= 137 and Credits < 10:
  print('Sorry not your day')
elif Height <= 137:
  print("You are not tall enough to ride.")
elif  Credits < 10:
  print("You don't have enough credits.")
