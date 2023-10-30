"""
1.user input the password
2.variables initialize to check criteria
3.check for each criteroia with if else condition
 """
# 1.
user_password = input("Enter password: ")


# 2.
length_crt = False
upper_crt = False
lower_crt = False
digit_crt = False
spl_char_crt = False

# checkinjg length
if len(user_password) >= 8 and len(user_password) <= 12:
    length_crt = True
    print("Length is good")
elif len(user_password) < 8:
    print("Password is too short")
else:
    print("password is too long")

# 3.
for i in user_password:
    if i.isupper():
        upper_crt = True
    if i.islower():
        lower_crt = True
    if i.isdigit():
        digit_crt = True
    if i in "!@#$%^&*()_+-=|\{}[];':<>?/.,":
        spl_char_crt = True

if length_crt and upper_crt and lower_crt and digit_crt and spl_char_crt:
    print("Password created is strong!")
if not upper_crt:
    print("Password should contain atleast one uppercase letter.")
if not lower_crt:
    print("Password should contain atleast one lowercase letter.")
if not digit_crt:
    print("Password should contain atleast one digit.")
if not spl_char_crt:
    print("Password should contain atleast one special character.")
if (
    not length_crt
    and not upper_crt
    and not lower_crt
    and not digit_crt
    and not spl_char_crt
):
    print("Password is weak")
