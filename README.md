# Docker Flask MariaDB tech demo
This is a tech show-case for a frequently used tech stack. Flask is an amazing way to quickly serve data from a Python application to a website but the runtime can be annoying. This is where Docker comes into play.

## How to get started

Simply clone the repository, open the command line tool of your choosing and navigate to the folder where you cloned the repo. Then run the following command:
```
docker-compose up -d
```
This will pull the remaining components from the world wide interweb and compile everything. It will also read the requirements.txt file and install all Python packages mentioned there.

## See if it works
After checking your Docker if application is alive, simply go to your browser and go to your [http://localhost](http://localhost:80) location, where the Flask application is served.