# Temperature Monitor and Alarm Checker

## What it does
My program collects 5 temperature readings from a factory machine and finds the highest, lowest and average. It also checks if any reading is too hot.

## How to run it
python temperature_monitor.py

## Sample output
Enter temperature 1 (in C): 45
Enter temperature 2 (in C): 75
...
Highest: 75 C
Lowest: 45 C
Average: 62.0 C
75 C -> DANGER! Machine too hot, shut down!

## My own twist
I added a daily report that counts how many times the machine was hot and gives advice to call technician or continue work. I also added overall status based on average.

## What I learned
I learned how to use list to store values, and how to use max(), min() and sum() to get results.

## Author
Simon Ayomipo , ND1 Mechatronics, YABATECH
