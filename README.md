1. Open your Docker.
2. Open the code in VSCode. 
3. Make sure you put the proper database name and credentials on database.js located at the folder config.
4. Open you mySQL Workbench and create new conenction with the port and credentials that you have entered.
5. After making sure Docker is already running in your unit, Right Click the docker-composer.yml file and 
    choose Compose Up.
6. Wait for the process to be completed. To check if it has been successfully deployed or there are no errors,
    go to Docker extension on VSCode and under Containers right-click the container and choose View Logs.
7. After you finished using or editing the code you need to turn off the container by right click the 
    docker-composer.yml and choose Compose Down.

