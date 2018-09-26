phpmyadmin: /run.sh supervisord -n
dockergen: docker-gen -watch -notify "killall php-fpm7" /pma-config.tmpl /etc/phpmyadmin/config.inc.php
