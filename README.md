# PythonLoop
QA Python Loop Task
Objectives: To design and implement a Python application that prints all numbers between 1 and 100 with the square value in the allotted time specified.
Requirements: Create a python application that will loop between 1 and 100, the numbers are to be printed out alongside their squared value, the app should stop when a squared value of 200 or more is reached, reconfigure the application to take in a user value to produce squared values up to.
Acceptance Criteria: Requirements + Explanation.
No syntax errots, correct format + code written and saved within a .py file, user interaction + user is prompted for input and applicaiton responds, variables + data storage through variables implemented, control flow and iteration + control flow through loops and conditional statements implemented.


Test:
max_square = int(input("Enter the max square number"))
    for i in range(1,100):
        if i**2 < max_square:
            print("Number: {}, Square of Number: {}".format(i, i**2))
except Exception:
    print("Enter a valid input")
    
    Test2: 
    for Number in range (1, 101):
    count = 0
    for i in range(2, (Number//2 + 1)):
        if(Number % i == 0):
            count = count + 1
            break

    if (count == 0 and Number != 1):
        print(" %d" %Number, end = '  ')
