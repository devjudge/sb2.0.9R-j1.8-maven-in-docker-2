# Spring Boot Maven

PROJECT START STEPS:

    Pre-requisites:
    1. Java must be installed
    2. Install maven module (https://maven.apache.org/install.html).

    Steps:
    1. To run this application, do the following:
        1.a. Go to the project root directory.
        1.b. Run the following commands in the terminal/command line to build the app:
            - mvn clean install
        1.c. Run the following command(s) in the terminal/command line to run the app:
            - java -jar ./target/spring-boot-in-docker.jar

    2. Go to http://localhost:8080/ in your browser to view it.
    
    CLOUD-IDE SETUP STEPS(follow the below steps in case you are using the Cloud IDE instead of your Local IDE):
    1. Please run the below command from the project root to setup MySQL and MongoDB in this workspace:
        - sh ./database-setup.sh
