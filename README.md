# Bash Scripts
This repo has useful bash scripts for automating processes

## empty trash
Used by crontab to empty trash bin out without navigating there 

```
chmod +x ~/[file_path]/empty_trash.sh
crontab -e
00 21 * * * cd ~/[file_path] ./empty_trash.sh
```
make certain file is executable and edit crontab to set job schedule and commandto execute

