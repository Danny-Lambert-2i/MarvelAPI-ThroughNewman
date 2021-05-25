# MarvelAPI-ThroughNewman
Running the API call and tests through command line in VS code 

<<< Command to run to get the postman collection to run >>>
<<< Start with docker run -v >>>

<<< Get relative path of the folder to put in --
C:/Users/DannyL/Documents/development/marvelApiDocker/newman (right click the folder name on the left and copy path of file)>>>

<<< Followed by '':/etc/newman postman/newman run' >>>

<<< Followed by the link gathered from the postman collection Share option >>>

<<< Followed by '-e env.json' - this is the name of the json file >>>

<<< So the full command is below >>>>>
docker run -v C:/Users/DannyL/Documents/development/marvelApiDocker/newman:/etc/newman postman/newman run https://www.getpostman.com/collections/5ee01326486d3d74fd31 -e env.json
