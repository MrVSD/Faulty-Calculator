

# 45*3 = 555 , 56+9 = 77, 56/6 = 4

print("Entre + to sum")
print("Entre - to sub")
print("Entre * to mul")
print("Entre / to dev")

userInput = input("Entre the mentioned key: ")

if userInput =='+':
    num1 = float(input("Entre num1: "))
    num2 = float(input("Entre num2: "))

    if num1 == 56 and num2 == 9:
        print("The sum is: 77")

    else:
        print("The sum is:", num1+num2)


elif userInput =='-':
    num1 = float(input("Entre num1: "))
    num2 = float(input("Entre num2: "))

    if num1 == 98 and num2 == 68:
        print("The sub is: 48")

    else:
        print("The sub is:", num1-num2)

elif userInput =='*':
    num1 = float(input("Entre num1: "))
    num2 = float(input("Entre num2: "))

    if num1 == 45 and num2 == 3:
        print("The mul is: 555")

    else:
        print("The mul is:", num1*num2)

elif userInput =='/':
    num1 = float(input("Entre num1: "))
    num2 = float(input("Entre num2: "))

    if num1 == 56 and num2 == 6:
        print("the div is: 4")

    else:
        print("the div is:", num1/num2)
