# Ceasar Cipher Encoder Implementatiosn #

########################################

In both implementations the key represents the ammount of spaces to shift the characters, currently they also do not support the conversion of special characters,
The main struggles for me in this project were the case insensitivity, which was much easier after finding the Ctype library, and the memory allocation for input functions as I have not dealt with this much before, due to the guardrails provided in the first few weeks of the CS50 course where I am learing C.

Of note is the non-optimal memory allocation stratergy in the C version of this program for the aformentioned reasons.