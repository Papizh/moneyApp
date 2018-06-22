# moneyApp 
Personal expenses management application that allows users to track how much money have they spent.
(Little changed output formating to be more clear and show only entered date expenses on use of add command, 
only list command shows all expenses for all dates.
And currencies exchange rates are requested only at application start, not every time on total command execute)

Application could be run from Main.class as java application. Tests in test folder, could be run all together by suite AllTests.class
To run from command line use command:
java -jar moneyExenses.jar
executed from files root directory

# List of commands  
add, list, clear, total, help, exit

add 2018-06-22 12 USD Jogurt  
 -- adds expenses entry to the list of user expenses. Expenses for various dates could be added in any order. Command accepts following parameters:
2018-06-22- is the date when expenses occured(choose date between 2000-2050)
12 - is an amount of money spent
USD - the currency in which expense occured 
Jogurt - is the name of product purchased (allows products name up to 29 symbols)

list
 -- shows the list of all expenses sorted by date

clear 2018-06-22
 -- removes all expenses for specified date, where 
2018-06-22 - is the date on which expenses should be removed

total PLN
 -- this command calculates the total amount of money spent and present it to use in specified currency, where
PLN - is the currency in which total amount of expenses shoul be presented

help
 -- presents list of available commands

exit
 -- stop program 
