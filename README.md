# spring-boot-echo
<h1>This repo contains a take-home assignment for CMU research programmer position.</h1>
Here are a few additional notes about the app: 


1) The url of the endpoint is http://localhost:8080/message. 
To make a post request in the terminal, run the following command: 

`curl -X POST -H "Content-type: application/json" -d "MESSAGE_TEXT_HERE" "http://localhost:8080/message"`

2) I wasn't able to successfully create an image from the Dockerfile. This is most likely because I didn't have Docker on my laptop, and attempted to run the following command while Docker was loading: 

`docker build --build-arg JAR_FILE=build/libs/demo-0.0.1-SNAPSHOT.jar -t spring/demo.`

3) The app is configured to run via gradle, and uses Java 11.


