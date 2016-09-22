# sudo_without_entering_password
Steps to edit sudoers file to allows user to execute 'root' like commands


###  On the server where we want 'dpeuser' to execute commands as root.

dpeuser ALL=(ALL) NOPASSWD: ALL

### Debugging tips

Enter this at the end of the file
Or else this wont work.
