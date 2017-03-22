rmssh
=

Allows you to fire off multiple ssh commands and will process the output of those commands.
Allows you to filter the contents of the commands.

Example
===

node rmssh.js --filter=cron \
"me@server tail -f /server/cron/log/file"

Commands
===

--filter - String to filter by.
--user - Username for ssh connection (will prompt if not supplied)
--password - Password for ssh connection (will prompt if not supplied, silent)