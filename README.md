# Adventure-Labirinth
Project for Python learning
print("Let's play a game of Labirinth!")
print("You are in a maze of twisty little passages, all alike. Some are narrow, some are wide, some are rough, and some are smooth. You are not sure about the way to go, but you are certain that you will find your way out.")
print()
print("Type 'left' to go left, 'right' to go right, 'up' to go up, and 'down'to go down.")
left = "left"
right = "right"
up = "up"
down = "down"
print("Now I need you to answer some questions.")
print()
friendName = input("What is your friend's name? ")
famMembName = input("What is your family member's name? ")
treasureType = input("What is the reward for getting out from Labirinth? ")
monsterName = input("What is the name of the monster? ")
warningSign = input("What is written on the warning sign? ")
superPower = input("what is your superpower? ")
print()
print("You are in a hallway. You see three directions: to the", right, "to the", left, "and to the", up, ".")
print("What direction you will choose? ", left, ",", right, "," , "or", up, "?")
print()
print("\033[1;32m", "You have decided to go to the", left, ".")
print()
print("\033[1;37m", "You see the door to the next room and a warning sign. The warning sign says:", "\033[0;34m", warningSign)
print()
print("To be continued...")
