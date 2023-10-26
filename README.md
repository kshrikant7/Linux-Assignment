# Linux-Assignment

Configure smtp in localhost.

Create a user in your localhost, which should not be able to execute the sudo command.

Configure your system in such a way that when a user type and executes a describe command from anywhere of the system it must list all the files and folders of the user's current directory.

Ex:- $ describe
$  content1 content2
Content3 content 4
Users can put a compressed file at any path of the linux file system. The name of the file will be research and the extension will be of compression type, example for gzip type extension will be .gz.
You have to find the file and check the compression type and uncompress it.

Configure your system in such a way that any user of your system creates a file then there should not be permission to do any activity in that file.

Note:- Don’t use the chmod command.
Create a service with the name showtime , after starting the service, every minute it should print the current time in a file in the user home directory.

Ex:-
sudo service showtime start   -> It should start writing in file.
sudo service showtime stop   -> It should stop writing in file.
sudo service showtime status -> It should show status.
