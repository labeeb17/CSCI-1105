# CSCI-1105
Assignment and PoD codes.
##
# CSCI 1105
# Assignment 2: Problem 3 (p3.py)
# 

a = int(input())
b = int(input())
c = int(input())
print("Number 1:", a)
print("Number 2:", b)
print("Number 3:", c)

if a>100 or b>100 or c>100:
    print("Numbers must be between 1 and 99.")
    
else : 

    
    
        if a < 1 or a > 50 :
            calculation_1 = a * c
            print("Calculation 1: ", calculation_1)
        else :
            calculation_1 = a * b
            print("Calculation 1: ", calculation_1)
        

        if b % 2 == 0 :
            calculation_2 = b**2
            print("Calculation 2: ", calculation_2)
        else :
            calculation_2 = c**2
            print("Calculation 2: ", calculation_2)
   
        import math
        calculation_3 = round(math.sqrt(a), 2)
        print("Calculation 3: ", calculation_3)
    
        calculation_4 = max(a,b,c)
        print("Calculation 4: ", calculation_4)
    
        calculation_5 = min(a,b,c)
        print("Calculation 5: ", calculation_5)
 
    
