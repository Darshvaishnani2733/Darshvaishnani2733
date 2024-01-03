year=int(input("Enter the year"))

if(year % 4 == 0):
 print("leap year")
elif(year % 400 == 0): 
 print("leap year")
else:
 print("Not a leap year")
