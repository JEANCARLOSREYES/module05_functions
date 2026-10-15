# debug_log.md
# Author: Jean Carlos Reyes-Munoz

## Bug 1
Error type: Key error
File + line: week8_buggy.py + line 4
What the error means: Error means a word was misspelled (amout)
What I told the duck: get_total(records) takes a list of all records. total = 0 means starting total at zero. for rec in records means going through each record one at a time. total+= rec['amount'] means adding the amount to the total of each record. return total returns the total amount of the sum.
What I tried: I tried fixing the the key error with the misspelled word "amout" to "amount". I typed out print(f"DEBUG: rec = {rec}") to spot out and locate the bug/error.
How I fixed it: I was able to fix the error by correcting the word to have it spelled properly which fixed that line which was the word amout to amount.

## Bug 2
Error type: Type error
File + line: week8_buggy.py + line 17
What the error means: Python can't compare int to str and with the line 17, 1000 was in quotations '1000' which made it a string and cannot compare it to the integers to the other records that did not have quotations.
How I fixed it: I removed the quotations and added the int before 1000 so int(1000) so Python can read it as an integer.

## After Fixing Both Bugs
Final output: Total: $5150.00 across 3 records and true
Did pytest pass? Yes all 5 tests passed.

## AI Literacy Reflection
Did I use AI? Yes
If yes -- exact prompt I used: "how do i explain to the duck what get total is"
What AI explained: AI explained the get_total process of starting from zero and how the amounts add up together to get a total sum.
What I changed myself: I corrected the amout to amount in the first record and also changed the '1000' to the int 1000.
Can I explain every fixed line: Not yet fully

## What I learned
I learned that Python cannot match strings and integers and must be corrected so that there is no type error. I also learned that the keys must match exactly or there will be a key error.