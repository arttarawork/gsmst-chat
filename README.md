gsmst-chat
==========



Install Instructions 
==========
Setup a MySQL DB

Run the database_setup.sql on that database

Install NodeJS on the server

Run the Node package install in the directory that you downloaded the server files to. (there should be a node_modules folder in the same folder as the nodejs folder)

Modify and place the config.json in the nodejs folder

	a.mysql - The information for the mysql database
	b.mail - The email user that the mail is sent from
	c.dir - The absolute directory of the public folder
Run the server with "sudo node nodejs/server.js >> logfile.log 2>&1 &"
