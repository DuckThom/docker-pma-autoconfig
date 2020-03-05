phpmyadmin: /docker-entrypoint-pma.sh php-fpm
dockergen: docker-gen -watch -notify "killall php-fpm" /pma-config.tmpl /etc/phpmyadmin/config.inc.php
