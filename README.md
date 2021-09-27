I have been working on and brainstorming what my ideal dev setup might look like. Docker has really pulled me in and I would love to get your input on what you would like to add to a new base image. Any essential PHP extensions or helper apps you guys use that you think would useful to add?




Here are the specs I'm shooting for right now:

# Core services
- Nginx
- PHP
- MySQL

# Additional Drupal Stuff
- Apache Solr
- Redis

# PHP Extensions
- XDebug
- Zend OPCache
- bcmath bz2 calendar iconv intl mbstring mysqli opcache pdo_mysql pdo_pgsql pgsql soap zip gd ldap exif redis

# GUI Apps
- OpCache GUI - https://github.com/PeeHaa/OpCacheGUI
- PHPRedMin - https://github.com/sasanrose/phpredmin
- Adminer - https://www.adminer.org/
- Pimp my Log - http://pimpmylog.com/
- MailHog - https://github.com/mailhog/MailHog

# References
- http://devilbox.org/
- https://www.drupalvm.com/
- https://github.com/drud/ddev

If there are any useful existing project internally or open source I should check out for inspiration let me know.
