first_name, second_name = input("Enter your first name and second name \n") .split()
while any(i.isdigit() for i in first_name):
    print("Invalid first name and second name")
    first_name, second_name = input("Enter your first name and second name \n") .split()
username = second_name[0:5] + first_name[0]

print("Your username is " + username.lower())
