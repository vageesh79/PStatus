# PStatus
Ping of internal servers and port check of related services with a Web front end.

# Requirements
Web server running PHP (7 is tested.. 5 should work fine)

MYSQL Database (See pstatus.sql for structure)

uptime.php needs to be run as a cron timer - */10 * * * * /usr/bin/php /var/www/html/status/uptime.php

# WIP

21.05.17 - Admin page : So far you can add a server, smart device and a service.. the rest needs to be done in SQL at the moment.
Need to add a row to the uptime table when a server is added.

# Planned
* Run in backgroud to build stats of uptime
* Delete Devices etc..
* Edit Devices etc..
* Display uptime data including last uptime / downtime
* Reset uptime data


# Done
* Add auto refresh rate
* Add services for each parent server
* Add Smart device controls

# Screenshot
![Alt text](/../screenshots/pstatus.png?raw=true "Main Screen")
![Alt text](/../screenshots/pstatus2.png?raw=true "Service Screen")

# Credit 
Original idea sparked by https://gist.github.com/k0nsl/733955a3c3093832de49
