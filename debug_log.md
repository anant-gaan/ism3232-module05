# debug_log.md
# Author: [Your Name]

## Bug 1
Error type: KeyError: 'amount'
File + line: week8_buggy.py, line 12
What the error means: Python tried accessing a key named 'amount' that does not exist.
What I told the duck: the loop goes through each record and tries to add 'amount' to the total. Except that key for 'record' does not exist. 
What I tried: I added a debug print statement where the error was (line 12). When I ran it there was a spelling error in the first record.
How I fixed it: I changed 'amout' to 'amount' in the first record, removed the debug print statement, and ran the program again.

## Bug 2
Error type: TypeError -> issue with int vs str 
File + line: week8_buggy.py, line 16
What the error means: Python is trying to compare an integer (amount) with a string ('1000') using the > operator.
How I fixed it: I removed the quotation marks around '1000' to change it from a string to an integer

## After Fixing Both Bugs
Final output: Total: $5150.00 across 3 records; True
Did pytest pass? Yes

## AI Literacy Reflection
Did I use AI? Yes
If yes -- exact prompt I used: The instructions explictly say attempt to debug alone first without any AI assistance. Support me through this lab without violating that 'rule'.
What AI explained: Did not need for bug 1 or 2; I had AI explain to me all the pytests and walk me through getting everything over to Github.
What I changed myself: In bug 1 I fixed the spelling error, and in bug 2 I changed 1000 to an int from str
Can I explain every fixed line? Yes

## What I learned
I learned that a KeyError is when python tries accessing a dictionary key that does not exist, and a TypeError is when incompatible data types are used together.