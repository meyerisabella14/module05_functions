# debug_log.md
# Author: Isabella Meyer

## Bug 1
Error type: KeyError: 'amount'
File + line: week8_buggy.py, line 12
What the error means: Python could not find the key 'amount' in a dictionary.
What I told the duck: The function starts at zero, loops through each record, adds its amount to the total, and returns the total.
What I tried: I ran the code, read the traceback, and checked the get_total function to understand where it failed.
How I fixed it: I used print debugging to find that "amount" was misspelled as "amout" in the first record. I corrected the spelling and removed the DEBUG print.
## Bug 2
Error type: TypeError
File + line: week8_buggy.py, line 18
What the error means: Python cannot compare a number with a string.
How I fixed it: Changed "1000" to 1000 so both values are numbers.
## After Fixing Both Bugs
Final output:
Total: $5150.00 across 3 records
True

Did pytest pass? Yes - 5 passed

## AI Literacy Reflection
Did I use AI? Yes

Exact prompt I used: "Where do I add the first thing—in terminal?"

What AI explained: AI helped me understand where to enter my code and how to follow the debugging steps.

What I changed myself: I edited my Python file, corrected the errors, and ran pytest to check my work.

Can I explain every fixed line? Yes
## What I learned
I learned how to identify errors in Python and correct mistakes in my code. I also got more comfortable using VS Code and running tests.