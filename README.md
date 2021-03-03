import time
import random

print("Let's see how many ways we can write 'hello' ")
print("This is displayed by printing items in a list: ")


my_list = ['h', 'e', 'l', 'l', 'o']


print(my_list[0])
print(my_list[1])
print(my_list[2])
print(my_list[3])
print(my_list[4])

time.sleep(2)

print('''

I'm using a string to talk right now, and I can also use it to say HELLO!  ''')

time.sleep(2)

print('''

Now I'll use the format function to use your name in my greeting! ''')
name = input("What's your name?")
print('Hello {}!'.format(name))

time.sleep(2)

print('''

I'll use an if/else statement to let you choose how you want me to greet you.''')

greetingChoice = input(" Would you like me to say 'hi' or 'hello'?").lower()

if greetingChoice.lower() == 'hi':
    print("Hi!")

elif greetingChoice.lower() == 'hello':
    print('Hello!')

else:
    print("Please type hi or hello")

time.sleep(2)

print('''

Now let's try picking a random letter from the word 'hello'!''')

time.sleep(2)

print('''

Remeber the first list we used to display 'hello'? The program can take a random item (letter) from that same list! Let's see what it chooses...''')

time.sleep(2)

letter = random.choice(my_list)
print(letter)

time.sleep(1)

print("The program chose the letter '{}' ! My favorite letter :)".format(letter))

