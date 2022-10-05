print("welcome to the python quiz!\n" + "what is your name?") #prints the introduction to the quiz and asks for users name
name = input()
score = 0
print("hello, " + name + "!") #prints hello, (name)!
answer = input("are you ready to quiz yourself on python? answer yes or no. ") #assigns a variable to user's answer
def question(answer: str) -> str:
    if answer == "yes":
        print("okay, let's get started!")
    if answer == "no":
        print("well, let's see how you do anyway!")
question(answer)
print("question one: what is a good way to keep track of code?\n a. document your code\n b. write the code on paper\n c. take pictures of your code\n d. none of the above")
answer1 = input()
def question1(answer1: str) -> str:
    if answer1 == "a":
        global score
        score = score + 1
        print("congratulations! you earned your first point!")
    else:
        print("sorry, your answer is incorrect or you did not properly format your answer :(")
question1(answer1)
print("okay, now for your second question.")
answer2 = input("how many possible returns are there for a boolean function?")
def question2(answer2: str) -> str:
    if answer2 == "2":
        global score
        score = score + 1
        print("congratulations, you just earned one more point!")
    else:
        print("sorry, your answer is incorrect or you did not properly format your answer :(")
question2(answer2)
print("okay, you're still here. let's do a third question.")
answer3 = input("your friend is trying to write an exponent in his math function. what is the correct operator for an exponent? ")
def question3(answer3: str) -> str:
    if answer3 == "**":
        global score
        score = score + 1
        print("congratulations, you just earned one more point!")
    else:
        print("sorry, your answer is incorrect or you did not properly format your answer :(")
question3(answer3)
print("your current score is: " + str(score) + " out of 5 possible points. there are two more questions left! now, let's go to question 4.")
answer4 = input("fill in the blank: the function str() returns an integer as a ___. (hint: write out the full word!)")
def question4(answer4: str) -> str:
    if answer4 == "string":
        global score
        score = score + 1
        print("congratulations! your score is now " + str(score) + "!")
    else:
        print("sorry, your answer is incorrect or you did not properly format your answer :(")
question4(answer4)
print("onto the final question! in order to pass you need at least 4 points :)")
answer5 = input("what operator do you use to return the remainder after dividing two numbers? (hint: type the operator, not the word!)")
def question5(answer5: str) -> str:
    if answer5 == "%":
        global score
        score = score + 1
        print("congratulations! your score is now " + str(score) + "!")
    else:
        print("sorry, your answer is incorrect or you did not properly format your answer :(")
question5(answer5)
def final_grade(score: int) -> float:
    final = score/5*100
    return float(final)
print("you scored " + str(score) + " out of 5. thats a " + str(final_grade(score)) + "%!")
print("thank you for taking the time to take my python quiz! it would mean a lot to me if you check out my github profile, which is\n github.com/j-larimore")
