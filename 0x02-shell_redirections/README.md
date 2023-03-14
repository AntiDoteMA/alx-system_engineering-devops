0-hello_world : echo -e 'Hello, World' -> display "Hello, World" in terminal

1-confused_smiley : echo "\"(Ôo)'" -> display a confused smiley face in terminal

2-hellofile : cat /etc/passwd -> display contents of /etc/passwd file in terminal

3-twofiles : cat /etc/passwd /etc/hosts -> display contents of /etc/passwd and /etc/hosts files in terminal

4-lastlines : tail -n 10 /etc/passwd -> display last 10 lines of /etc/passwd file in terminal

5-firstlines : head -n 10 /etc/passwd -> display first 10 lines of /etc/passwd file in terminal

6-third_line : head -n 3 iacta | tail -n 1 -> display the third line of iacta file in terminal

7-file : echo 'Best School' > '\*\\'"'"'"Best School"'"\'\\\\*$\\?\\*\\*\\*\\*\\*:)" -> create a file named "*\'\"Best School\"\'\\*$?****:)" with "Best School" as its contents

8-cwd_state : ls -la > ls_cwd_content -> list the contents of the current directory with detailed information and save it in a file named ls_cwd_content

9-duplicate_last_line : tail -n 1 iacta >> iacta -> duplicate the last line of iacta file and append it to the end of the file

10-no_more_js : find . -name '*.js' -type f -delete -> find and delete all files with .js extension in the current directory and its subdirectories

11-directories : find . -mindepth 1 -type d | wc -l -> count the number of directories in the current directory and its subdirectories

12-newest_files : ls -t | head -n 10 -> list the 10 most recently modified files in the current directory and its subdirectories

13-unique : sort | uniq -u -> display only unique lines in a file

14-findthatword : grep root /etc/passwd -> search for the word "root" in /etc/passwd file and display the matching lines

15-countthatword : grep bin /etc/passwd | wc -l -> count the number of times the word "bin" appears in /etc/passwd file

16-whatsnext : grep -A 3 'root' /etc/passwd -> display the line containing "root" in /etc/passwd file and the next 3 lines

17-hidethisword : grep -v bin /etc/passwd -> display all lines in /etc/passwd file except those containing the word "bin"

18-letteronly : grep '^[[:upper:]]\|^[[:lower:]]' /etc/ssh/sshd_config -> display only the lines in /etc/ssh/sshd_config file that start with an uppercase or lowercase letter

19-AZ : tr Ac Ze -> replace all "A" characters with "Z" characters and all "c" characters with "e" characters in the input

100-empty_casks : find . -empty -printf '%f\n' -> find and display the names of all empty files and directories in the current directory and its subdirectories

101-gifs : find -type f -name "*.gif" | rev | cut -d "/" -f 1 | cut -d '.' -f 2- | rev | LC_ALL=C sort -f -> find all files with .gif extension in the current
