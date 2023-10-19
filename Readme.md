
# fun with WordPress

  ## Purpose: Create a contact form to email site admin
  With a secondary purpose of catching up on WP 

## Prerequisites: 
	VS Code 
	Docker Desktop 
 

## Setup:  
 From the command line install docker WordPress image: 

     $ docker pull wordpress

## Start the dev environment
From VSCode Terminal fire up the WP instance like so

	 docker-compose -f .\docker-compose.yml up
     then browse to ~~http://localhost:8080/~~
this complains a lil on first run, because te db has been initialized. No worries