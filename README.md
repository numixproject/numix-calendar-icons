# numix-calendar-icons
This script will change the calendar icons in the numix theme(s), to represent the current date.

# Usage
1. Download this script and place it somewhere.
2. Download and install a cron daemon (preferably `anachron` or `fcron` or the standard `cron` daemon if your computer is running 24/7)
3. -When using `anachron` symlink your scirpt to `/etc/cron.daily` (this will ensure that the script is run every day)
   -When using `fcron` run `fcrontab -e` and add this line `2 0 * * * /path/to/script`
   -When using the standard `cron` run `crontab -e` and add this line `2 0 * * * /path/to/script`
4. Enjoy!
