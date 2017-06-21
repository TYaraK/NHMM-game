# NHMM-game
Game for the NHMM Period 6 project UM, 2017
print("Natuur Historisch Museum Maastricht")

print('Hello! What is your name, if I may ask?')
myName = input()

print('Well, {}, lets play a little game'.format(myName))

Question1= "Where was the mosasaurus found?"
Options1= "a. Sittard\nb. Paris\nc. Maastricht\nd. Eindhoven\n"
print(Question1)
print(Options1)

while True:
    response = input("Please select 'a', 'b','c' or 'd' to answer\n")

    if response == "c":
        break
    else:
        print("Incorrect!!! Please try again.")

        while True:
            response = input("Please select 'a', 'b','c' or 'd' to answer\n")

            if response == "c":
                stop = True
                break
        else:
            print("Incorrect!!! You ran out of attempts")
            stop = true
            break
        if stop:
            break



Question2= "How can you see that the mosasaurus is a sea animal?"
Options2= "a. Legs\nb. Head\nc. Abdomen\nd. Arms\n"
print(Question2)
print(Options2)

while True:
    response = input("Please select 'a', 'b','c' or 'd' to answer\n")

    if response == "d":
        break
    else:
        print("Incorrect!!! Please try again.")

        while True:
            response = input("Please select 'a', 'b','c' or 'd' to answer\n")

            if response == "d":
                stop = True
                break
        else:
            print("Incorrect!!! You ran out of attempts")
            stop = true
            break
        if stop:
            break


Question3= "Which animal is this skeleton from, look at the Dutch dinosaur?"
Options3= "a. 1\nb. 2\nc. 3\nd. 4\n"
print(Question3)
print(Options3)

while True:
    response = input("Please select 'a', 'b','c' or 'd' to answer\n")

    if response == "c":
        break
    else:
        print("Incorrect!!! Please try again.")

        while True:
            response = input("Please select 'a', 'b','c' or 'd' to answer\n")

            if response == "c":
                stop = True
                break
        else:
            print("Incorrect!!! You ran out of attempts")
            stop = true
            break
        if stop:
            break




Question4= "What animal is this ?"
Options4= "a. Turtle\nb. Mosasaurus\nc. Monkey\nd. Cat\n"
print(Question4)
print(Options4)

while True:
    response = input("Please select 'a', 'b','c' or 'd' to answer\n")

    if response == "a":
        break
    else:
        print("Incorrect!!! Please try again.")

        while True:
            response = input("Please select 'a', 'b','c' or 'd' to answer\n")

            if response == "a":
                stop = True
                break
        else:
            print("Incorrect!!! You ran out of attempts")
            stop = true
            break
        if stop:
            break




Question5= "In what age did the mosasaurus live?"
Options5= "a. Cretaceous Period\nb. Jurassic Period\nc. Triassic Period\n"
print(Question5)
print(Options5)


while True:
    response = input("Please select 'a', 'b','c' or 'd' to answer\n")

    if response == "a":
        break
    else:
        print("Incorrect!!! Please try again.")

        while True:
            response = input("Please select 'a', 'b','c' or 'd' to answer\n")

            if response == "a":
                stop = True
                break
        else:
            print("Incorrect!!! You ran out of attempts")
            stop = true
            break
        if stop:
            break

Question6= "What type of animal was the mosasaurus?"
Options6= "a. Omnivore\nb. Carnivore\nc. Herbivore\nd. Detritivore\n"
print(Question6)
print(Options6)

while True:
    response = input("Please select 'a', 'b','c' or 'd' to answer\n")

    if response == "b":
        break
    else:
        print("Incorrect!!! Please try again.")

        while True:
            response = input("Please select 'a', 'b','c' or 'd' to answer\n")

            if response == "b":
                stop = True
                break
        else:
            print("Incorrect!!! You ran out of attempts")
            stop = true
            break
        if stop:
            break 

Question7= "Which statement is incorrect?"
Options7= "a. The mosasaurus was not very long in length, this was so it could move easier through the water\nb. It had a streamlined body and flippers. This way it could sail effortlessly through the water at very high speeds\nc. The mosasaurus was said to weigh around 15 tons; tiwce the wieght of an elephant\nd. It had long jaws filled with razorsharp teeth\n"
print(Question7)
print(Options7)

while True:
    response = input("Please select 'a', 'b','c' or 'd' to answer\n")

    if response == "a":
        print("The mosasaurus was approximately 50 feet l-ongl this is the same size as a semi-truck")
        break
else:
    print("Incorrect!!! Please try again.")

    while True:
        response = input("Please select 'a', 'b','c' or 'd' to answer\n")

        if response == "a":
            stop = True
            break
        else:
             print("Incorrect!!! You ran out of attempts")
             stop = true
             break
        if stop:
            break

print("Thank you for playing and many happy returns")
