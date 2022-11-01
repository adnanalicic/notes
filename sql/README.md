#### SQL
Change MySQL/MariDB password of user

`ALTER USER 'appointmentservice'@'%' IDENTIFIED BY 'appointmentservicepassword';`

####Create PostgreQSQL user and database
`sudo -u postgres psql`

`create database mydb;`

`create user myuser with encrypted password 'mypass';`

`grant all privileges on database mydb to myuser;`