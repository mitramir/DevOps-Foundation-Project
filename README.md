# Install rsync:
```
$ sudo apt-get install rsync
```

Run rsync command to make local back up
```
$ rsync -av --delete dir1/ dir2/
```

To edit the cron table file 
```
$ crontab -e
```

Install zip
```
$ apt-get install zip
```

Edit the cron table file to run the backup script every day midnight and put backup into azip file.
```
$ zip ZippedFiles/archive.zip /dir1/ && rsync -av --delete ZippedFiles/ /dir2/
```


