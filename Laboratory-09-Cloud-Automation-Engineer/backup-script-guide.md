# Backup Script & Cron Reference

## Full backup.sh Source Code
#!/bin/bash
# Automated Backup Script for CloudNova Technologies

SOURCE_DIR="app-data"
BACKUP_DIR="backups"
TIMESTAMP=$(date +"%Y%m%d_%H%M%S")

echo "Starting automated backup process..."

# Create target folder if it does not exist
mkdir -p $BACKUP_DIR

# Package and compress source into timestamped archive
tar -czf $BACKUP_DIR/backup_$TIMESTAMP.tar.gz $SOURCE_DIR

echo "Backup completed successfully at $TIMESTAMP!"

## What Did the chmod +x Command Do?
The command chmod +x backup.sh modifies file permissions to mark the script as executable, so Linux recognizes it as a runnable program instead of plain text. Without this change, the system blocks direct execution as a security measure and returns a permission error.

## Cron Schedule
cron
0 2 * * * /root/backup.sh

The five time fields mean:

| Field | Value | Meaning |
|---|---|---|
| Minute | 0 | At minute zero |
| Hour | 2 | At 2 AM |
| Day of Month | * | Every day of the month |
| Month | * | Every month |
| Day of Week | * | Every day of the week |

The backup script runs automatically at 2:00 AM every day.
