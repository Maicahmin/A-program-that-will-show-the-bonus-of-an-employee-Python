# A-program-that-will-show-the-bonus-of-an-employee-Python
A program that will show the bonus of an employee by asking the employees years in service and office. 
The user will input number for years in service and the following office (IT, acct, hr)

    name = input("Enter your name: ")

    yrs = int(input("Enter yrs in service: "))

    office = str(input("Enter office: "))


    it1 = 10000

    it2 = 5000

    acct = 12000

    acct2 = 6000

    hr = 15000

    hr2 = 7500
 

    off1 = "IT"

    off2 = "ACCOUNTANT"

    off3 = "HR"


    if office == off1:

    if yrs >= 10:
    
        print("Hi " + name.upper() + ", your bonus is: " + str(it1))
        
    if yrs < 10:
    
        print("Hi " + name.upper() + ", your bonus is: " + str(it2))
        
    elif office == off2:

    if yrs >= 10:
    
        print("Hi " + name.upper() + ", your bonus is: " + str(acct))
        
    if yrs < 10:
    
        print("Hi " + name.upper() + ", your bonus is: " + str(acct2))
        
    elif office == off3:

    if yrs >= 10:
    
        print("Hi " + name.upper() + ", your bonus is: " + str(hr))
        
    if yrs < 10:
    
        print("Hi " + name.upper() + ", your bonus is: " + str(hr2))
        
    else:

    print(" \ninvalid occupation or n/a\n pls make sure the letter is correct and uppercase")
