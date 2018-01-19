# Catalog-Server (Udacity Course)

## Author: Corey Poff

## Server Access

The site is accessible through a browser via:
 - IP: 18.217.102.26
 - SSH port: 2200
 - URL to app: http://18.217.102.26

The application software installed on the Amazon web server is found in the github repository: https://github.com/coreyjpoff/Catalog-Server

I also installed the following software:
 - Apache
 - PostgreSQL
 - git

The following configuration changes were made on the server:
 - Updated all currently installed packages
 - Changed the default SSH port from 22 to 2200
 - Enabled UFW to only allow connections from ports 2200 (SSH), 80 (HTTP), and 123 (NTP)
 - Account named grader with sudo access (SSH key pair info in submission notes)
 - Changed the local timezone to UTC
 - Installed software listed above (Apache, PostgreSQL, and git)
 - Created catalog database and PosgreSQL user
 - Cloned and setup Item Catalog application, as noted above

The following Python 2.7 libraries were installed:
 - flask
 - oauth2client
 - psycopg2
 - httplib2

The following resources were used:
 - Flask, apache, python, and PostgreSQL documentation
 - Ubuntu documentation
 - AWS and Lightsail documentation
 - A few stackoverflow posts about the above programs and packages
