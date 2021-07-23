FROM wordpress:5.8.0-apache



##########################################################
###  Custom Build ########################################
#                                                        #
#  This was an initial attempt at building a custom WP   #
#  instead of using the wordpress docker image           #
#                                                        #
##########################################################
#RUN apt update
#RUN apt upgrade -y

# install WP-CLI
#RUN curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar
#RUN chmod +x wp-cli.phar
#RUN mv wp-cli.phar /usr/local/bin/wp

# Run WP-CLI install site as "www-data" user
#RUN wp core download --allow-root --version=5.8
#RUN wp config create --allow-root --skip-check --dbname=wordpress_db --dbuser=wordpress_user --dbpass=wordpress_password --dbhost=db:3306
#RUN wp core install --allow-root --url=example.com --title=Example --admin_user=supervisor --admin_password=strongpassword --admin_email=info@example.com