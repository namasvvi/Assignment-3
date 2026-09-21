# Assignment 3
def triangle(a,b,c):
    if a*a+b*b==c*c or a*a+c*c==b*b or b*b+c*c==a*a :
        return True
        return False
x=int(input("Enter side 1 :"))
y=int(input("Enter side 2 :"))
z=int(input("Enter side 3 :"))
if triangle(x,y,z):
    print("Right angled triangle")
else:
    print("Not a right angled triangle")