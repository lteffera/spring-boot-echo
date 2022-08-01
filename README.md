# spring-boot-echo
<h1>This repo contains a take-home assignment for CMU research programmer position.</h1>
Here are a few additional notes about the app: 

1) The app is configured to run via gradle, but I can make it into
an executable jar file if that's preferable. 

2) The url of the endpoint is http://localhost:8080/message. 
To make a post request in the terminal, run the following command: 

`curl -X POST -H "Content-type: application/json" -d "MESSAGE_TEXT_HERE" "http://localhost:8080/message"`

3) The app uses an older version of gradle (~6.5), so I am creating a version of this app that runs on maven. 
Please let me know if you have any questions, thanks! 

