a=float(input("Enter 1st item : "))
q1=int(input("Enter quantity of 1st item : "))
b=float(input("Enter 2nd item : "))
q2=int(input("Enter quantity of 2nd item : "))
c=float(input("Enter 3rd item : "))
q3=int(input("Enter quantity of 3rd item : "))
total=(a*q1)+(b*q2)+(c*q3)
if(total>50):
   print(f"The total cost of items is: {total-(1/10)*total}")
else:
  print(f"The total cost of items is: {total}")
