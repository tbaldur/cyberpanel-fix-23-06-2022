# cyberpanel-fix-23-06-2022
To who updated during 23/06/2022 and now has the "phpMyAdmin" page at the domain.tld:8090 login

phpMyAdmin was extracted to the "/usr/local/CyberCP/public" by mistake.

Fix: Delete the extra folders from "/usr/local/CyberCP/public" that belong to phpMyAdmin

1 - Use the fix.sh or run its commands individually.
