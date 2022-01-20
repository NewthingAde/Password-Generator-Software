# Password Generator Software
 Password Genearator software ia a software that generate password base on the user preference and save it in a local CSV file. 

# How it works

The program present a menu of what the user wants to do. 

 
Choose between 1-4!
 1. Generate a password
 2. Display password
 3. Clear password
 4. Customize password
 5. EXIT

    If the User pick one, it will ask;

        Choose what kind of difficulty you want for your password. Choose between 1-4: 

        1. Easy
        2. Medium 
        3. Strong

    it will ask the user to select a name of the website or app the password is used for and the password will be saved in a local CSV file

2. If the user select 2. It will diplay the password on the screen

3. if the user select 3 it will clear the password 

4. if the user select 4, it will ask the user ;

        Minimum 8 characters in total!

        How many uppercase letter do you want?: 
        How many lowercase letter do you want?: 
        How many digits letter do you want?: 
        How many special characters do you want?: 
        What website is the password for? 

    It will generate the password base on the user preference.

5. If the user select 5 it will Exit the program

# Why Password Generator Software
Password has been an integral part of our life. We make use of password in our dialy life which is too taking and this let us outsourced saving of our password to to our web brwser. However due to increasing rate of cyber threat it is import to find a creative way of building a sustainable solution to make our passoword secure. This bring about the creation of this software.


# The Program componenets

The software is built purely on python language with some import library from pandas

The program has 8 function which perform dofferent task. A brief explaination of each function is given below

def easy_password():
    This generates an easy password containing a string with 4 letters and 4 digits.


def medium_password():
    This generates a generate a medium password containing a string with 5 letters and 5 digits with atleast two upper- and lowercase. 


def strong_password():
    This generates a medium password containing a string with 5 letters, 5 digits and 2 special charachters with atleast two upper- and lowercase. 


def auto_password():
    This generates a medium password containing a string with 5 letters, 5 digits and 2 special charachters with atleast two upper- and lowercase. 

def user_choice():
    This function displays what level of password the user wants.


def save_password(choice):
    This function takes the saved password and asks the user what the of the password will be and then saves add the name and the password to an existing CSV-file. 

def reading_DF():
    This function reads the csv file.


def feedback(choice):
    This function clears the csv file