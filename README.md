# BashScriptingProgram

This Repo is dedicated to my Learning of Bash Scripting

On 05-Apr-2025, I am going to write few programs



To Schedule the task use cron tab. Below is the steps
crontab -l
crontab -e
0 21 * * * echo "Welcome to cron" >> /tmp/echo.txt
crontab -l

#! /bin/bash
# print the current date time
date
# print the disk free statistics
df -h

chmod u+x diskusage.sh
./diskusage.sh

crontab -e
0 0 * * * /home/project/diskusage.sh >>/home/project/diskusage.log
crontab -l
crontab -r
crontab -l

