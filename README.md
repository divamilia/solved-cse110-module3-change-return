Download Link: https://assignmentchef.com/product/solved-cse110-module3-change-return
<br>
We’ve developed a new cash register and like most machines, it subtracts the amount owed from the amount received to determine how much money the cashier must return to the customer. However, to avoid some human error, we automatically return the correct change through a coin dispenser. As our company’s only software engineer, you need to write the code this function.

You are to accept two amounts: the amount owed, and the amount received. Print a series of messages indicating how many dollars, quarters, dimes, nickels and cents are to be returned. For the dollar amount, just specify a whole number. It is not necessary to break it up into $10s, $5s or $1s. Also note that our coin dispenser does not hand out dollar coins or 50 cent pieces.

If the user provides less than the amount owed, print an error message which includes the amount short and terminate the program. The error message should look something like the following:

*** You did not provide enough money. You are $1.45 short. ***

<h1>2. Notes</h1>

<ul>

 <li>You are to return the fewest number of coins possible. While accurate, it is not acceptable to return 89 pennies if the change is $0.89.</li>

 <li>Floating point math may cause you some issues. Sometimes 0.10 – 0.03 is 0.069999… Consider converting to pennies for your internal calculations.</li>

 <li>Turn in only your source files. Do not use a package (e.g. use <em>dafault</em>).</li>

</ul>

<ol start="3">

 <li><strong>Required Main Class </strong></li>

</ol>

CoinMachine

<h1>4. Required Input</h1>

Amount owed, as a float

Amount Received, as a float

<strong>             </strong>

<h1>5. Required Output</h1>

Your output should look something like the following example. It should include your name.

Coin Machine – E. Eckert




Enter the amount owed: 2.34

Enter the amount received: 3.45




Your change today is $1.11




Dollars : 1

Quarters: 0

Dimes   : 1

Nickels : 0

Cents   : 1




Here’s another example:

Coin Machine – E. Eckert




Enter the amount owed: 6.45

Enter the amount received: 5.00




*** You did not provide enough money. You are $1.45 short. ***