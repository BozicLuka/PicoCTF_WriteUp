# Description
Want to play a game? As you use more of the shell, you might be interested in how they work! Binary search is a classic algorithm used to quickly find an item in a sorted list. Can you find the flag? You'll have 1000 possibilities and only 10 guesses. Cyber security often has a huge amount of data to look through - from logs, vulnerability reports, and forensics. Practicing the fundamentals manually might help you in the future when you have to write your own tools!

# Solution
First we need to connect to the server with given info. Now we can start guessing.
*Lets say our number is 216
*We start with 500, since it is the middle number of 0-1000. We get "Lower" message.
*We continue with 250, middle of 0-500. We get "Lower" message.
*We continue with 125, middle of 0-250. We get "Higher" message.
*We continue with 188, middle of 125-250. We get "Higher" message.
*We continue with 218, middle of 188-250. We get "Lower" message.
*We continue with 203, middle of 188-218. We get "Higher" message.
*We continue with 211, middle of 203-218. We get "Higher" message.
*We continue with 215, middle of 211-218. We get "Higher" message.
*We continue with 217, middle of 215-218. We get "Lower" message.
*We continue with 216, middle of 215-217.

picoCTF{g00d_gu355_de9570b0}
