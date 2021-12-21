
"""
Design a faulty calculator which will correctly solve all the problems except the following ones:
 45 * 3 = 555, 56+9 = 77, 56/6 = 4
 Your program should take operator  and the two numbers as input from the user and then return the result
"""

print("enter 1st number: ")
n1=int(input())
print("enter 1st number: ")
n2=int(input())
print("what you want to perform(+,-,*,/):- ")
op=input()
if op=="+"  and n1==56 and n2==9:
    print(77)
elif op=="+":
    print(n1+n2)
elif op=="*"  and n1==45 and n2==3:
    print(999)
elif op=="*":
    print(n1*n2)
elif op=="/"  and n1==56 and n2==6:
    print(4)
elif op=="/":
    print(n1/n2)
else:
    print(n1-n2)
