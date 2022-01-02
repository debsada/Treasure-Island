# Treasure-Islandd
A choose your own adventure game

print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.")
decision_1 = input("Let's start! First important decision, left or right? ") 

if decision_1 == "left":
  decision_2 = input("Good job! You've made it to the sea of doom, would you like to swim or wait? ") 
  if decision_2 == "wait":
    decision_3 = input("Good choice for a sea called doom! The mystery doors have appeared, which will you choose, red, blue or yellow? ")
    if decision_3 == "yellow":
      print("Congratulations you win! Enjoy the treasure! ")
    elif decision_3 == "red":
      print("Burned by fire, game over! ")
    elif decision_3 == "blue":
      print("You were eaten by beasts, game over! ")
    else:
      print("You died of natural causes, game over! ")
  else:
    print("sorry, you drowned. Game over! ")
else:
  print("You fell into a hole. game over! ")
