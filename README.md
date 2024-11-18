name=str(input("Please enter your name  :"))
print(name.capitalize().center(70,"#"),("\nwelcome to calcutta university"))
num = int(input("enter your number:    "))
if (num >= 0 and num <= 500): 
  if (num < 175):
    print("you are fail ")
  elif (num <= 249):
    print("your 3rd devision \n youre grade is C")
  elif (num <= 299):
    print("you 2nd devision\n youre grade is B")
  else:
    print("youre 1st devision \n youre grade is A")
else:
  print("your number is wrong")
