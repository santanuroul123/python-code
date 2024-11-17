num = int(input("enter your number:    "))
if (num >= 0 and num <= 100):
  print("your number is right")
  if (num < 25):
    print("your semester not clear ")
  elif (num <= 40):
    print("your semester clear\n youre grade is C")
  elif (num <= 60):
    print("youre semester clear\n youre grade is B")
  elif (num <= 80):
    print("youre semester clear\n youre grade is A")
  else:
    print("youre semester clear\n youre grade is A+")
else:
  print("your number is wrong")
