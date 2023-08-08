0 alias ls="rm *" => Create a script that creates an alias.

1 echo "hello" $USER => script that prints hello user, where user is the current Linux user.

2 PATH=$PATH:/action => Add /action to the PATH. /action should be the last directory 

3 find -mindepth 1 -type d | wc -l => script that counts the number of directories in the PATH

4 printenv => script that lists environment variables

5 set =>  script that lists all local variables and environment variables, and functions.

6 BEST="School" => script that creates a new local variable.

7 BEST="School" export BEST =>   script that creates a new global variable.

8 echo $((128+TRUEKNOWLEDGE)) => script that prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE

9 echo $((POWER/DIVIDE)) => script that prints the result of POWER divided by DIVIDE, followed by a new line.

10 echo $((BREATH**LOVE)) => script that displays the result of BREATH to the power LOVE

11 echo $((2#$BINARY)) =>  script that converts a number from base 2 to base 10.

12 echo {a..z}{a..z} | tr ' ' '\n' | grep -v "oo" => script that prints all possible combinations of two letters, except oo (a-z)

13 printf "%.2f\n" $NUM =>  script that prints a number with two decimal places, followed by a new line.

14 printf "%x\n" $DECIMAL => script that converts a number from base 10 to base 16.

15 tr 'A-Za-z' 'N-ZA-Mn-za-m' => encodes and decodes text using the rot13 encryption. Assume ASCII.

16 paste -d, - - | cut -d, -f1 => script that prints every other line from the input, starting with the first line.

17 'water' '01234'))) + $((5#$(echo $STIR | tr 'stir.' '01234'))))) | tr '01234567' 'bestchol') => stored in the environment variables WATER and STIR and prints the result.

