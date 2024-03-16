# game

print("Welcome to Treasure Island.\U0001F334 \nYour mission is to find the treasure.\U0001F4B8,\n ")          
print("You have two ways and you have to choose the right way to reach the island.\nSo concentrate!!\U0001F608 ")      
print()
answer_question = input("woulde you like to turn Right or Left?\n ")     
print()

if answer_question== "Left" :
    print("You have reached a sea, after which there is an island.\nYou have two ways to cross the sea, one of which you have to choose \U0001F4AA")
    print()
    answer_question2 = input("You Swim to reach the island Or you Wait for a boat to come?\n ")
    if answer_question2 == "Wait":
        print("Well, you managed to reach the island, now there are three doors in front of you and there is a treasure behind one of the doors!!\U0001F6B7")
        print()
        answer_question3 = input("There are three doors with three colors: Yellow, Blue and Red, which one do you choose?\n ")
        if answer_question3 == "Blue":
            print("You opened the wrong door, there was no treasure behind this door. ")
        elif answer_question3 == "Red":
            print("You opened the wrong door, there was no treasure behind this door. ")
        else:
            print("Congratulations, you found the treasure!!!\U0001F4B0 ")
    else:
        print("I'm sorry, the sharks ate you and you died \U0001F31A")
else:
     print("I'm sorry, you can't continue playing because you lost\U0001F479")
