# UdacityFinalReadMe

Objective:
To deploy an application previously written to an Ubuntu server along with various changes to the ports, users, and database.

Pertinent Information:
URL - http://34.202.236.163.xip.io
Port - 2200

Steps taken:
  1. Created Ubuntu server on Amazon Lightsail.
  2. Updated all packages.
  3. Changed port to 2200.
  4. Configured UFW to allow port 2200, 80 and 123.
  5. Configured Lightsail connections.
  6. Created new user 'grader' and give sudo permission.
  7. Created SSH key pair for user.
  8. Changed local timezone to UTC.
  9. Installed Apache and PostgreSQL.
  10. Installed git and used to clone my repository for the previous item catalog.

Python pip installs needed:
 * Oauth2client
 * Psycopg2
 * Requests
 * Flask
 * Sqlalchemy
 
