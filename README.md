libgraph
===========

Author: Robert Mayr <robyduck@fedoraproject.org>

Wordpress theme for Libre Graphics Meeting 2014

This README is a short guide to install the Wordpress Libre Graphics Meeting
site locally for testing
Theme: expound rewritten by Robert Mayr

================================================================================

IMPORTANT: You need a running webserver (LAMP) to deploy the site locally,
please refer to the official documentation to install apache, mysql, php and
phpmyadmin.

================================================================================

INSTALLATION

1) FILES

Place all the files, except libgraphdb.sql, in your Document Root. Default is
in /var/www/html. Open a terminal and go to you Document Root, assigning chmod
777 do you content directory:

 # cd /var/www/html/libgraph
 # chmod -R 777 wp-content/

2) DATABASE

Open phpmyadmin and create a new database called libgraphdb with utf_8_unicode.
Click on the database and import the libgraphdb.sql.

Note: you can use also the command line to do this.

3) RUN IT

Open http://localhost/libgraph

If all went fine you should be able to access the site.
To login as admin use:
 user: admin
 pass: gnokii2014
