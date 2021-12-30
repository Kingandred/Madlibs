# Madlibs
#Setting up program
import time
print("Welcome to the Madlibs Stadium! Enter your name, and according to which name you enter into the program is which mad libs you get to do!")
user = input("Enter your name:")

#Clara - disney
if user == "clara":
    cnoun1 = input("Enter a noun:")
    cname1 = input("Enter a name:")
    cverb1 = input("Enter a verb:")
    cadjective1 = input("Enter an adjective:")
    cadjective2 = input("Enter an adjective:")
    cnoun2 = input("Enter a noun:")
    
    print("Elsa had been locked up in Arendelle castle by the", cadjective1, "prince hans. As she was escaping she saw a", cnoun1, "named", cname1,". As Elsa and", cname1, "escaped the castle, she said urgently: 'You must", cverb1, "this", cadjective2, "castle.'", cname1, "obeyed, and traveled on, eventually reaching a place of safety called:", cnoun2, ".")
#Paul - pokemon
if user == "paul":
    pname1 = input("Enter a name:")
    pregion1 = input("Enter a pokemon region:")
    pprofessor1 = input("Enter the professor's name:")
    pemotion1 = input("Enter an emotion:")
    
    print(pname1, "had just entered the world of Pokemon! He was in the", pregion1, "region, and ran all the way to Professor", pprofessor1,"'s office.")
    print("Excited to get a pokemon,", pname1, "rushed to the desk where all the pokemon were supposed to be. There weren't any. He looked around for clues, and to his surprise, he saw the dead Professor", pprofessor1, ".")
    print("Even though", pname1, "felt", pemotion1, "for the Professor's death, he stole the pokemon the man was carrying and took them for himself.")
    
    paul1 = input("Do you feel guilty about taking his pokemon?:")
    if paul1 == "yes":
        print(pname1, "felt bad about taking the pokemon and put them on the floor, right by the professor's dead body. The day after the man's death,", pname1, "got a pokemon in the mail the next day!")
    elif paul1 == "no":
        print(pname1, "felt no remorse and went home with his new pokemon. The very first day he tried training them, one of them had very powerful fire attacks the burned him, resulting in his death.")
#Andrew - zelda
if user =="andrew":
    print("Zelda")
#Peter - 
if user =="peter":
    print("Red Dead Redemption")
#Nathaniel - song of ice and fire
if user =="nathaniel":
    print("Song of Ice and Fire")

#Helena - travel
if user =="helena":
    print("denmark")
#Bryan - running
if user =="bryan":
    print("running")
