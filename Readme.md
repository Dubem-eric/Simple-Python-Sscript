 ##This is a sample Python script.

# Press Shift+F10 to execute it or replace it with your code.
# Press Double Shift to search everywhere for classes, files, tool windows, actions, and settings.
import datetime

x = datetime.datetime.now()

yr = int(x.strftime("%Y"))

print("What is your name?..")

name = input()

print('What is your date of birth')

date = int(input())
age = yr-date
print(" Your name is " + name + " and you are", age)
