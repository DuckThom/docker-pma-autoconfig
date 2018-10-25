phpmyadmin: /run.sh supervisord -n
dockergen: docker-gen -watch -notify "killall php-fpm" /pma-config.tmpl /etc/phpmyadmin/config.inc.php
