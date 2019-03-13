## Needed stacks
    + maven 3
    + java8
    + scalyr
    + newrelic

## To get started follow this checklist:
    + change api key scalyr in logback.xml
    + see log in scalyr web
    + put newrelic.yml same dir with app.jar and newrelic.jar
    + edit newrelic.yml (change api key and name apps)
    + java -javaagent:newrelic.jar -jar app.jar
    + see in newrelic web
   
