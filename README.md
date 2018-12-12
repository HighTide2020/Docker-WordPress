

# Simple & fast spin up for monorepo single developer WordPress Dev using Docker for local development
Has that MAMP feel on tradtional LAMP stack.
Easy to intergrate web hooks or code deploy to AWS or DO by making deployment branch and rewriting URLs and wp-config file exculsive to deployment branch.

SSH in to Docker shell to install WP-CLI in need be also can use locally installed composer and WP-CLI instead

Docker compose file for a Wordpress project. Sets up wordpress, MySQL, phpmyadmin.

mkdir
cd && Docker-compose up

and Boom!

creates a site running at http://localhost:8080
phpmyadin http://localhost:8082
