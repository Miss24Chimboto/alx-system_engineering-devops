19. su betty - Switching a user from current to betty
20. whoami- Who am I command. Prints the effective username of the current user
21. chown betty hello- Changing file ownership from to betty
22. touch- Create an empty file
23. chmod u+x hello - Execute permissions to owner of the file hello
24. chmod ug+x,o+r hello - adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
25. chmod ugo+x hello- adds execution permission to the owner, the group owner and the other users, to the file hello
26. chmod 007 hello- Owner: no permission at all, Group: no permission at all, and Other users: all the permissions
27. chmod 753- -rwxr-x-wx
28. chmod -R +111 */- script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
29. mkdir -m 751 my_dir- script that creates a directory called my_dir with permissions 751 in the working directory
30. chgrp school hello- changes the group owner to school for the file hello
