# Engineering 4 Notebook
This is where all my stuff will go!
## Headless
### Code
### Lessons Learned
## GPIO-Pins I2C
### Code
### Lessons Learned
## GPIO-Pins Flask
### Code
### Lessons Learned
## Hello Flask
### Code
### Lessons Learned
## SSH
### Code
### Lessons Learned
## Python
### Code
### Lessons Learned
## Bash
### Code
### Lessons Learned
## MSP
### Code
### Lessons Learned
## Strings and Loops
### Code
### Lessons Learned
## Forks and Clones
### Code
### Lessons Learned
## Hello Git 
### Code
### Lessons Learned
 
## Quadratic Solover
### Code 
##### [https://github.com/cmunro97/Engineering_4_Notebook/blob/master/Python/Quadsolver.py]
    import math

    def myFunction(a,b,c):
        return b**2-4*a*c

    def mathFunction(a,b,c):
        return[(-b+math.sqrt((b**2)-(4*(a*c))))/(2*a),(-b-math.sqrt((b**2)-(4*(a*c))))/(2*a)]


    a = int(input("Enter the coefficients of a: "))
    b = int(input("Enter the coefficients of b: "))
    c = int(input("Enter the coefficients of c: "))


    d = myFunction(a,b,c) #b**2-4*a*c # discriminant

    if d < 0:
        print ("This equation has no real solution")
    elif d == 0:
        print ("this equation has one solution: "), x
    else:
        print ("This equation has two solutions: ", mathFunction(a,b,c)[0], " or", mathFunction(a,b,c)[1])


### lessons learned

## Calculator 
### Code
##### [https://github.com/cmunro97/Engineering_4_Notebook/blob/master/Python/calc.py]
    a = input("Type a number")
    b = input("type a second number")
 

    def doMath(x,y,z):
        x = int(x)
        y = int(y)
        if z==1:
            return(str(x+y))
        if z==2:
            return(str(x-y))
        if z==3:
            return(str(x*y))
        if z==4:
            return(str(round (x/y,2)))
        if z==5:
            return(str(x%y))

    print("Sum:\t\t" + doMath(a,b,1))
    print("Difference:\t\t" + doMath(a,b,2))
    print("Product:\t\t" + doMath(a,b,3))
    print("Quotient:\t\t" + doMath(a,b,4))
    print("Modulo:\t\t" + doMath(a,b,5))
### Lessons learned
    The calculator alowed us as the users to input 2 numbers that would then be added, subtracted, divided, and multiplied. At first our code didn't allow for us to input a number but after trouble shooting we fixed it, then we had to figure out how to make the numbers round which we easily found code for by googling. 
## Dice Roller
### Code 
##### [https://github.com/cmunro97/Engineering_4_Notebook/blob/master/Python/diceroller3.py]
    from random import randint

    print ("Do you want to roll? (Y)es or (N)o")
    answer = input()
    while answer.lower()[0] == "y":
        num1 = randint(1,6)
        print ("You rolled a", num1)
        print ("Do you want to roll? (Y)es or (N)o")
        answer = input()
### Lessons learned
## Hello Python
### Code
##### [https://github.com/cmunro97/Engineering_4_Notebook/blob/master/Python/lesson00.py]
    str = "Hello World!"

    for x in range(0,10):
        print (str)
### Lessons leadrned
