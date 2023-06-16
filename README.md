class Food_items():
    
    def __init__(self,id,name,price,Quantity,Discount):
        self.id = id
        self.name = name
        self.price = price
        self.Quantity=Quantity
        self.Discount=Discount
        
F1= Food_items(1,'Paneer Angara','250rs','250gm','5% Dis')
F2= Food_items(2,'Veg Handi','159rs','250gm','5% Dis')
F3= Food_items(3,'Chicken leg piece ','500rs','4 piece','10% Dis')
F4= Food_items(4,'Fish piece ','450rs','4 piece','10% Dis')
F5= Food_items(5,'Coca-cola','60rs','100 ml','No discount')
F6= Food_items(6,'Thums up','65rs','100 gm','No discount')

print(F1.id,F1.name,F1.price,F1.Quantity,F1.Discount)
print(F2.id,F2.name,F2.price,F2.Quantity,F2.Discount)
print(F3.id,F3.name,F3.price,F3.Quantity,F3.Discount)
print(F4.id,F4.name,F4.price,F4.Quantity,F4.Discount)
print(F5.id,F5.name,F5.price,F5.Quantity,F5.Discount)
print(F6.id,F6.name,F6.price,F6.Quantity,F6.Discount)

# Edit food items using FoodID.
print("\n Edit food items using FoodID. :- ")
if F1.id == 3:
    print("\n Truffle Cake 500gm) [INR 900] 10 per n/")
else : 
    print("\n Chicken leg piece  500rs 4 piece 10% Dis ")

# View the list of all food items
print("\n View the list of all food items :- ")
dict1 = {'name':'tandoori chicken', 'name1':'tandoori roti','name2':'paneer angara','name3':'Veg handi','name4':'Thums up','name5':'Coca cola'}

list = list(dict1.items())
print(list)

# Remove a food item from the menu using FoodID.
print("\n Remove a food item from the menu using FoodID.:-  ")
if F1.id == 1:

    print("\n Tandoori Chicken (4 pieces) [INR 240] 5 per")
else :
    print("\n 2 Vegan Burger (1 pieces) [INR 320] 5 per")

# The user will have the following functionalities:
print("\n The user will have the following functionalities:-  ")
class User():    
    
    def __init__(self,Full_Name,Phone_Number,Email,Address,password):
        
        self.Full_Name = Full_Name
        self.Phone_Number = Phone_Number
        self.Email = Email
        self.Address = Address
        self.password = password
Us = User('Dilliprasanna',9030315895,'dilliprasanna1295@gmail.com','Banglore-Karnataka','prasanna1995')
print(Us.Full_Name)
print(Us.Phone_Number)
print(Us.Email)
print(Us.Address)
print(Us.password)

print("\n The user login id & password:-  ")
class User_login(): 
    def signup(self,username,password):
        self.username = username
        self.password = password
        return "singup succeed"
    
    def login(self,username,password):
        if self.username == username and self.password==password:
            return "logged in"
        else:
            return "Username and password is incorrect"
        
U1 =  User_login()
print(U1.signup('Dilliprasanna','prasanna1995'))
print("register sucessful")
print(U1.login('Dilliprasanna','prasanna1995'))
print(U1.login('Dilliprasanna','prasanna1995'))
print(U1.login('D','prasanna'))

# Place New Order: The user can place a new order at the restaurant.
# Show list of food. The list item should as follows:
# 1. Tandoori Chicken (4 pieces) [INR 240]
# 2. Vegan Burger (1 Piece) [INR 320]
# 3. Truffle Cake (500gm) [INR 900]

print("\n Place New Order: The user can place a new order at the restaurant.:-  ")

class place_order(Food_items):
    
    def __init__ (self):
        
        if place_order == Food_items :
            return (Food_items)
        else:
            print("1. Tandoori Chicken (4 pieces) [INR 240] 5 per")
            print("2. Vegan Burger (1 pieces) [INR 320] 5 per")
            print("3. Truffle Cake (500gm) [INR 900] 10 per")
f11 = place_order()


# Order History should show a list of all the previous orders
print("\n Order History should show a list of all the previous orders :-  ")
class order_history(Food_items):
    
    def __init__ (self):
        
        if order_history == Food_items :
            return (Food_items)
        else:
            print("2. Vegan Burger (1 pieces) [INR 320] 5 per")
            print("3. Truffle Cake (500gm) [INR 900] 10 per")
f3 = order_history()


# Update Profile: the user should be able to update their profile.
print("\n Update Profile: the user should be able to update their profile :-  ")
class User_update_profile (User):    
    
    def __init__(self):

        self.Full_Name = Full_Name
        self.Phone_Number = Phone_Number
        self.Email = Email
        self.Address = Address
        self.password = password
        
U1 = User('Dilliprasanna',9030315895,'dilliprasanna1295@gmail.com','Banglore-Karnataka','prasanna1995')
print = input('Enter your name : ')

print = input('Enter mobiled no. : ')

print = input('Enter Email id: ')

print = input('Enter address : ')

print = input('Enter password : ')

print = input("updated sucessfully")

print = input ("Thank you for your time.")
print = input ("Please Visit Again.")

