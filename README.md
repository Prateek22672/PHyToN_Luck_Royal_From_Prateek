#Python-Luck_Royal_From_Prateek
print("WELCOME TO PRATEEK'S LUCKY ROYAL {100% Garanted Gifts & Scam Free}\n")
print("Guess an Lucky number between (1 - 10)\nTo win An Apple iPhone 15 Pro MaX '&' Apple Watch series-9\nenter (start) to start LUCKY ROYAL\n")
g = 9
i = 0
l = 3
enter = input("enter:").lower()
if(enter == "start"):
 print("ALL THE BEST\n")
 while  (i < l):
    x = int(input('Guess: '))
    i += 1
    if  (x == (g-1)):
        print("You won Apple iPhone 15 Pro MaX")
        add = input("enter you address:")
        phone = input("enter Your Phone number")
        print("thank you, your Gft From PRATEEK'S LUCKY ROYAL Will be Delivered between 2-Working Days\nExpected Delivery Date-(31-12-2024)\nThank You")
        break
    elif  (x == g):
        print("You won Apple WAtch Series-9")
        add = input("enter you address:")
        phone = input("enter Your Phone number")
        print("thank you, your Gft From PRATEEK'S LUCKY ROYAL Will be Delivered between 2-Working Days\nExpected Delivery Date-(31-12-2024)\nThank You")
        break
    elif (i==l):
       print("BETTER LUCK NEXT TIME")
    else:
        print("Opss Not this time")

elif(enter == "stop"):
   print("Thank you")
