
mark = int(input("Enter final mark for CSF"))
if mark >= 40:
   elem1 = int(input("Enter mark for element1:"))
   if elem1>=20:
      print("You have passed")
   else:
      print("You needed a minimum of 20 for this element to pass the module")
elif mark >= 20:
      print("You have failed but are eligible for a re-sit")
else:
      print("Sorry! You will have to re-take your module")
