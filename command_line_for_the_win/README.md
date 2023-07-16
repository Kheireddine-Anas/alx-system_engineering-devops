#Command line for the win

Description
This project is a part of the CMD Challenge, focusing on improving command-line skills. The objective of this project is to complete various tasks using the command line and demonstrate the use of the SFTP command-line tool for file transfer.

#Installation

Clone this repository:

git clone https://YOUR ACCES TOKEN@github.com/Kheireddine-Anas/alx-system_engineering-devops.git
Change into the project directory:

cd repo-name
SFTP File Transfer
To transfer files from your local machine to the sandbox environment, follow these steps:

Take screenshots of the completed levels as mentioned in the project requirements.

Open a terminal or command prompt on your local machine.

Use the SFTP command-line tool to establish a connection to the sandbox environment. Replace "hostname", "username", and "password" with the provided information:

sftp Your_USERNAME@alx-cod.online

Enter the password when prompted to authenticate and establish the connection.

Once connected, navigate to the directory where you want to upload the screenshots in the sandbox environment. For example:


cd /root/alx-system_engineering-devops/command_line_for_the_win/
then go to your local files where your JPG or PNG Images located, In ma case:
lcd C:\Users\anask\OneDrive\Bureau\Git\

Then Use put commande to uplaod the JPG or PNG files to uplaod it from your local machines to your sandbox.

1- put 0-first_9_tasks.jpg

2- put 1-next_9_tasks.jpg

3- put 2-next_9_tasks.jpg

Confirm that the screenshots have been successfully transferred by checking the sandbox directory.

Push the screenshots to your GitHub repository, making sure to include them in the "command_line_for_the_win" directory.
