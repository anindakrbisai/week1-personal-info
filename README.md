# week1-personal-info
# A simple Python project that displays personal information, created as part of Week 1 practice on GitHub and Python basics.

# -----------------------------------------
# Name: Aninda Bisai
# Project: Personal Information Manager
# Description:
# This program stores and displays
# personal information using variables,
# user input, validation, and formatting.
# -----------------------------------------

# Welcome Message
print("=" * 50)
print("      PERSONAL INFORMATION MANAGER")
print("=" * 50)
print()

# -----------------------------------------
# Store Static Information
# -----------------------------------------

# Store name as a string
name = "Aninda Bisai"

# Store age as an integer
age = 20

# Store city as a string
city = "Siliguri"

# Store hobby as a string
hobby = "Coding"

# -----------------------------------------
# Get User Input
# -----------------------------------------

print("Please tell me about yourself:")
print("-" * 40)

# Ask for favorite food
favorite_food = input("What's your favorite food? ").strip()

# Validate food input
while favorite_food == "":
    print("Please enter a valid food!")
    favorite_food = input("What's your favorite food? ").strip()

# Ask for favorite color
favorite_color = input("What's your favorite color? ").strip()

# Validate color input
while favorite_color == "":
    print("Please enter a valid color!")
    favorite_color = input("What's your favorite color? ").strip()

# -----------------------------------------
# Calculate Age in Months
# -----------------------------------------

age_in_months = age * 12

# -----------------------------------------
# Display Information
# -----------------------------------------

print()
print("=" * 50)
print("           YOUR INFORMATION")
print("=" * 50)
print()

# Display formatted information
print(f"Name            : {name.title()}")
print(f"Age             : {age} years")
print(f"Age in Months   : {age_in_months} months")
print(f"City            : {city.title()}")
print(f"Hobby           : {hobby.capitalize()}")

print()

print(f"Favorite Food   : {favorite_food.title()}")
print(f"Favorite Color  : {favorite_color.capitalize()}")

print()

# -----------------------------------------
# Goodbye Message
# -----------------------------------------

print("=" * 50)
print("Thanks for using this program!")
print("Have a great day!")
print("=" * 50)
