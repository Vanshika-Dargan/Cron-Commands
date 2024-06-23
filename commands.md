

service cron status

service cron start

service cron stop

service cron restart



<!-- List all cron jobs -->
crontab -l

<!-- To add a cron job -->

crontab -e

\* * * * * echo 'Hello' >> /mnt/e/crons/output.txt