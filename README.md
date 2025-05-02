# meok
#Function to display the restaurant menu 
def show_menu():  
print("    \n            
OUR MENU\n") 
#Starters section 
print("Starters:") 
print("1. Chicken Wings - Rs. 300") 
print("2. Fries - Rs. 150") 
print("3. Soup - Rs. 200") 
#Main course section 
print("Main Course:") 
print("4. Biryani - Rs. 250") 
print("5. Chicken Karahi - Rs. 800") 
print("6. Naan - Rs. 30") 
print("7. BBQ Platter - Rs. 1200") 
#Desserts section 
print("Desserts:") 
print("8. Kheer - Rs. 120") 
print("9. Gulab Jamun - Rs. 100") 
print("10. Ice Cream - Rs. 150") 
#Beverages section 
print("Beverages:") 
print("11. Soft Drink - Rs. 50") 
    print("12. Lassi - Rs. 100") 
    print("13. Tea - Rs. 40") 
    print("14. Coffee - Rs. 70") 
#Infinite loop for main menu 
while True: 
#Display welcome message and options 
    print("Welcome to Restaurant Management System") 
    print("    1. View Menu") 
    print("    2. Exit") 
#user to choose an option 
    choice = input("Choose an option (1 or 2): ") 
#If user chooses to view menu 
    if choice == '1': 
        show_menu() 
#If user chooses to exit the program 
    elif choice == '2': 
        print("Thank you for visiting! Goodbye!") 
        break 
#In case user enters an invalid option 
    else: 
        print("\nInvalid option. Please try again.\n")
