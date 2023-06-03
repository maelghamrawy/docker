# docker
Docker lab 3
1. Problem 1:
    Create bridge network with subnet 192.168.0.0/24.
    Run 2 containers and attach containers to this network.
    ![Screenshot 2023-06-03 015148](https://github.com/maelghamrawy/docker/assets/28117071/ba62c98a-a688-4c19-845c-5b57268d20f3)

    Create another bridge network with subnet 10.5.0.0/24.
    Run any container and attach it to the new network.
    ![Screenshot 2023-06-03 015803](https://github.com/maelghamrawy/docker/assets/28117071/e4065a7e-aaaf-4f27-adaa-69d169751927)

    Make sure that the containers at different network can’t ping each other
    ![Screenshot 2023-06-03 015828](https://github.com/maelghamrawy/docker/assets/28117071/c39c46a7-d8c5-4690-9812-6fc79ab96c79)


2. Problem 2:
    Create static html file
    Write Dockerfile to build image based on httpd to host the html file and
    specify the following
    Copy the html file.
    Copy a new configuration file to listen on port 9999 instead of 80
    Open the port 9999 in the container
    Add environment variable CONTAINER with value docker .
    Add startup command to echo the variable
    ![Screenshot 2023-06-03 021543](https://github.com/maelghamrawy/docker/assets/28117071/56934736-3793-4cc5-a324-b58acdb59a49)

    ![Screenshot 2023-06-03 021416](https://github.com/maelghamrawy/docker/assets/28117071/abd38eff-9449-4aff-a964-99c37f96169c)

    

 3. Problem 3:
    Create a docker compose to up mysql container, and
    https://github.com/sabreensalama/dockerize-node-app-task which depend on mysqldb.
    Add volume for mysqldb
    ![Screenshot 2023-06-03 023301](https://github.com/maelghamrawy/docker/assets/28117071/679480d2-7425-483a-bf33-b25a88d58144)
    ![Screenshot 2023-06-03 023203](https://github.com/maelghamrawy/docker/assets/28117071/a88b153a-ddcb-4a28-b424-9c0f62f7dcab)
    
  
4. Problem5:
    Use docker compose to deploy ghost platform (image: ghost:1-alpine)(Ghost is a free and open source blogging platform written in JavaScript)
    Use mysql database instead of sqlite
    
    i dont know what is the proplem
    ![Screenshot 2023-06-03 024714](https://github.com/maelghamrawy/docker/assets/28117071/6b70d23d-d306-4bcb-b1c0-d2752516a63a)


