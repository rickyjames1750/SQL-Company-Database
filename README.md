# sqldatabase
SQL Database

# Instructions
1. Download mySQL Community Server - https://dev.mysql.com/downloads/mysql/

2. Run installer

3. Write down temporary password

4. Open ‘MySQL’ in System Preferences and start the server

5. Configure command line to recognize ‘mysql’ command

echo ‘export PATH=/usr/local/mysql/bin:$PATH’ >> ~/.bash_profile
. ~/.bash_profile

6. mysql -u root -p

6.Enter temporary password from step 3 when prompted

Change temporary password

7. ALTER USER 'root'@'localhost' IDENTIFIED BY 'new_password';

8. Test to make sure new password worked

exit

mysql -u root -p

Enter new password when prompted

9. Create a database

     CREATE DATABASE giraffe_db;

10. Done!
