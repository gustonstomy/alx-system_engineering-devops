echo "Hello, World" => prints hello tostandard output with new line

echo "\"(Ôo)'" => script that displays a confused smiley "(Ôo)'

cat /etc/passwd => Display the content of the /etc/passwd file

cat /etc/{passwd,hosts} => Display the content of /etc/passwd and /etc/hosts

tail -n 10 /etc/passwd => Display the last 10 lines of /etc/passwd

head -n 10 /etc/passwd => Display the first 10 lines of /etc/passwd

head -n 3 iacta | tail -n 1=> displays the third line of the file iacta

echo "Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\) => displaying "\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)"

ls -ls > ls_cwd_content => writes into the file ls_cwd_content the result of the command ls -la
 duplicates the last line of the file iacta

tail -n 1 iacta >> iacta => duplicates the last line of the file iacta

find . -type f -name "*.js" -delete => deletes all the regular files (not the directories) with a .js

find . -mindepth 1 -type d | wc -l => counts the number of directories and sub-directories in the current directory.

ls -t | head => Create a script that displays the 10 newest files in the current directory

sort | uniq -u => takes a list of words as input and prints only words that appear exactly once

grep "root" /etc/passwd => Display lines containing the pattern “root” from the file /etc/passwd

grep "bin" /etc/passwd | wc -l => Display the number of lines that contain the pattern “bin” in the file /etc/passwd

grep -A 3 "root" /etc/passwd => Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd

 grep -v "bin" /etc/passwd => Display all the lines in the file /etc/passwd that do not contain the pattern “bin"
grep "^[[:alpha:]]" /etc/ssh/sshd_config => Display all lines of the file /etc/ssh/sshd_config starting with a letter

tr Ac Ze => Replace all characters A and c from input to Z and e respectively.

tr -d 'cC' => script that removes all letters c and C from input

rev => Write a script that reverse its input

 cut -d":" --fields=1,6 /etc/passwd | sort => Write a script that displays all users and their home directories, sorted by users

find . -empty -printf "%f\n" => finds all empty files and directories in the current directory and all sub-directories

 find . -type f -name "*.gif" -printf "%f\n"| rev | cut -d '.' -f2- | rev | LC_ALL=C sort -f => lists all the files with a .gif extension in the current directory and all its sub-directories

echo -ne $(cut -c-1 | tr -d '\n')'\n' => script that decodes acrostics that use the first letter of each line.

tail -n +2 | cut -f1 | sort | uniq -c | sort -nr | head -11 | tr -s ' ' | cut -d' ' -f3 => script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests
