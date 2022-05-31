0. Script that prints “Hello, World”, followed by a new line to the standard output.
1. echo \"\(Ôo\)\' - script that displays a confused smiley "(Ôo)'
2. cat /etc/passwd- script that displays the content of the /etc/passwd file
3. cat /etc/passwd /etc/hosts- display the content of /etc/passwd and /etc/hosts
4. tail -n 10 /etc/passwd Display the last 10 lines of /etc/passwd
5. head -n 10 /etc/passwd- Display the first 10 lines of /etc/passwd
6. head -n 3 iacta | tail -n 1Write a script that displays the third line of the file iacta
7. echo "Best School" | cat > '\*\\'\''"Best School"\'\''\\*$\?\*\*\*\*\*:)'-script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School
8. ls -la > ls_cwd_content -script that writes into the file ls_cwd_content the result of the command ls -la
9. tail -n 1 iacta >> iacta -script that duplicates the last line of the file iacta 
10. find . -name "*.js" -type f -delete- a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
11. find . -mindepth 1 -type d | wc -l-script that counts the number of directories and sub-directories in the current directory.
The current and parent directories should not be taken into account
Hidden directories should be counted
12. ls -t | head-script that displays the 10 newest files in the current directory.
13. sort | uniq -u- Create a script that takes a list of words as input and prints only words that appear exactly once. Words should be sorted
14. grep root /etc/passwd- Display lines containing the pattern “root” from the file /etc/passwd
15. grep -c bin /etc/psswd- Display the number of lines that contain the pattern “bin” in the file /etc/passwd
16. cat /etc/passwd | grep -A 3 "root" -Display lines containing the pattern “root” and 3 lines after them in the file  /etc/passwd
17. grep -v bin /etc/passwd -Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
18. grep ^[[:alpha:]]  /etc/ssh/sshd_config - Display all lines of the file /etc/ssh/sshd_config starting with a letter.
19. tr 'Ac' 'Ze'  - Replace all characters A and c from input to Z and e respectively.
20. tr -d 'Cc'  -script that removes all letters c and C from input
21. rev -script that reverse its input
22. cut -d":" --fields=1,6 /etc/passwd | sort -Write a script that displays all users and their home directories, sorted by users
