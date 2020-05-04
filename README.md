# sqldatabase
SQL Database

# Instructions
Download mySQL Community Server - https://dev.mysql.com/downloads/mysql/
Run installer
Write down temporary password
Open ‘MySQL’ in System Preferences and start the server
Configure command line to recognize ‘mysql’ command
echo ‘export PATH=/usr/local/mysql/bin:$PATH’ >> ~/.bash_profile
. ~/.bash_profile
mysql -u root -p
Enter temporary password from step 3 when prompted
Change temporary password
ALTER USER 'root'@'localhost' IDENTIFIED BY 'new_password';
Test to make sure new password worked
exit
mysql -u root -p
Enter new password when prompted
Create a database
     CREATE DATABASE giraffe_db;
Done!
