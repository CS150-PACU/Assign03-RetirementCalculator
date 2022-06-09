## CS150 Assignment 3

Can I Retire???

**Date assigned:** Wednesday, September 28, 2021

**Program due:** Wednesday, October 6, 2021, \[9:15AM Sect 02; 1:00PM
Sect 01\]

**Points:** 25

**Goals:**

1.  Understand how to construct and use a loop

2.  More data validation

**Retirement Questions**

As soon as you start working, you should begin investing in a retirement
plan such as a 401k or an IRA. The sooner you start investing; the
sooner you can retire if you so desire. This program will help you
decide what you should do!

-   If I gave each of you $1,000 to invest, how many would know what to
    do?

-   How much money do you think you need to save to comfortably retire?

-   Will Social Security be around when you retire?

-   How much will you pay for medical expenses in retirement?

When you get close to retirement, you will have saved about all of the
money you can. At that point, you will need to start withdrawing money
from your retirement to live on. This money will need to last you the
rest of your life. If you retire at 65, you could live another 25+
years. Will you have enough money to do so comfortably?

Fun Facts
(https://www.personalcapital.com/blog/retirement-planning/average-401k-balance-age/)

<pre>
Vanguard Data of Average 401k by Age (2021)

AGE         AVERAGE 401K BALANCE    MEDIAN 401K BALANCE
22 - 25     $5,419                  $1,817
25 - 34     $26,839                 $10,402
35 - 44     $72,578                 $26,188
45 - 54     $135,777                $46,363
55 - 64     $197,322                $69,097
65 +        $216,720                $64,548
</pre>

**Here is the problem that you are to solve**

Write a C++ program that will calculate how long your money in a
retirement plan will last if you take out a fixed amount every year.
Your program is to terminate when the ending balance is less than the
amount withdrawn.

The user will input a retirement total (double), an amount to be taken
out every year (double), and a yearly rate of return on the remainder of
the money in the retirement account (double). User inputs are in bold
below.

Your program will output a report as follows:

<pre>
*** How Long Will My Retirement Last? ***

Enter Retirement Account Value: $ <b>64548.00</b>
Enter Amount Withdrawn Yearly: $ <b>12000.00</b>
Enter Rate of Return: % <b>4.0</b>

   Beginning         Amount       Earnings           Ending     Year
     Balance      Withdrawn                         Balance
------------     ----------     ----------     ------------     ----
$   64548.00     $ 12000.00     $  2101.92     $   54649.92        1
$   54649.92     $ 12000.00     $  1706.00     $   44355.92        2
$   44355.92     $ 12000.00     $  1294.24     $   33650.15        3
$   33650.15     $ 12000.00     $   866.01     $   22516.16        4
$   22516.16     $ 12000.00     $   420.65     $   10936.81        5
</pre>

You are to make sure that the user enters a value greater than 0.0 for
the Retirement Account Value, the Amount Withdrawn Yearly, and the Rate
of Return. Further, make sure that the user does not try and withdraw
more money than is in the account. Here are some sample invalidation
examples. These examples are not exhaustive.

<pre>
*** How Long Will My Retirement Last? ***

Enter Retirement Account Value: $ <b>-10</b>
Enter Retirement Account Value: $ <b>64548.00</b>
Enter Amount Withdrawn Yearly: $ <b>100000.00</b>
Enter Amount Withdrawn Yearly: $ <b>12000.00</b>
Enter Rate of Return: % <b>-1.5</b>
Enter Rate of Return: % <b>4</b>

   Beginning         Amount       Earnings           Ending     Year
     Balance      Withdrawn                         Balance
------------     ----------     ----------     ------------     ----
$   64548.00     $ 12000.00     $  2101.92     $   54649.92        1
$   54649.92     $ 12000.00     $  1706.00     $   44355.92        2
$   44355.92     $ 12000.00     $  1294.24     $   33650.15        3
$   33650.15     $ 12000.00     $   866.01     $   22516.16        4
$   22516.16     $ 12000.00     $   420.65     $   10936.81        5
</pre>

NOTE: It is possible that if you earn more interest on your money than
you withdraw each year, your program will never end. I will not test
this condition. When you retire, this is a very nice problem to have and
very doable!!!!

**To complete this assignment you must submit the following:**

1.  **An electronic Solution of your program on GitHub**

    a.  You are to click on the Assign03 GitHub Assignment Link on
        Moodle to accept this assignment as we've done in lab. Once
        accepted, code up a complete solution to the above assignment
        specification. Your complete solution is to be pushed to GitHub
        no later than the date and time specified above for your
        specific section. I will only grade your solution from the
        proper location on GitHub.

    b.  Pay attention to the example output above. Your program's output
        must look **exactly** like the example output! The spacing and
        newlines in your output must match exactly.

    c.  Make sure that your program compiles and runs correctly with no
        errors and no warnings. If you get any errors, double check that
        you typed everything correctly. Be aware that C++ is
        case-sensitive.

2.  **An electronic copy of your program is to be placed on Moodle**

    a.  See Lab01 for producing a pdf of your complete program. Once you
        have produced the pdf of your program and named the pdf your
        **punetid**, drop the pdf in the Assign03 folder on Moodle.

    b.  The pdf must be in the drop folder on Moodle by the time and day
        specified above. Anything submitted after that will be
        considered late.

> **Good luck! And remember, if you have any problems, come and see
> straight away.
