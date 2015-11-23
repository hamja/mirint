#How to use the MIRINT script.

# Introduction #

MIRINT script will read MIR files produced by Galileo GDS system into a database.


# Details #

To use this script:

1. Install MySQL database or use an AMP (e.g. http://portableapps.com/apps/development/xampp).

2. Install the MYSQL .Net driver available from  https://mysql.com/products/connector/

3. Run the create\_mirint\_mysql.sql script to create the tables for MIRINT schema.

4. Edit the Mirint\_mysql.vbs script and update the paths and MySQL database connection parameters.