title = The-Sign-In-Page-
User_name =input("what is your user name?")
email= input("what is your email? ")
age = int(input("what is your age? "))

print(f"My name is {User_name} {email} and I am {age } years old.")
print(f"Your email is {email}.")

 # -----account extra stuff-------

 # create a password 

password = input("create a password for your account ")
confirm_Password = input ("confirm your password")

if password == confirm_Password:
    print("Password confirmed!")
else:
    print("Passwords do not match. Please try again.")
if password == confirm_Password:
    print("Account created successfully!")
else:
    print("Failed to create account.")
