## INSTALLATION GUIDE LINUX
Clone the repository to home folder

Clone or download the repository to home folder

Run this in terminal
```
nano ~/.bashrc
```

Add this to the bashrc file
```
if [ -f ~/custom-aliases ]; then
    . ~/custom-aliases/aliases
fi
```

Apply changes immediately. Run this from terminal
```
source ~/.bashrc
```








