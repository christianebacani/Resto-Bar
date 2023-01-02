# Resto-Bar
Creating simple program of resto bar ordering system using Python

# Code

def order():
    print("WELCOME TO CHRISTIANE BACANI'S RESTO BAR\n")
    enter=str(input("Press any key to continue\n"))
    print("\nPlease choose a category")
    print("(1) Meal")
    print("(2) Drinks")
    print("(3) Snacks")
    menu=int(input("\nType Here:\n"))
    if menu == 1:
        print("\nWhat type of Meal")
        print("(1) Adobo = 50.00")
        print("(2) Chicken w/rice = 65.00")
        print("(3) Sisig w/rice = 75.00")
        menumeal=int(input("\nType Here:\n"))
        if menumeal == 1 :
            quantitymeal=int(input("\nEnter the quantity for your meal\nType Here: "))
            mealprice=0
            meal=0
            while meal < quantitymeal:
               mealprice+=50
               meal+=1
            print("\nYour total bill:",mealprice)
            cash=int(input("\nEnter your cash: "))
            change=cash-mealprice
            print("\nYour change is:",change)
            print("\n\n---------------     THANK YOU     ---------------")
        elif menumeal == 2:
               quantitymeal2=int(input("\nEnter the quantity for your meal\nType Here:\n"))
               mealprice2=0
               meal2=0 
               while meal2< quantitymeal2:
                  mealprice2+=65
                  meal2+=1
               print("\nYour total bill:",mealprice2)
               cash2=int(input("\nEnter your cash:"))
               change2=cash2-mealprice2
               print("\nYour change is:",change2)
               print("\n\n---------------     THANK YOU     ---------------")
        elif menumeal == 3:
               quantitymeal3=int(input("\nEnter the quantity for your meal\nType Here: "))
               mealprice3=0
               meal3=0
               while meal3 < quantitymeal3:
                   mealprice3+=75
                   meal3+=1
               print("\nYour total bill:",mealprice3)
               cash3=int(input("\nEnter your cash: "))
               change3=cash3-mealprice3
               print("\nYour change is:",change3)
               print("\n\n---------------     THANK YOU     ---------------")
    elif menu == 2:
        print("\nWhat type of Drinks")
        print("(1) Softdrinks = 15.00")
        print("(2) Juice = 12.00")
        print("(3) Water = 10.00")
        menudrinks=int(input("\nType Here:\n"))
        if menudrinks==1:
            quantitydrinks=int(input("\nEnter the quantity for your drinks\nType Here: "))
            drinksprice=0
            drinks = 0 
            while drinks< quantitydrinks:
                drinksprice+=15
                drinks+=1
            print("\nYour total bill",drinksprice)
            cashdrinks=int(input("\nEnter your cash: "))
            changedrinks=cashdrinks-drinksprice
            print("\nYour change:",changedrinks)
            print("\n\n---------------     THANK YOU     ---------------")
        elif menudrinks==2:
            quantitydrinks2=int(input("\nEnter the quantity for your drinks\nType Here: "))
            drinksprice2=0
            drinks2 = 0
            while drinks2 < quantitydrinks2:
                drinksprice2+=12
                drinks2+=1
            print("\nYour total bill",drinksprice2)
            cashdrinks2=int(input("\nEnter your cash: "))
            changedrinks2=cashdrinks2-drinksprice2
            print("\nYour change:",changedrinks2)
            print("\n\n---------------     THANK YOU     ---------------")
        elif menudrinks==3:
            quantitydrinks3=int(input("\nEnter the quantity for your drinks\nType Here: "))
            drinksprice3=0
            drinks3 = 0 
            while drinks3 < quantitydrinks3:
                drinksprice3+=10
                drinks3+=1
            print("\nYour total bill: ",drinksprice3)
            cashdrinks3=int(input("\nEnter your cash: "))
            changedrinks3=cashdrinks3-drinksprice3
            print("\nYour change:",changedrinks3)
            print("\n\n---------------     THANK YOU     ---------------")
    elif menu == 3:
             print("\nWhat type of Snacks")
             print("(1) Isaw = 8.00")
             print("(2) Barbecue = 15.00")
             print("(3) Chitcharong Bulaklak = 20.00")
             menusnacks=int(input("\nType Here:\n"))
             if menusnacks == 1:
                quantitysnacks=int(input("\nEnter the quantity for your snacks:\nType Here: "))
                snacksprice=0
                snacks=0
                while snacks < quantitysnacks:
                    snacksprice+=8
                    snacks+=1
                print("\nYour total bill:",snacksprice)
                cashsnacks=int(input("\nEnter your cash: "))
                changesnacks=cashsnacks-snacksprice
                print("\nYour change:",changesnacks)
                print("\n\n---------------     THANK YOU     ---------------")
             elif menusnacks == 2:
                 quantitysnacks2=int(input("\nEnter the quantity for your snacks:\nType Here: "))
                 snacksprice2=0
                 snacks2=0
                 while snacks2< quantitysnacks2:
                    snacksprice2+=15
                    snacks2+=1
                 print("\nYour total bill:",snacksprice2)
                 cashsnacks2=int(input("\nEnter your cash: "))
                 changesnacks2=cashsnacks2-snacksprice2
                 print("\nYour change:",changesnacks2)
                 print("\n\n---------------     THANK YOU     ---------------")
             elif menusnacks == 3:
                 quantitysnacks3=int(input("\nEnter the quantity for your snacks: "))
                 snacksprice3=0
                 snacks3=0
                 while snacks3 < quantitysnacks3:
                    snacksprice3+=20
                    snacks3+=1
                 print("\nYour total bill:",snacksprice3)
                 cashsnacks3=int(input("\nEnter your cash: "))
                 changesnacks3=cashsnacks3-snacksprice3
                 print("\nYour change:",changesnacks3)
                 print("\n\n---------------     THANK YOU     ---------------")
                 
                 
order()
