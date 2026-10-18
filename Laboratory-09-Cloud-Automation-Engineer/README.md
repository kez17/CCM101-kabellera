# The Cloud Automation Engineer

## Mission Overview
This mission places the Cloud Automation Engineer role into practice to remove human error from recurring tasks. A client experienced permanent data loss because scheduled backups were forgotten, so the work focuses on building a script that packages and saves files automatically, then configuring Cron to run the process daily at 2:00 AM — fully independent and consistent.

## Objectives
- Understand Bash script fundamentals including variables and command flow
- Create and edit executable scripts using the nano terminal editor
- Apply execution permissions through the chmod command
- Learn crontab scheduling structure and time-field meaning
- Document code and configurations clearly using Markdown
- Finalize the complete Cloud Computing portfolio on GitHub

## Commands Executed
mkdir app-data
echo "This is critical client data." > app-data/data.txt
nano backup.sh
./backup.sh
chmod +x backup.sh
./backup.sh
ls -l backups/
crontab -l
env EDITOR=nano crontab -e
crontab -l
## Skills Learned
- Building Bash scripts that generate timestamped compressed archives
- Recognizing the purpose of the shebang line at the start of scripts
- Managing Linux file permissions to control program execution
- Applying crontab syntax for reliable task scheduling
- Transitioning from manual steps to scalable, repeatable automation
