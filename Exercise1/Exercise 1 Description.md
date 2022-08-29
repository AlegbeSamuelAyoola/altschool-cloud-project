-----------------------
Excercise 1 Description
-----------------------

# etc/group (etc_group due to windows file naming rules)
- The groups admin, support, and engineering were created as groups.
- The command used to create the groups was "addgroup"

# etc/passwd (etc_passwd due to windows file naming rules)
- The users User1, User2, User3 were created and added to the groups admin, support, and engineering in that order respectively.
- The command used to create the users was "useradd".
- The command used to add the users to their respective groups was "usermod -a -G"

# etc/sudoers (etc_sudoers due to windows file naming rules)
- Inorder to generate an SSH key in the admin group, it had to be given root privileges. and that was done by editing the sudoers file with "visudo".
- The line of code added to the sudoers file was "%admin ALL=(ALL) ALL