This is a simple program to track and maintain software requirements,
I have just started the project, but the general ideas are:

sqlite database     --create a new database file for each project
                    --database schema will be in a sql file so when a new 
                      project is created we can create the bare database
hosted database     --option to have a projects requirements on a postgresql
	              server for a shared project
requirements        --have a title, user story, and notes section
	            --can be related to other requirements parent-child
acceptance criteria -- have title(scenario for cucumber style), description,
		      notes section, related to a requirement
display on screen
sort
filter
export to csv
export html

