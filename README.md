# Linux-Crontab

Linux Crontab Format

```
MIN HOUR DOM MON DOW CMD
```

Field	Description	Allowed Value

```
MIN	Minute field	0 to 59
HOUR	Hour field	0 to 23
DOM	Day of Month	1-31
MON	Month field	1-12
DOW	Day Of Week	0-6
CMD	Command	Any command to be executed.

```

To view your crontab entries type crontab -l from your unix account as shown below.

```
 $ crontab -l
 
arun:~ arun$ crontab -l
crontab: no crontab for arun
```

[Note: This displays crontab of the current logged in user]

##We can use ```at``` as well

