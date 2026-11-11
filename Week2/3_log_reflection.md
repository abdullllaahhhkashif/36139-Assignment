BEFORE CLEANING

There were 97 rows
There was 1 price missing
Some items were entered in lower case

AFTER CLEANING

Rows became 96
Missing prices count increased from 1 to 2
Names were standardized

REFLECTION

My cleaning approach differed from what the AI first suggested, especially when it came to handling missing values and outliers. Instead of deleting those rows, I decided to convert the weird 9999 placeholder and the missing entry into standard NaN values. This turned out to be a much better call because dropping them entirely would have messed up the 12-week timeline of our dataset. If I hadn't checked things carefully on my own, I would have totally missed that hidden duplicate at row 96, which secretly inflated the count to 97 and would have thrown off all our price averages.
