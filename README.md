# Desert-Dash-
#Desert Dash
#Intro
name = input('What is your name? ')
print('Welcome to Desert Dash', name)
print('You have stolen a camel to make your way across the great Camel desert.')
print('The natives want their camel back and are chasing you down!')
print('Survive your desert dash and outrun the natives!!!!')

#Vitality/Distance Variables
import random
done = False
miles_traveled = 0
player_thirst = 0
camel_stamina = 0
natives_traveled = -20
canteen = 5
hunger = 0
natives_moving = random.randrange(0,10)
medium_speed = random.randrande(5,15)
full_speed = random.randrange(10,20)

while not done:
    print("A. Drink from water sack.")
    print("B. Go at a medium pace.")
    print("C. Speed your camel up to full speed.")
    print("D. Stop to rest your camel overnight.")
    print("E. Make an inventory of your supplies.")

