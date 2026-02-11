# Guess-Who-
I made a Guess Who game in Python! pls dont bully its my first project...
Project v1: gameplay = True
while gameplay:
    wears_accessories = input("Does your character wear an accessory? ")
    if wears_accessories == "yes": #6 people wears accessories such as earrings, hats, and glasses, and the rest don't
        wears_hat = input("Is the accessory that your character wears a hat? ")
        if wears_hat == "yes":
            ends_with_L = input("Does your character's name end with a L? ")
            if ends_with_L == "yes":
                red_hat = input("Are they wearing a red hat? ")
                if red_hat == "yes":
                    print("The character is Rachel.")
                else:
                    print("The character is Daniel.")
            else:
                print("The character is Brandon.")
        else:
            wears_earrings = input("Is your character wearing earrings? ")
            if wears_earrings == "yes":
                blue_eyes = input("Does your character have blue eyes? ")
                if blue_eyes == "yes":
                    print("The character is Megan.")
                else:
                    print("The character is James.")#If you look closely, you can see that James has one gold earring, which may be hard to see but it's there
            else:
                print("The character is Alex.")
    else:
        start_with_J = input("Does the character's name start with J? ")
        if start_with_J == "yes":
            moustache = input("Does your character have a moustache? ")
            if moustache == "yes":
                blond_hair = input("Does your character have blond hair? ")
                if blond_hair == "yes":
                    print("The character is Jake.")
                else:
                    print("The character is Justin.")
            else:
                print("The character is Jon.")
        else:
            looking_to_the_side = input("Is your character looking to the side? ")
            if looking_to_the_side == "yes":
                mouth_is_open = input("Is your character's mouth open? ")
                if mouth_is_open == "yes":
                   print("The character is Andy.")
                else:
                    print("The character is William.")
            else:
                print("The character is Matt.")

    play_again = input("Do you want to play again? ")
    if play_again == "no":
        print("Goodbye.")
        gameplay = False


How It's Made:
Tech used: PyCharm
It took me a while to create this because I had to split all of the people into different groups and equally give them 3-4 questions until the bot was able to guess.

Lessons Learned:
I really learned how to use if...then... statements and repeatibly use them until I ended up with this!
