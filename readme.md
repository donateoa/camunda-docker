# Camunda BPM

Open terminal and  run

````
docker-compose up -d
````

Open your browser and access URL
````
 http://localhost:8080/manager/html
````
in the login form type username: `tomcat` and password `tomcat`.

If you want change user and password update the file tomcat-users.xml in this folder.

here are the application available under tomcat service.
1. `/camunda`: workflow engine.
2. `/camunda-invoice`: standard example of BPMN.
3. `/demoWeather`: custom example of BPM.
4. `/engine-rest`: REST API of camunda.
