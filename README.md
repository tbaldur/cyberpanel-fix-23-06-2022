# cyberpanel-fix-23-06-2022
To who updated during 23/06/2022 and now has the "phpMyAdmin" page at the domain.tld:8090 login

phpMyAdmin was extracted to the "/usr/local/CyberCP/public" by mistake.

Fix: Delete the extra folders from "/usr/local/CyberCP/public" that belong to phpMyAdmin

1 - Open putty, paste command bellow and press enter.
2 - CTRL + F5 at at cyberpanel login

rm -rf /usr/local/CyberCP/public/doc
rm -rf /usr/local/CyberCP/public/examples
rm -rf /usr/local/CyberCP/public/js
rm -rf /usr/local/CyberCP/public/libraries
rm -rf /usr/local/CyberCP/public/locale
rm -rf /usr/local/CyberCP/public/setup
rm -rf /usr/local/CyberCP/public/sql
rm -rf /usr/local/CyberCP/public/templates
rm -rf /usr/local/CyberCP/public/themes
rm -rf /usr/local/CyberCP/public/vendor
rm -f /usr/local/CyberCP/public/babel.config.json
rm -f /usr/local/CyberCP/public/ChangeLog
rm -f /usr/local/CyberCP/public/composer.json
rm -f /usr/local/CyberCP/public/composer.lock
rm -f /usr/local/CyberCP/public/config.sample.inc.php
rm -f /usr/local/CyberCP/public/CONTRIBUTING.md
rm -f /usr/local/CyberCP/public/favicon.ico
rm -f /usr/local/CyberCP/public/index.php
rm -f /usr/local/CyberCP/public/LICENSE
rm -f /usr/local/CyberCP/public/package.json
rm -f /usr/local/CyberCP/public/print.css
rm -f /usr/local/CyberCP/public/README
rm -f /usr/local/CyberCP/public/RELEASE-DATE-5.1.3
rm -f /usr/local/CyberCP/public/robots.txt
rm -f /usr/local/CyberCP/public/show_config_errors.php
rm -f /usr/local/CyberCP/public/url.php
rm -f /usr/local/CyberCP/public/yarn.lock
