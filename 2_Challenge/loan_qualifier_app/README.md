# Loan Qualifier Application

This application is used as a financial calculator that will provide you with a list of loans you qualify for based off you credit score, monthly debt, monthly income, desired loan amount, and home value. After providing all the details necessary, the loans will be saved to a csv file for you to have the ability to compare all the loans. 

---

## Technologies

This application requires all the following:

1. Python 3.10.9
2. Fire 0.3.1
3. Questionary 1.5.2
4. CSV
5. Pathlib
6. Sys

<img width="196" alt="image" src="https://user-images.githubusercontent.com/92451674/207772086-c3d5a820-6502-40b6-9783-42bf18cff2d0.png">


---

## Installation Guide

Download and import all the modules prior to this guide. After that is completed open your terminal and run the app.py file. You will be met with questions which will have to be answered to get results.

---

## Usage

Once the app.py file is executed, you will be asked to provide the path for the csv file containing all the loans. After that you will be asked to input your credit score, current monthly debt, total monthly income, desired loan amount, and the home value. Shortly after it will spill out your monthly debt to income ratio, loan to value ratio, and the amount of loans you qualify for. You will be met with the option of saving all the loans you qualify for to a csv file, which can later be used to compare and contrast all the different loans. Below you will find a screenshot of what the CLI will look like once you run the application and input all your values correctly.

<img width="421" alt="image" src="https://user-images.githubusercontent.com/92451674/207771807-a53b433b-0a9b-4026-b5c8-7bfd0f4cfbed.png">

---

## Changes to App

Only two major changes were done to the pre-existing application which were the following.

<img width="355" alt="image" src="https://user-images.githubusercontent.com/92451674/207772443-2173e1f6-2f35-4a5f-b4d1-87ddf2310c97.png">

Above I created a function named save_csv in the input/output file which is used to create a csv file and write into it whichever list we run through it, I then imported the function to the main app file to connect with the save_qualifying_loans function; which is shown below.

<img width="623" alt="image" src="https://user-images.githubusercontent.com/92451674/207772351-4db4ce79-fc2a-462c-a979-32c79271b039.png">

I then implemented a question into the CLI after being provided all the details needed to calculate the users qualifying loans to confirm if the user would like to save the list unto a CSV file. Also with that being said the user is presented with two options Y/N (Yes or no). If the user inputs Y then the csv file will be updated, if not then the command line will display some text confirming the user did not want to save the list unto the qualifying csv file. 

---

## Contributors

Created by: Bryan Rodriguez

---

## License

This project is in the public domain within the United States.

We waive copyright and related rights in the work worldwide through the CC0 1.0 Universal public domain dedication.


