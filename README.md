 print("Simple chatbot")
print("=========================================")
print("You may ask any one of these questions:")
print("hello")
print("How are you?")
print("What is your name?")
print("bye")
print("Quit")
print("=========================================")

while True:
    question = input("Enter one question from above list: ")
    question = question.lower().strip()

    if question in ["hello"]:
        print("Hi!")

    elif question in ["how are you?"]:
        print("I'm fine, thank you")

    elif question in ["what is your name?"]:
        print("My name is xyzbot")
        name = input("What is your name: ")
        print("Nice name, and nice meeting you", name)

    elif question in ["bye"]:
        print("Good bye!")
        break

    elif question in ["quit"]:
        print("Program closed")
        break

    else:
        print("Sorry, I don't understand what is said")
