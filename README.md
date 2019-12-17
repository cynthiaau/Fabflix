# Fabflix

About:
Movie-service website where users can browse, search for, and purchase movies.

Tools: Java, SQL, JavaScript, HTML, CSS, jQuery, Ajax, REST

Running:
1. Clone each micro-service repo
2. Open a terminal for each micro-service and navigate to each micro-service folder
3. Build each micro-service
    ./gradlew clean --refresh-dependencies build
4. Start each micro-service with the yaml file (jar name different for each micro-service)
    java -jar build/libs/[jarfile] -c [name of yaml file]
5. Navigate to URL specified in yaml file
    http://[URL]:[PORT]/index.html
