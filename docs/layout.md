# Project layout

The project is structurated in three folders, one for the configuration files such as language.py and secrets.py, then there are a second folder with the test file that contains the test for the rates calculation function, and there is the src file where the most part of the program lives.

## Main.py

This is the first file that te program runs, inside there are the menu configurations and the symbols used in the program: symbols = ['GGAL', 'YPFD', 'PAMP', 'DLR']

## Config Folder

inside we have the language and the secrets files:

###### Language.py

Here we have all the translation for the entire program that allow us to select in the menu the language that we want and change the visualization of the program with that language.

###### Secrets.py

Inside this file we have the secrets of the communication with the api such as the user, account and password for the remarket api.

## Test

Inside this file we have the test_RatesCalculator.py file, 

###### test_RatesCalculator.py

With this file we can run the test cases for the 2 methods inside the RatesCalculator class: calculate_offered_rate() and calculate_taker_rate()

## src

The most part of the program lives here:

###### clear.py

This small file allow us to clear the console if the user select that option in the menu

###### consolePrinter.py

This file has the necessarily function to print the tables in the console with the relevant information about the futures with Printer function and the arbitrage oportunities with the Printer_arbitrage_oportunities function.

###### RatesCalculator.py

This file has the functions to calculate the taken rate and the offered rate of the futures passed as a parameter.

That functions can be tested with the test_RatesCalculator.py file inside the test folder.

###### Strategy.py

Inside this file the program can calculate and checks the arbitrage possibilities, according with the choosen arbitrage strategy.

###### TraderBot.py

This is the biggest file, inside the program calls the functions inside the others files to retrieve the relevant information or to show the content in the console. Also here the program controls the communication with the remarket enviroment with web sockets and the yfinance api communication.
