![Shell Cheat Sheet](https://miro.medium.com/max/720/1*F20fM4cjs0LqvbaZ8BN2oA.jpeg)
# Shell, init files, variables and expansions
Each file here is a script that execute a basuc command from the shell. 
* Task 0 Create a script that creates an alias. alias  ls="rm *"
* Task 1 Create a script that prints hello user, where user is the current Linux user. **echo hello $USER**
* Task 2 Add /action to the PATH. /action should be the last directory the shell looks into when looking for a program. **export PATH=$PATH:/action**
* Task 3 Create a script that counts the number of directories in the PATH. **echo $PATH | tr ":" "\n" | wc -l**
* Task 4 Create a script that lists environment variables. **printenv**
* Task 5 Create a script that lists all local variables and environment variables, and functions. **set**
* Task 6 Create a script that creates a new local variable. **BEST="School"**
* Task 7 Create a script that creates a new global variable. **export BEST=School**
* Task 8 Write a script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE, followed by a new line. **echo $(( TRUEKNOWLEDGE + 128 ))**
* Task 9 Write a script that prints the result of POWER divided by DIVIDE, followed by a new line. **echo $(($POWER / $DIVIDE))**
* Task 10 Write a script that displays the result of BREATH to the power LOVE. **echo $(( BREATH ** LOVE))**
* Task 11 Write a script that converts a number from base 2 to base 10. **echo $((2#$BINARY))**
* Task 12 Create a script that prints all possible combinations of two letters, except oo. **echo {a..z}{a..z} | tr ' ' '\n' | grep -v 'oo'**
* Task 13 Write a script that prints a number with two decimal places, followed by a new line. **printf "%0.2f\n" "$NUM"**
* Task 14 Write a script that converts a number from base 10 to base 16. **printf "%x\n" $DECIMAL**
* Task 15 Write a script that encodes and decodes text using the rot13 encryption. Assume ASCII. **tr 'a-zA-Z' 'n-za-mN-ZA-N'**
* Task 16 Write a script that prints every other line from the input, starting with the first line. **perl -ne 'print if (++$x)%2'**
* Task 17 (Lets not talk about this one lol) Incomplete!!!

### Resources:

Lizbeth Garcia Lebron (Creator)

Proyects from September 26, 2022 - September 30, 2022
