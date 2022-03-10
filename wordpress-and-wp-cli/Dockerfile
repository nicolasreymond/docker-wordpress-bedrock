FROM wordpress:latest
RUN curl -o /usr/local/bin/wp https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar
RUN chmod +x /usr/local/bin/wp
RUN rm -f /var/www/html/.htaccess
RUN ln -s config/.htaccess /var/www/html/