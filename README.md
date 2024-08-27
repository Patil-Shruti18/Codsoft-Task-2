# Codsoft-Task-2
# Calculator

print("1. Addition \n2. Substraction \n3. Multiplication \n4. Division")
z=int(input("Enter your choice -"))
print("-----------------")
x=int(input("Enter 1st number:"))
y=int(input("Enter 2nd number:"))
print("-----------------")
add=x+y
sub=x-y
mult=x*y
div=x/y

if z==1:
    print("Addition:",add)
elif z==2:
    print("Substraction:",sub)
elif z==3:
    print("Multiplication:",mult)
elif z==4:
    print("Division:",div)
else:
    print("Please enter a valid choice...")
