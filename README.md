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
    question = question.lower()

    if question in ["hello"]:
        print("Hi!")
    elif question in ["how are you?"]:
        print("I'm fine, thank you")
    elif question in ["what is your name?"]:
        print("my name is xyzbot")
        name = input("what is your name: ")
        print("nice name, and nice meeting you", name)
    elif question in ["bye"]:
        print("good bye!")
    elif question in ["quit"]:
        break
    else:
        print("sorry, I don't understand what is said")
        
