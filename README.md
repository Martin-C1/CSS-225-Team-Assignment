# CSS-225-Team-Assignment


#Hello this is my edit<br>
#Hello this is a test edit<br>

#Oveview, would have to make assorted options to whenever the user picks a choice it will then prompt the user how many hours they will to do it<br>
option1= "1. Learn python"
option2= "2. Learn Java"
option3= "3. Go swimming"
option4= "4. Have dinner"
option5= "5. Go to bed"
option6= "6. Exit"

print(option1)
print(option2)
print(option3)
print(option4)
print(option5)
print(option6)
choice= input("Choose an option: ")

if choice == (option6):
    print("ending program")
elif choice in [option1, option2, option3, option4, option5]:
    hours= input(f"how many hours will you spend on {choice} ")
    print(f"You will spend {hours} hours on option {choice}")
else:
    print("invalid option")
