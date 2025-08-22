# slstatus
Triet's version of suckless slstatus. It shows status bar which can include battery percentage, date, time, cpu usage, ram usage, disk space, etc. This tool is useless unless you are building your own Desktop Environment (DE). In this case, Triet uses slstatus together with dwm to replace a regular DE.

![image](https://github.com/user-attachments/assets/19e9150f-b612-422a-a3ba-1e7b07697edc)

Source code: https://tools.suckless.org/slstatus/

## Current feature
1. Date
2. Time
3. Battery percentage

## Download
```git clone https://github.com/triet228/slstatus.git```
## Installtion
Go to cloned directory
```cd slstatus``` 
Install
```sudo make clean install```
Uninstall
```sudo make uninstall```

## Run slstatus
Temporary run in terminal ```slstatus```

Run in background ```slstatus &```

Kill slstatus in background ```pkill slstatus```
## Recommend usage
Run with dwm inside ~/.xinitrc
```
slstatus &

exec dwm
```




