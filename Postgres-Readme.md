HOW TO CREATE NEW USER IN POSTGRESS

Login as Postgres User(root user):       sudo -i -u postgres

Create another User:                     createuser --interactive

It ask of Inputs: 

                      Enter name of role to add:  newuser
                      Shall the new role be a superuser? Y
                      
Check the New User Created and its poermissions:              

psql                      #enter postgres environment as postgres user or root user

\du                       #List the users created.


HOW TO CREATE A NEW DATABASE:

Login as Postgress User:             sudo -i -u postgres

Create a new database:               createdb newdata

Check if the New database is created:

psql                  #enter postgress environment

\l                    # List of databases


Change Password:

\password




