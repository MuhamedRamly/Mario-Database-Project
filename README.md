# Mario-Database-Project
This repository hosts the project of a Mario database project, and my notes on the project.

- the project uses the Psql terminal application.
- for logging in use the command:
--username=UserName --dbname=postgres
  #note no spaces between the equals.
  
  # prompt window commands:
  \l 	#lists available databases
  
  \c database_name 	#connects to the database database_name
  
  \d 	#displays the tables within a database
  
  \d table_name 	#displays the table table_name schema
  
  \dt #displays the tables within a database
  
  \du (or \du+ or \dg) #Lists all roles (users) in the PostgreSQL database cluster. Adding + after \du provides more details about each role.
  
  \password #Allows you to change the password of the currently logged-in PostgreSQL user.
  
  \i filename #Executes commands from a SQL script file (filename).
  
  \q (or \quit) #Quits the psql command-line interface and disconnects from the PostgreSQL server.
  
  \timing #Toggles the display of the query execution time on or off.
  
  ? #Displays a list of available psql commands with brief descriptions.
  
  
