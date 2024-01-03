# BetterWindows
A collection of .bat files that I use on a daily basis 
if you want to know what each file does before dropping them in system32,<br> see [documentation](https://github.com/isaaclins/BetterWindows/blob/main/README.md#documentation)


# Installation
```bash
git clone https://github.com/isaaclins/BetterWindows.git
```
drag & drop all desired batch files into system32 so you can access them from every directory
done!


# Documentation
this is a simple documentation written by hand for each file.

## kill.bat
Kill the PID that uses port X
### Examples:
```
C:\Users\exampleuser\Desktop>kill
Enter the port number you would like to kill: XXXX
No process found running on port XXXX.

Press any key to continue . . .
```
OR
```
C:\Users\exampleuser\Desktop>kill
Enter the port number you would like to kill: XXXX
Killing process with PID YYYY...
Process terminated.

Press any key to continue . . .
```

## ls.bat
This just does what the linux ls does
### Example:
```
C:\Users\exampleuser\Desktop\dockerexample>ls
docker-compose.yml
dockerfile
```

## pwdg.bat
this generates a string that gets copied to the clipboard. the password is not shown to the user.
it has following customisable characters:
- Length (Number)
- Capitalized characters (y/n)
- Symbols (y/n)
- Numbers (y/n)
### Example:
```
C:\Users\exampleuser\Desktop\dockerexample>pwdg

how many characters? 12
do you want capital letters? (y/n) y
do you want symbols? (y/n) y
do you want numbers? (y/n) y

PASSWORD WAS COPIED TO CLIPBOARD
enjoy!
made by isaaclins

```
